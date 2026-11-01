---
id: 1979-8-lopshits-vektornoe-reshenie-affinnyih-zadach-9f8c84cc
issue: kvant_1979_8
year: 1979
number: "8"
title: Vector solution of affine problems
authors:
  - Лопшиц А. М.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 32
page_last: 35
page_labels: 30-33
tag: QZ3X
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5d69dddffb99d3338b53831122a13aca0874b38f48a49801c2b5bf87944a6bf2
prompt_sha256: draft-1
translated_from: content/ru/1979/08/articles/10_lopshits-vektornoe-reshenie-affinnyih-zadach-9f8c84cc.md
source_content_sha256: 2d0eb0bcb2d06500dce796a43211d48ee00c4f69edfe38cea6479fc67dd04570
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 30⟧

Vector solution of affine problems

In this math circle lesson, we will learn how to solve geometric problems of a certain type - the so-called affine problems. We will not explain in advance what these tasks are. We hope that after reading the article you will understand this.

1. Affective version of Morley's theorem

In «Kvant» No. 8 for 1978 (p. 28) the following remarkable theorem was considered: if in a triangle ABC the trisecgrises of angles A, B and C are drawn, then their points of intersection, close to the sides, are the vertices of an equilateral triangle. What happens if trisecgris are replaced with tris, that is, straight lines passing through the vertices of the triangle and dividing its opposite sides into three equal parts? It turns out... However, the real reader himself will finish the formulation of the theorem, find out the properties of the triangle $P_{14}P_{36}P_{25}$ (the notation is easy to communicate, saying

Fig. 1

on figure 1), will verify that the sides of the hexagon $P_{13}P_{46}P_{15}P_{24}P_{35}P_{26}$ are parallel to the sides of the original triangle ABC, and finally prove that the midpoints of the side of this hexagon and the points $P_{36}, P_{23}, P_{25}, P_{45}, P_{14}, P_{61}$ lie on three straight lines. If you don’t yet understand how to solve this problem, don’t worry. After reading the article, you will undoubtedly be able to do this. Let's start with a simpler task.

2. Lewis Carroll's Affinity Problem

The penultimate problem in the collection “March-day problems invented during sleepless hours” *) requires writing a hexagon in a given triangle such that its opposite sides are equal and parallel, three of them lie on the sides of the triangle, and the diagonals intersect at a given point inside the triangle. The solution given by Carroll uses the means given for a schoolchild of those ancient times (the eighties have passed centuries). We will consider a more general formulation of Carroll's problem and solve it using a tool familiar to a complete schoolchild from the seventh grade - in which. Of course, Carroll's problem is not at all difficult to solve without their help. But precisely because it is not difficult, you learn well from it!

We will solve Carroll's problem in the following formulation: on the lines containing sides BC, CA and AB of triangle ABC, we will place, correspondingly, the points $A_1$ and $A_2$, $B_1$ and $B_2$, $C_1$ and $C_2$ so that the opposite vertices of the hexagon $A_1A_2B_1B_2C_1C_2$ (i.e. points $A_1$ and $B_2$, $A_2$ and $C_1$, $B_1$ and $C_2$) were symmetrical about a point P, arbitrarily defined in the plane of triangle ABC (Fig. 2)**). (Such a hexagon is called central.)

*) Lewis Carroll. The Story with Knots (M., Mir, 1973).
**) This is the great generality of our formulation - Carroll believes that point P lies inside triangle ABC.

⟦folio 31⟧

3. Vector decomposition

We will need the following fact: if the vectors $\vec{a}$ and $\vec{b}$ are not collinear, then any vector $\vec{c}$ lying in the same plane as the vectors $\vec{a}$, $\vec{b}$ can be represented as

$$\vec{c} = \alpha \vec{a} + \beta \vec{b}$$

(here $\alpha$ and $\beta$ are real numbers), and such a representation is unique (cf. the theorem from § 23 of “Geometry 9”).

We will call this representation the decomposition of the vector $\vec{c}$ into the vectors $\vec{a}$ and $\vec{b}$ (Fig. 3).

Note that if $O$ is a fixed point of the plane, then the vector $\overrightarrow{OM}$ can be constructed at any point $M$ of the plane. The point $O$ is called the pole, the vector $\overrightarrow{OM}$ is the radius vector of the point $M$. The radius vector $\overrightarrow{OM}$ uniquely determines “its own” point $M$; we will denote it by $\overrightarrow{M}$ for brevity.

4. Solution of Carroll's problem

Let us choose the vertex $C$ of this triangle as the pole.

Let us expand the radius vector of a given point $P$ into vectors $\vec{A}$ and $\vec{B}$:

$$\vec{P} = \alpha \vec{A} + \beta \vec{B}.$$

Since the required point $A_1$ lies on the line $CB$ (Fig. 2),

$$\vec{A}_1 = x\vec{B},$$

where $x$ is the fraction that point $A_1$ “cuts off” from the directed segment $\overrightarrow{CB}$. We put the word “cuts off” in quotation marks because the point $A_1$ does not necessarily lie inside the segment $CB$; it can “cut off” even a negative “share” (in this case $x < 0$). Similarly, for the desired point $B_2$ we obtain

$$\vec{B}_2 = y\vec{A}$$

(here $y$ is the fraction that the desired point “cuts off” from the directed segment $\overrightarrow{CA}$). From the fact that the point $P$ is the midpoint of the segment $A_1B_2$, it follows (§ 22 “Geometry 9”)

$$\vec{P} = \frac{1}{2} (\vec{A}_1 + \vec{B}_2),$$

that is

$$\alpha \vec{A} + \beta \vec{B} = \frac{1}{2} (x\vec{B} + y\vec{A}),$$

where

$$x = 2\beta, y = 2\alpha$$

and therefore

$$\vec{A}_1 = 2\beta\vec{B}, \quad \vec{B}_2 = 2\alpha\vec{A}.$$

These equalities allow us to construct the points $A_1$ and $B_2$.

Finding the points $B_1$ and $C_2$ is a little more difficult. If point $B_1$ cuts off part $z$ from the directed segment $\overrightarrow{CA}$, then

$$\vec{B}_1 = z\vec{A}.$$

Let us now compose an expression for the radius vector of the point $C_2$, cutting off the fraction $u$ from the directed segment $\overrightarrow{AB}$:

$$\vec{AC}_2 = u\vec{AB}.$$

Let's use the fact that $\vec{AC}_2 = \vec{C}_2 - \vec{A}$; $\vec{AB} = \vec{B} - \vec{A}$. Therefore $u(\vec{B} - \vec{A}) = \vec{C}_2 - \vec{A}$ and therefore $\vec{C}_2 = \vec{A} + u(\vec{B} - \vec{A}) = (1 - u)\vec{A} +$

⟦folio 32⟧

+ $u\vec{B}$. By condition
$$P = \frac{1}{2} (\vec{B}_1 + \vec{C}_2),$$
that is
$$\alpha \vec{A} + \beta \vec{B} = \frac{1}{2} [z\vec{A} + (1 - u)\vec{A} + u\vec{B}]$$
and thus
$$u = 2\beta, z = 2\alpha + 2\beta - 1$$
$$\vec{B}_1 = (2\alpha + 2\beta - 1)\vec{A},$$
$$\vec{C}_2 = (1 - 2\beta)\vec{A} + 2\beta\vec{B}.$$
Perform the final stage independently, the reader will be convinced that
$$\vec{A}_2 = (2\alpha + 2\beta - 1)\vec{B},$$
$$\vec{C}_1 = 2\alpha\vec{A} + (1 - 2\alpha)\vec{B}.$$
We have thus discovered that Carroll's problem has a solution (no matter how the point $P!$ is specified) and this solution is unique:
$$\begin{cases} \vec{A}_1 = 2\beta\vec{B}, \vec{A}_2 = (2\alpha + 2\beta - 1)\vec{B} \\ \vec{B}_1 = (2\alpha + 2\beta - 1)\vec{A}, \vec{B}_2 = 2\alpha\vec{A} \\ \vec{C}_1 = 2\alpha\vec{A} + (1 - 2\alpha)\vec{B}, \vec{C}_2 = \\ = (1 - 2\beta)\vec{A} + 2\beta\vec{B} \end{cases}$$

5. A departure from Carroll's problem.
The derivation of the formula for $\vec{C}_2$ actually proves the following general result: if $\vec{A}$ and $\vec{B}$ are the radius vectors of arbitrary points $A$ and $B$ (relative to an arbitrary chosen policy $C!$), then the radius vector $\vec{M}$ of the point belonging to the line $AB$ and cutting off The “share” $\lambda$ from the directed segment $\vec{AB}$, that is, the point $M$, for which $\vec{AM} = \lambda\vec{AB}$ (Fig. 4), is determined by a simple and beautiful formula:
$$\vec{M} = (1 - \lambda)\vec{A} + \lambda\vec{B}.$$ (!!)
This formula should be remembered - it has great user application in solving many geometric problems *).

*) See the article by V. Boltyansky “Three points on one straight line” («Kvant», 1978, No. 10) and the article by I. Gabovich “Vectors help on the exam” («Kvant», 1979, No. 1).

Fig. 4.
The number $\lambda$ is called the affine coordinate of the point $M$ (relative to the coordinate system specified by the initial $A$ and the scale vector $\vec{AB}$). This name is defined: after all, if a coordinate system and an arbitrary number $\lambda$ are given, then the point $M$ on the line $AB$ is uniquely determined:
$$\vec{AM} = \lambda\vec{AB}.$$
Let's go back to the formula
$$\vec{P} = \alpha\vec{A} + \beta\vec{B},$$
with the help of which we wrote down the radius vector of the point $P$ located in the plane of the triangle $ABC$. It shows that specifying an arbitrary ordered pair of numbers $\alpha$, $\beta$ defines a point $P$ in the plane $ABC$, if given a point $C$ and vectors $\vec{CA}$ and $\vec{CB}$ (Fig. 5).
These numbers are called the affine coordinates of the point $P$ (in a coordinate system whose origin is the point $C$, and the scale vectors are $\vec{CA}$ and $\vec{CB}$). It is easy to see that points of the plane $ABC$, whose second coordinate is equal to zero, lie on the line $CA$; therefore it is called the first coordinate axis. Similarly, points whose first coordinate is zero lie on

⟦folio 33⟧

6. Special cases of Carroll's problem

1) If the point $P$ is the centroid of the triangle $ABC$ (i.e. the intersection of its medians), then (§ 22 “Geometry 9”)
$$\overrightarrow{OP} = \frac{1}{3} (\overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC})$$
and therefore
$$\bar{P} = \frac{1}{3} \bar{A} + \frac{1}{3} \bar{B},$$
that is
$$\alpha = \frac{1}{3}, \quad \beta = \frac{1}{3}.$$
Substituting these values ​​into formulas (1), we obtain $\bar{A}_1 = \frac{2}{3} \bar{B},$
$$\bar{A}_2 = \frac{1}{3} \bar{B}, \quad \bar{B}_1 = \frac{1}{3} \bar{A}, \quad \bar{B}_2 = \frac{2}{3} \bar{A},$$
$$\bar{C}_1 = \frac{2}{3} \bar{A} + \frac{1}{3} \bar{B}, \quad \bar{C}_2 = \frac{1}{3} \bar{A} + \frac{2}{3} \bar{B}$$
and, therefore (due to what was said in the previous paragraph), the vertices of the found hexagon are cut off from the sides of the triangle $\frac{1}{3}$ and $\frac{2}{3}$.

2) Let $P$ be any point of the segment $B'C'$ connecting the midpoints $B'$ and $C'$ sides CA and AB. Since this point is located inside the segment $B'C'$, it cuts off the part $0 < \lambda < 1$ from it and, by virtue of the formula (!!),
$$\bar{P} = (1 - \lambda) \bar{B}' + \lambda \bar{C}'$$
$$\bar{P} = \frac{1 - \lambda}{2} \bar{A} + \frac{\lambda}{2} (\bar{A} + \bar{B})$$

that is
$$\alpha = \frac{1}{2}, \quad \beta = \frac{\lambda}{2}.$$
Substituting these values ​​into formulas (1), we obtain
$$\bar{A}_1 = \lambda \bar{B}, \quad \bar{A}_2 = \lambda \bar{B}, \quad \bar{B}_1 = \lambda \bar{A}, \quad \bar{B}_2 = \bar{A},$$
$$\bar{C}_1 = \bar{A}, \quad \bar{C}_2 = (1 - \lambda) \bar{A} + \lambda \bar{B}.$$
Thus, in this case, the hexagon $A_1A_2B_1B_2C_1C_2$ degenerates into a parallelogram $A_1A_1B_1AAC_2 = A_1B_1AC_2$ (figure 6 is made for the case when $\lambda = \frac{4}{5}$).

3) If the point $P$ is located arbitrarily on the line $B'C'$ in the non-segment $B'C'$, then its affine coordinate $\lambda$ (in a coordinate system having origin at point $C'$ and scale vector $\overrightarrow{B'C'}$) is either a positive number greater than one or a negative number. The radius vectors of the vertices of the constructed hexagon are determined, of course, by the same formulas as in the general case, however, these vertices - the reader will see this for himself - although located on the straight lines AB, BC and CA, will be outside the segments AB, BC, CA (at figure 7 $\lambda = \frac{5}{4}$).

4) If the point $P$ is chosen in the middle $A'$ of the segment BC, that is, if $\bar{P} = \frac{1}{2} \bar{B}$ and, therefore, $\alpha = 0, \quad \beta = \frac{1}{2}$, then, by virtue of the formulas
