---
id: 1973-2-kreyn-nudelman-o-nekotoryih-prostranstvennyih-izoperimetricheskih-zadachah-e80e31ee
issue: kvant_1973_2
year: 1973
number: "2"
title: On some spatial isoperimetric problems
authors:
  - Крейн М. Г.
  - Нудельман А. А.
rubric: osnovnye-stati
page_first: 24
page_last: 28
page_labels: 22-26
tag: U1OU
lang: en
source: kvant_digital
extraction: vision
content_sha256: 33390af7ff45553291c0e44181d9267ccefa96e85e49fb6e5a2d058f265caba2
prompt_sha256: draft-1
translated_from: content/ru/1973/02/articles/06_kreyn-nudelman-o-nekotoryih-prostranstvennyih-izoperimetricheskih-zadachah-e80e31ee.md
source_content_sha256: 191c48e398b05c6b98fa2327876c790821d10b07c9690952443d4a764066bf0d
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 22⟧

On some spatial isopermetric problems

M. G. Krein, A. A. Nudelman

Introduction

Before proceeding to the subject of this article, we invite the reader to independently prove (or remember) the following well-known propositions.

Sentence 1.
Among all parallelograms with a given perimeter, the square has the largest area.

Proposal 2.
Among all parallelograms with a given perimeter and the length of one of the diagonals, the rhombus has the largest area.

Obviously, Proposition 2 is equivalent to the following:

Proposition 2'.
Among all triangles with a given perimeter and the length of one of the sides, the area of ​​the largest is an equilateral triangle.

Proposal 3.
Among all triangles with a given perimeter, the equilateral triangle has the largest area.

Propositions 1-3 are among the so-called isopermetric problems: among figures of a defined type with a given perimeter, it is required to find figures with the largest area. Let us note here that Propositions 1 and 3 are special cases of a more general statement: among all $n$-gons with a given perimeter, the equilateral $n$-gon has the largest area. From it we propose a transition to easily obtain that among all figures with a given perimeter (the type of figures does not overlap with the area limited by the largest area, the circle has *).

Setting goals

Let us now consider the extended analogues of propositions 1-3; in them, parallelograms are replaced by parallelipeds, triangles by tetrahedrons (triangular pairs), and areas by volumes.

Task 1. Among all parallelipeds with a given sum of edge lengths, find the paralleliped that has the largest volume.

Task 2. Among all parallelipeds with a given sum of edge lengths and the length of one of the diagonals, the area has the largest volume.

Before reformulating Problem 2 so as to obtain an analogue of Proposition 2', let us introduce some definitions.

A closed broken line consisting of four links, the vertices of which do not lie in the same plane, is called a spatial quadrilateral. About a tetrahedron whose vertices coincide with the vertices of a spatial quadrilateral, we will say that it is named after this quadrilateral (Fig. 1).

It is easy to see that the volume of a tetrahedron spanned by the spatial

*) The reader will find an elegant proof of this statement, which does not use the passage to the limit, in the book: G. Rademacher and O. Toeplitz. Numbers and Figures, M., Fizmatgiz, 1962.

⟦folio 23⟧

A quadrilateral whose sides are the diagonal of the parallelepid and its three consecutive edges (Fig. 2) constitute one sixth of the volume of the parallelepid. Therefore task 2 includes the following task:

Task 2'. Among all spatial quadrilaterals with a given perimeter 2p and the length of one of the sides h, find that we need the metrahedron to have the most volume.

Once solved, this problem is easily solved.

Task 3. Among all spatial quadrilaterals with a given perimeter 2p, find the maximum volume that we need for a metrahedron.

Problem solving

Solution to problem 1

Since among parallelograms with fixed lengths the rectangular paralleloped has the largest side area, and among parallelopeds with fixed edge lengths the rectangular paralleloped has the most volume, then when solving Problem 1 it is enough to consider rectangular parallelopeds.

Fig. 2.

Fig. 3.

If the lengths of the edges of a right paralleloped are denoted by $a_1, a_2, a_3$, then the well-known inequality between the arithmetic mean and the geometric mean

$$\sqrt[3]{a_1 a_2 a_3} \leq \frac{1}{3} (a_1 + a_2 + a_3)$$

(where the equal sign occurs only in the case of $a_1 = a_2 = a_3$) leads to the following result:

Theorem 1. Among all parallelopeds with a given sum of edge lengths, the cube has the largest volume.

Solution to problem 2'

Let's start considering problem 2'. To solve it, the following auxiliary sentence will be used.

Let us denote by П the plane perpendicular to side AB of the spatial quadrilateral ABCD (Fig. 3). Projecting ABCD onto P, we obtain triangle BEF.

Lemma 1. The volume V of the metrahedron, we need on ABCD, is calculated by the formula

$$V = \frac{1}{3} h S,$$

(1)

food $h - \text{dлина стороны } AB, S - \text{ площадь треугольника } BEF$.

To prove this, it is enough to note that the ABCD and ABEF terzers are equal in size, since each of them is equal in size to the ABCF terzer.

Formula (1) immediately suggests the solution to problem 2': you need the lengths and positions of side BC, CD and

⟦folio 24⟧

Fig. 4.
AD (Fig. 3) should be chosen so that the area of ​​the triangle BEF is the widest possible.

To achieve this, we first make sure that its perimeter is as wide as possible. Let us unfold the faces ABFD, FDCE, CEB onto the plane, projecting the quadrilateral ABCD onto the plane P. In the resulting system of a plane figure (Fig. 4), the length of the side $B_1B_2$ is equal to the perimeter of the triangle BFE, whence it is clear that this perimeter will be the widest in the case when the segments AD, DC, CB form the same angle $\alpha = \arccos \frac{h}{2p-h}$ from the side AB (Fig.5). Thus, a spatial quadrilateral from side $AB = h$ and perimeter $2p$, for which triangle BEF has the widest perimeter, can be obtained as a result of the following construction: a rectangle from side $AB_1 = h$ and diagonal $AB_2 = 2p - h$ is folded into a triangular prism so that points $B_1$ and $B_2$ coincide, and its the side edge is the segment $AB_1$. In this case, line $B_1ADCB_2$ turns into the original spatial quadrangle.

Solution to problem 3

Let's calculate the maximum volume discussed in Theorem 2. From figure 5 we see that the perimeter of triangle BFE is equal to $\sqrt{(2p-h)^2-h^2} = 2\sqrt{p(p-h)}$, which means its maximum area is $\left[\frac{2\sqrt{p(p-h)}}{3}\right]^2 = \frac{p(p-h)}{3\sqrt{3}}$;

finally, the maximum area of ​​the formed tetrahedron, in accordance with formula (1), is equal to

$$V = \frac{1}{3}h \frac{p(p-h)}{3\sqrt{3}} = \frac{p}{9\sqrt{3}}h(p-h).$$

Now problem 3 can be easily solved. It differs from problem 2' in that it specifies the molecular perimeter of the quadrilateral.

⟦folio 25⟧

Obviously, to solve it, it is enough in the previous problem to set the value $h$ at which the right side of formula (2) takes on the greatest value. This value of $h$ is found using the inequality between the argmetic mean and the geometric mean:

$$h(p-h) \leq \left[ \frac{h+(p-h)}{2} \right]^2 = \frac{p^2}{4};$$

it is equal to $\frac{p}{2}$, since $h = p - h$ is precisely at $h = \frac{p}{2}$. This implies the solution to problem 3:

Theorem 3. The average of metrahedrons, oriented on the space of quadrilaterals with a given perimeter, the largest volume is a metrahedron oriented on a quadrilateral, in which all sides are equal and the angles formed by any pair of sides are equal.

Indeed, if $h = \frac{p}{2}$, then the length of each of the other three sides is $\frac{2p-h}{3} = \frac{p}{2}$; the equality of angles can be obtained directly by calculating (since $h = \frac{p}{2}$, then all angles are equal to arccos$^1/3$), but it is easier to notice that in the quadrilateral under consideration all sides are equal.

By means that go beyond elementary mathematics, it is possible to prove that a parallelepid that gives a solution to problem 2 also gives a solution to the following problem: under the same conditions, find a parallelepid with the most given total surface.

Some generalizations

Formula (1) can be generalized to bodies of a more complex shape than a tetrahedron, and allows us to solve problems similar to problems 2 and 3 for such bodies in a similar way: reducing the spatial isopermetric problem to a plane isopermetric problem.

Let some $n$-dimensional spatial broken line $A_0 A_1 \dots A_n$ be given. We will say that it is a simple frame if the entire plane passing through its ends $A_0$ and $A_n$ has at most one common point with the broken line $A_1 A_2 \dots A_{n-1}$.

About a polyhedron whose faces are triangles $A_0 A_1 A_2$, $A_0 A_2 A_3$, ..., $A_0 A_{n-1} A_n$ and triangles $A_n A_0 A_1$, $A_n A_1 A_2$, ..., $A_n A_{n-2} A_{n-1}$, we will say that it is attached to a given simple frame (Fig. 6) (the indicated faces form its “compartment”).

Since a polyhedron spanned by a simple frame can be composed of tetrahedra $A_0 A_1 A_2 A_n$, $A_0 A_2 A_3 A_n$, ..., $A_0 A_{n-2} A_{n-1} A_n$, to each of which Lemma 1 applies, then it is true.

Lemma 2. The volume $V$ of a polyhedron attached to a simple frame is calculated by the formula

$$V = \frac{1}{3} h S,$$

food $h$ is the distance between the ends $A_0$ and $A_n$, $S$ is the area of ​​the polygon $A_0 A_1^2 \dots A_{n-1}^2 A_n$ ($A_n^2 = A_0^2$), which is the projection of the frame onto the plane P, perpendicular to the straight line $A_0 A_n$.

Using the same example as in the proof of Theorem 2, the reader can easily prove, based on the solution of the isopermetric problem for $n$-gons, the following theorem:

Theorem 4. Average polyhedra, referred to simple $n$-vein frames $A_0 A_1 \dots A_n$ with a given distance $h$ between the ends, the most given one is a polygon, referred to a frame, located on the lateral faces of the right n-y prism, in which the segment $A_0 A_n$ serves as an edge, and the base is argmeter $\sqrt{L^2 - h^2}$; in this case, the sides of the frame form equal angles $\alpha = \arccos \frac{h}{L}$ with $A_0 A_n$.

⟦folio 26⟧

Thus, the maximum volume is equal to
$$\frac{1}{12} h (L^2 - h^2) \frac{1}{n} \text{ctg} \frac{\pi}{n}.$$
If we do not fix the distance between the ends of the frame, then it immediately follows from Theorem 4.

Theorem 5. Among all the polyhedra we need for simple n-link frames of a given length L, the most volume we have is the polyhedron we need for the frame, located on the side faces of the right n-link prism with a height of $\frac{L}{\sqrt{3}}$ and a base perimeter of $L \sqrt{\frac{2}{3}}$, and the sides of the frame form with a prism height equal to α = $\arccos \frac{1}{\sqrt{3}}$. This is the most volume equal to
$$\frac{1}{18 \sqrt{3}} L^3 \cdot \frac{1}{n} \text{ctg} \frac{\pi}{n}.$$

It is known that among n-gons with a given length of sides, the one with the largest area is the one that can be inscribed in a circle. Using this fact, the reader will be able to prove that among all the polyhedra, we need simple n-link frames with a given length of links $a_1, a_2, \dots, a_n$ and distance h between the ends, the most volume has a polyhedron, we need a frame located on the side faces of the prism with height h, sides of the base $b_k = a_k \frac{\sqrt{L^2 - h^2}}{L} (k=1, 2, \dots, n)$, where $L = a_1 + a_2 + \dots + a_n$, and the base of the prism can be inscribed in a circle.

Let us now abandon the requirement that the frame be necessarily composed of straight segments: we will consider “smooth” spatial curves. A curve is called smooth if a tangent can be drawn at each of its points and the direction of the tangent “smoothly” changes with small changes in the position of the tangent point. Thus, we do not consider curves with “kinks,” although at the cost of slightly complicating the presentation it would be possible to extend the results to such curves. A smooth spatial curve AB is called a simple smooth frame if every plane passing through the ends A and B has at most one common point with it.

Let point M move along a simple frame. Then the segments AM and BM will omit certain surfaces that make up the “skin” of the frame; about a body bounded by a “skin”, we will continue to say that it is stretched over a frame (Fig. 7).

Using the passage to the limit, it can be shown that the volume of a body stretched over a smooth simple frame is also calculated

Fig. 7.

is calculated according to formula (1), in which S now denotes the area of ​​the figure limited by the projection of the frame onto the plane Π. The nature of the transition to the limit is intuitively clear: it is necessary to replace the smooth frame “close” to it with broken ones; however, carrying out accurate calculations is a rather scrupulous matter.

Using the isoperimetric property of a circle, we can, as above, verify the validity of the following theorem:

Theorem 6. Among all the chalk, we need simple smooth frames with a given length L and a given distance h between the ends, the most volume we have we have, we need a frame, which is one helix with a step h, located on a circular cylindrical surface with a base radius $\frac{\sqrt{L^2 - h^2}}{2\pi}$ (Fig. 7).

Theorem 7. Among all the chalk, we need for simple smooth frames with a given length L, the most volume we have we have, we need for a frame, which is one coil of a helix with a step h = $\frac{L}{\sqrt{3}}$, located on a circular cylindrical surface with a base radius $\frac{\sqrt{L^2 - h^2}}{2\pi}$.
