---
id: 1985-10-ionin-nekrasov-vektoryi-v-geometricheskih-zadachah-0517c873
issue: kvant_1985_10
year: 1985
number: "10"
title: Vectors in geometric problems
authors:
  - Ионин Ю. И.
  - Некрасов В. Б.
rubric: shkola-v-kvante
page_first: 23
page_last: 25
page_labels: 21-23
tag: K5Y7
lang: en
source: kvant_digital
extraction: vision
content_sha256: 85e18c18435cec080aaf19f8ab1a7ae15ee84de541ae47f245e95a70ab61f1d2
prompt_sha256: draft-1
translated_from: content/ru/1985/10/articles/08_ionin-nekrasov-vektoryi-v-geometricheskih-zadachah-0517c873.md
source_content_sha256: 00cd43ae4424b31f7f2b16c8d63901ed3e55beb3ee791ff662600841fb8d5a0f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 21⟧

Matematika
8, 9, 10

The note published below is intended for tenth graders. However, its first part can be useful for students in 8th and 9th grades.

Vectors in geometric problems

1. Parallelism and ratio of segments

Problem 1. Points K, L, M, N are the midpoints of the side BC, CD, DE, EA of the pentagon ABCDE, points P and Q are the midpoints of the segments KM and LN. Prove that the segments PQ and AB are parallel and find the ratio of their lengths (page 1).

Let's translate the problem statement into vector language.

The parallelism of the segments PQ and AB is written by the equality $\overrightarrow{PQ} = k \cdot \overrightarrow{AB}$, where $k$ is some real number. Having calculated $k$, we find the ratio of the lengths of the segments PQ and AB.

The main formula in solving this problem is $\overrightarrow{OZ} = \frac{1}{2}(\overrightarrow{OX} + \overrightarrow{OY})$, where $Z$ is the midpoint of the XY segment, and $O$ is an arbitrary point.

Solution. $\overrightarrow{PQ} = \overrightarrow{OQ} - \overrightarrow{OP} = \frac{1}{2}(\overrightarrow{OL} + \overrightarrow{ON}) - \frac{1}{2}(\overrightarrow{OK} + \overrightarrow{OM}) = \frac{1}{2}\left(\frac{1}{2}(\overrightarrow{OC} + \overrightarrow{OD}) + \frac{1}{2}(\overrightarrow{OA} + \overrightarrow{OE})\right) = \frac{1}{4}(\overrightarrow{OA} - \overrightarrow{OB}) = -\frac{1}{4}\overrightarrow{AB}$.

It follows that the segments PQ and AB are parallel, and their ratio is $\frac{1}{4}$.

In the above solution we used the “difference formula” twice

$\overrightarrow{XY} = \overrightarrow{OY} - \overrightarrow{OX}$, which allows you to express any vector in terms of vectors plotted from the same point.

Here are some examples of writing the same statement in geometric and vector languages:

1. Points A, B, C lie on the same straight line.
2. Point M divides segment AB in relation to $|AM|:|MB| = l:k$
3. M is the point of intersection of the medians (centroid) of triangle ABC.
4. ABCD - parallels.

In the last two cases, the geometric and vector statements are equivalent, provided that points A, B, C do not lie on the same line.

Problem 2. Prove that the midpoints of the bases and the point of intersection of the diagonals of the trapezoid lie on the same straight line (Fig. 2).

Solution. Let M, N be the midpoints of the bases BC and AD of the trapezoid ABCD, O be the intersection point of the diagonals. From the similarity of triangles AOD and BOC it follows: $\frac{|OA|}{|OC|} = \frac{|OD|}{|OB|}$. Designating these

⟦folio 22⟧

2. Centroid of point system

The concept of a centroid can easily be transferred from a triangle to an arbitrary finite system of points in space:

A point M is called the centroid of a system of n points $A_1, A_2, \dots, A_n$ if $\overrightarrow{MA}_1 + \overrightarrow{MA}_2 + \dots + \overrightarrow{MA}_n = \overrightarrow{0}$.

Using the difference formula, the last equality can be rewritten as follows: $(\overrightarrow{OA}_1 - \overrightarrow{OM}) + (\overrightarrow{OA}_2 - \overrightarrow{OM}) + \dots + (\overrightarrow{OA}_n - \overrightarrow{OM}) = \overrightarrow{0}$ (O is an arbitrary point),

$\overrightarrow{OA}_1 + \overrightarrow{OA}_2 + \dots + \overrightarrow{OA}_n - n \cdot \overrightarrow{OM} = \overrightarrow{0}$,

$\overrightarrow{OM} = \frac{1}{n} (\overrightarrow{OA}_1 + \overrightarrow{OA}_2 + \dots + \overrightarrow{OA}_n)$.

From the last formula it follows that any finite system of points has a single centroid. Moreover, the centroid of a system consisting of one point is this point itself, the centroid of a pair of points is the middle of the segment connecting them. Finding the centroid of a large number is forgiven by the following principle: if $M_1$ is the centroid of the system of k points $A_1, A_2, \dots, A_k$, and $M_2$ is the centroid of the system of l points $B_1, B_2, \dots, B_l$ and these systems do not have common points, then the centroid of the system of k + l points $A_1, A_2, \dots, A_k, B_1, B_2, \dots, Bl$ is a point M belonging to the segment $M_1M_2$ and dividing it in the relation $|M_1M_2| = l:k$.

Indeed, let $k \cdot \overrightarrow{M_1M} = l \cdot \overrightarrow{MM_2}$.

Using the difference formula, we get:

$k (\overrightarrow{OM} - \overrightarrow{OM}_1) = l (\overrightarrow{OM}_2 - \overrightarrow{OM}_1)$,

$k \cdot \overrightarrow{OM} - k \cdot \overrightarrow{OM}_1 = l \cdot \overrightarrow{OM}_2 - l \cdot \overrightarrow{OM}_1$,

$(k + l) \cdot \overrightarrow{OM} = k \cdot \overrightarrow{OM}_1 + l \cdot \overrightarrow{OM}_2$,

$\overrightarrow{OM} = \frac{k}{k + l} \overrightarrow{OM}_1 + \frac{l}{k + l} \overrightarrow{OM}_2$.

According to formula (1)

$\overrightarrow{OM}_1 = \frac{1}{k} (\overrightarrow{OA}_1 + \overrightarrow{OA}_2 + \dots + \overrightarrow{OA}_k)$,

$\overrightarrow{OM}_2 = \frac{1}{l} (\overrightarrow{OB}_1 + \overrightarrow{OB}_2 + \dots + \overrightarrow{OB}_l)$,

So

$\overrightarrow{OM} = \frac{1}{k + l} (\overrightarrow{OA}_1 + \overrightarrow{OA}_2 + \dots + \overrightarrow{OA}_k)$,

and we got what we needed.

Applying this principle to the three vertices of a triangle, we find that the centroid of the triangle lies on

⟦folio 23⟧

a segment connecting the vertex with the center of two other vertices, that is, with the middle of the opposite side, and divides this segment in a ratio of 2: 1, counting from the vertex. This implies the well-known theorem of planimetry: the medians of a triangle intersect at one point and are divided by this point in a ratio of 2:1, counting from the vertices.

It is similarly proven that the segments connecting the vertices of a triangle with the centroids of opposite faces intersect at one point—the centroid of the triangle—and are divided at this point in a ratio of 3:1, counting from the vertices.

3. Calculating distances and angles

Having given a triple of non-complanan vectors in space - a basis, it is possible to expand any vector into this basis in a unique way. Knowing the scalar products of the basis vectors, we can easily calculate the scalar products of any vectors, and therefore their lengths and angles between them.

Task 4. Given $\vec{a}\vec{b} = 1$, $\vec{a}\vec{c} = 2$, $\vec{b}\vec{c} = 0$, $\vec{a}^2 = \vec{b}^2 = 4$, $\vec{c}^2 = 2$.

Find $|\vec{p}|$, $|\vec{q}|$, $(\vec{p}, \vec{q})$ if $\vec{p} = 2\vec{a} - \vec{b}$, $\vec{q} = \vec{a} + \vec{b} + \vec{c}$.

Solution: Let's rewrite the conditions of the problem in the form of a “multiplication table” (Table 1). We find: $|\vec{p}| = \sqrt{\vec{p}^2} = \sqrt{(2\vec{a} - \vec{b})^2} = \sqrt{4\vec{a}^2 - 4\vec{a}\vec{b} + \vec{b}^2} = \sqrt{16} = 4$;

$|\vec{q}| = \sqrt{\vec{q}^2} = \sqrt{(\vec{a} + \vec{b} + \vec{c})^2} = \sqrt{\vec{a}^2 + \vec{b}^2 + \vec{c}^2 + 2\vec{a}\vec{b} + 2\vec{a}\vec{c} + 2\vec{b}\vec{c}} = \sqrt{16} = 4$.

From the definition of the scalar product we get:

$$\cos(\vec{p}, \vec{q}) = \frac{\vec{p}\vec{q}}{|\vec{p}| \cdot |\vec{q}|} = \frac{2(\vec{a} - \vec{b})(\vec{a} + \vec{b} + \vec{c})}{16} = \frac{2\vec{a}^2 + \vec{a}\vec{b} + 2\vec{a}\vec{c} - \vec{b}^2 - \vec{b}\vec{c}}{16} = \frac{9}{16},$$

whence $(\vec{p}, \vec{q}) = \arccos \frac{9}{16}$.

Problem 5. The base $ABCA_1B_1C_1$ is a regular triangle. The side edge $AA_1$ is twice as large as the side of the base and forms angles $A_1AB = 90^\circ$, $A_1AC = 60^\circ$. O is the center of triangle $ABC$. Find on line $CC_1$ a point $K$ such that lines $B_1K$ and $A_1O$ are perpendicular.

Solution. The position of the point $K$ on the line $CC_1$ is determined by the value of the coefficient $x$ in the equality $\vec{C}_1\vec{K} = x \cdot \vec{C}_1\vec{C}$. Let us denote by $a$ the length of the side of the base of the recognition, choose as a basis the triple of vectors $\vec{m} = \vec{AB}$, $\vec{n} = \vec{AC}$, $\vec{p} = \vec{AA}_1$ (Fig. 5), after which we compile a “multiplication table” (Table 2).

Let us decompose the vectors $\vec{A}_1\vec{O}$ and $\vec{B}_1\vec{K}$ into the basis $(\vec{m}, \vec{n}, \vec{p})$: $\vec{A}_1\vec{O} = \vec{A}_1\vec{A} + \vec{A}O = -\vec{p} + \frac{1}{3}(\vec{m} + \vec{n}) = \frac{1}{3}(\vec{m} + \vec{n} - 3\vec{p})$, $\vec{B}_1\vec{K} = \vec{B}_1\vec{A}_1 + \vec{A}_1\vec{C}_1 + \vec{C}_1\vec{K} = \vec{m} + n - x\vec{p}$. Having written down the conditions perpendicular to the primes $A_1O$ and $B_1K$:

$(\vec{m} + \vec{n} - 3\vec{p})(-\vec{m} + \vec{n} - x\vec{p}) = 0$, we obtain using table 2: $11a^2x - 3a^2 = 0$, from where $x = \frac{3}{11}$.

Exercises

1. In the terraedron $ABCD$ the points $E$ and $F$ are the midpoints of the edges $AB$ and $CD$. Prove that the midpoints of the segments $CE, DE, AF$ are the vertices of the parallelogram.

2. Points $A, B, C, D, E, F$ do not lie in the same plane. Prove that if the lines $AB$ and $DE, BC$ and $EF, CD$ and $AF$ are parallel, then $|AB| = |DE|, |BC| = |EF|, |CD| = |AF|$.

3. Prove that the segments connecting the midpoints of the base of the quadrilaterals of a parallelogram intersect at one point. In what respect do they share this point?

4. Prove that the midpoints of the quadrilaterals discussed in the previous exercise are the vertices of a parallelogram.
