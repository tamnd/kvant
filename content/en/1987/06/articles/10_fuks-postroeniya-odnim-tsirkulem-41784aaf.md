---
id: 1987-6-fuks-postroeniya-odnim-tsirkulem-41784aaf
issue: kvant_1987_6
year: 1987
number: "6"
title: Constructions with one compass
authors:
  - Фукс Д. Б.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 36
page_last: 38
page_labels: 34-36
tag: C8ZZ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8ce02ac7304f49fb75fd2cd2f5237b154086e21aca46e5d2e20e1ad0cd8b0f8f
prompt_sha256: draft-1
translated_from: content/ru/1987/06/articles/10_fuks-postroeniya-odnim-tsirkulem-41784aaf.md
source_content_sha256: d0177bbb1a84cc7b716d5c8f7c4f2565f5a3e903e6390492612f4af622586713
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

Constructions
with one compass

Candidate of Physical and Mathematical Sciences
D. V. FUCHS

Among the countless construction problems, there are also those in which the construction needs to be done with one ruler or one compass. However, it has long been known that in the absence of a ruler there is no range of possible constructions: any construction performed with a compass and a ruler can be done with one compass.

The idea of ​​constructing using a single compass was advanced by the Italian scientist Giovanni Battista Benedetti (1530-1590). In 1672, the book “Euclidus Danicus” by the Danish geometer Georg Mohr (1640-1697) appeared. In it, he showed that all problems that can be reduced by a quadratic equation can be solved geometrically using one compass. More than 100 years later, in 1797, this problem was rebuilt and solved by the Italian Lorenzo Mascheroni (1750-1800). The corresponding statement is called the Mohr–Mascheroni theorem.

In this note we will provide a proof of this theorem.

In all construction tasks solved below, we limit ourselves to a description of the construction itself, leaving the reader to independently prove that the construction leads to the desired goal. However, the evidence is given in the section “Answers, instructions, solutions” on p. 58.

1. Formulation of the result. Of course, it is impossible to check a straight line with a compass, so all construction tasks under consideration must consist of constructing a certain point (on the plane).

Theorem. Let us assume that point M can be constructed from points $A_1$, ..., $A_n$ using a compass and ruler. Then the point M can be constructed from the points $A_1$, ..., $A_n$ using one compass.

To prove this theorem, let's construct some constructions of the product with a ruler. Using a ruler, you can check a straight line through two given points and find its points of intersection with previously constructed straight lines and circles. But since from the very beginning we had given points, every previously constructed straight line was sometimes checked through even earlier constructed points, and every

⟦folio 35⟧

a previously constructed circle has a previously constructed point as its center. Thus, during the construction process, the ruler is applied only to solving one of the following two problems.

Task 1. Given points A, B, C, D, find the point of intersection of lines AB and CD.

Problem 2. Given the center O and the given points A and B, find the point of intersection of the circle S with the line AB.

Our theorem will be proven if we establish that both of these problems can be solved using one compass.

2. Auxiliary constructions. In this and the next paragraphs, when we say “construction,” we mean construction with one compass. We'll start by solving four auxiliary problems.

Problem 3. Given (different) points A and B. Construct a point C on the ray AB such that AC=2AB.

Construction (Fig. 1). Let us draw a circle with center B through point A. On this circle we plot segment AB three times, starting from point A. The resulting point C after the third postponement satisfies the requirements of the problem.

Problem 4. Given a circle with center O and arm AB on it. Construct a point dividing this arc in half.

Construction (Fig. 2). Through point O we draw circles with centers A and B. Let us draw a circle with center O and radius AB. Let's take two points: P and Q, the intersections of this circle with the two constructed ones; then the arcs OP and OQ are equal to the arc AB. Then through points B and A we draw circles with centers P and Q until they intersect at point R. Finally, with radius OR we draw a circle with center P or Q. The point C of the intersection of this circle with arc AB will be the desired one.

Problem 5. Given a circle S with center O and point P≠O. On the ray OP, construct a point P′ such that OP·OP′=r², where r is the radius of the circle S.

(Such a point P′ is called symmetrical to the point P relative to the circle S.)

Construction. Listen 1. Point P lies outside the circle S (Fig. 3). Let us draw a circle with center P through the point O. Let Q and R be the points of its intersection with the circle S. Let us draw circles with centers Q and R through the point O. The intersection point of these circles different from O is the desired point P′.

(This construction also works in the case when point P lies inside the circle S, but is located from its center O at a distance greater than r/2.)

Listen 2. Point P lies inside the circle S. Using problem 3, we successively construct on the ray OP the points P₂, P₃, ... such that OP₂=2OP, OP₃=3OP, ... until we reach the point Pₙ, which will lie in S. For the point Pₙ we build a point P′₁ that is symmetric with respect to the circle S, use the previous construction. Finally, on the ray OP′₁ (i.e. on the ray OP) we construct points P′₂, P′₃, ... such that OP′₂=2OP′₁, OP′₃=3OP′₁, ... Point P′ₙ will be the required one.

Problem 6. Given a circle S with center O and divergent points A, B. Construct a circle passing through point O and the points of intersection of line AB with circle S (within the assumption that line AB does not pass through the center of circle S and intersects it at two points). Prove that this circle, minus the point O, is a locus of points symmetrical

⟦folio 36⟧

points of line AB relative to circle S.

Construction (Fig. 4). Let us draw circles with centers A and B through point O. We denote their intersection point, different from O, by P. Construct a point P′, symmetrical to point P relative to the circle S (task 5), and construct a circle with center P′ passing through O. This is the desired circle.

3. Basic constructions. Construction for task 2. If the point O does not lie on the straight line AB, we proceed with the construction of task 6 and even its simplified version: we build point P, as in task 6, and then draw a circle with a center P of radius equal to the radius of the circle S (meaning the center of the circle is S, we can change the radius of the circle with a cyclel); the points of intersection of the constructed circle with the given circle are the required points. If point O lies on straight line AB, then this construction will not work: point P will merge with point O. Then we use another construction (Fig. 5): with center A (or with center B, if A=O) we draw an arbitrary circle intersecting the circle S at two points, denote the intersection points by C and D and divide each CD and DC of the circle S in half (task 4). The division points will be the ones we are looking for.

Construction for task 1 (Fig. 6). Let us construct an arbitrary circle S, which contains all the given points inside and whose center O does not lie on any of the lines AB and CD. (This is easy to do “by eye”, but for “rigorous construction” such a sieve is not suitable. You can construct it like this: construct an arbitrary circle, find, using the construction of task 2, the points of its intersection with straight lines AB and CD and take as O a point of the constructed circle that is different from the found points.) Then, using the construction of task 6, we construct a circle S₁ passing through O and through the points of intersection of the circle S with the straight line AB, and a circle S₂, passing through O and through the points of intersection of the circle S with the line CD. Then we denote by P the intersection point of the circles S₁ and S₂, different from O, and construct a point P′, symmetrical to the point P relative to the circle S. This is the desired point.

4. Concluding remarks. 1°. If the given construction task involves more than just points, a ruler may be necessary to solve it. For example: given curve c and points A, B; find the points of intersection of curve c with line AB. This, generally speaking, cannot be done without a ruler. However, it happens that similar assignments of properties to those of the type considered are solved with one loop. For example: a circle is drawn on a plane; use one cyclel to find its center. This can be done like this: mark three points A, B, C on the circle; as you know, with a cyclel and a ruler you can construct the center of a circle circumscribed about triangle ABC; This means that this can be done with one cyclel. (However, the problem has cities and a simpler solution is to find it!) We see, by the way, that in the given 2, 4, 5 and 6 it was not necessary to indicate the center of the given circle.

2°. Not every construction can be done with a ruler alone; do it with a looper and a ruler. (For the proof, see the book: Rademacher G. and Teplitz O. Numbers and Figures. - M.: Nauka, 1966.) There is, however, an amazing theorem of Steiner, according to which all constructions performed by a cyclel and a ruler can be done with one ruler, if a circle is first drawn on the sheet and its center is marked.
