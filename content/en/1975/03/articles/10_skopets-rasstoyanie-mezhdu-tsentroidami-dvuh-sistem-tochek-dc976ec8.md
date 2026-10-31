---
id: 1975-3-skopets-rasstoyanie-mezhdu-tsentroidami-dvuh-sistem-tochek-dc976ec8
issue: kvant_1975_3
year: 1975
number: "3"
title: Distance between the centroids of two point systems
authors:
  - Скопец З. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 41
page_last: 45
page_labels: 39-43
tag: ZS78
lang: en
source: kvant_digital
extraction: vision
content_sha256: 85a6916f3246f4fa0a380374701ba26d36039b2c3760c134ea2c97c047657c35
prompt_sha256: draft-1
translated_from: content/ru/1975/03/articles/10_skopets-rasstoyanie-mezhdu-tsentroidami-dvuh-sistem-tochek-dc976ec8.md
source_content_sha256: e95a21eada2aa3f4e1c542a20561745c1d6840aa27f8fffbc9a5bb1398ad1d83
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧
⟦rubric⟧ MATHEMATICAL CIRCLE

## Distance between the centroids of two point systems
Z. A. Skopets

Consider a system of $n$ points $A_1, A_2, \ldots, A_n$, arbitrarily located in space. It is allowed that individual (or even all) points of this system coincide. The order of the points does not matter.

*The centroid of a system of points $A_1, \ldots, A_n$ is a point $O$ for which the vector equality holds*

$$\overrightarrow{OA}_1 + \overrightarrow{OA}_2 + \ldots + \overrightarrow{OA}_n = \sum_{i=1}^{n} \overrightarrow{OA}_i = \vec{0}. \quad (1)$$

The *existence* of a centroid does not directly follow from this definition. Therefore, we will prove that every system of points has a centroid and, moreover, a unique one.

Let us choose a system of points $A_1, A_2, \ldots, A_n$ in space, arbitrarily define a point $M$, which we take as the beginning of the vectors, and another point $O$ (Fig. 1). Then you can write

$$\overrightarrow{OA}_1 = \overrightarrow{MA}_1 - \overrightarrow{MO},$$
$$\overrightarrow{OA}_2 = \overrightarrow{MA}_2 - \overrightarrow{MO},$$
$$\ldots \ldots \ldots \ldots$$
$$\overrightarrow{OA}_n = \overrightarrow{MA}_n - \overrightarrow{MO}.$$

Let us assume that point $O$ is the centroid of this system of points. Summing these equalities term by term, we obtain, taking into account (1)

$$\vec{0} = \overrightarrow{MA}_1 + \overrightarrow{MA}_2 + \ldots + \overrightarrow{MA}_n - n \cdot \overrightarrow{MO}.$$

⟦column⟧

From here we find

$$\overrightarrow{MO} = \frac{1}{n}(\overrightarrow{MA}_1 + \overrightarrow{MA}_2 + \ldots + \overrightarrow{MA}_n) = \frac{1}{n}\sum_{i=1}^{n} \overrightarrow{MA}_i. \quad (2)$$

Carrying out the calculations in reverse order, we can easily verify that the point $O$, defined by equality (2), satisfies relation (1), that is, it is a centroid. Thus, the *existence* of a centroid is proven. It remains to prove *uniqueness*. Indeed, let us take a point $O'$, different from $O$. Then

$$\overrightarrow{O'A}_1 = \overrightarrow{O'O} + \overrightarrow{OA}_1, \ldots, \overrightarrow{O'A}_n = \overrightarrow{O'O} + \overrightarrow{OA}_n.$$

Adding these equalities and taking into account (1), we obtain

$$\overrightarrow{O'A}_1 + \ldots + \overrightarrow{O'A}_n = n \cdot \overrightarrow{OO'};$$

since the point $O'$ is different from $O$, then $\overrightarrow{O'O} \neq \vec{0}$ and $n \cdot \overrightarrow{O'O} \neq \vec{0}$, that is

$$\overrightarrow{O'A}_1 + \ldots + \overrightarrow{O'A}_n \neq \vec{0}.$$

Thus, no point $O'$ other than $O$ is the centroid of the system of points $A_1, \ldots, A_n$. This completes the proof of the existence and uniqueness of the centroid of the system of $n$ points. In addition, the method for constructing the centroid is indicated (see (2)).

Let us now prove the following statement.

Theorem 1. *Let $O_1$ be the centroid of the system of points $A_1, \ldots, A_m$ and $O_2$ be the centroid of the system of points*

⟦folio 39⟧

⟦folio 40⟧

In $B_1, \dots, B_n$. Then the centrode $O$ of the system of all $m + n$ points $A_1, \dots, A_m, B_1, \dots, B_n$ lies on the segment $O_1O_2$ and we satisfy the condition $|O_1O| : |OO_2| = n : m$.

Proof. For a point $O$ lying on the segment $O_1O_2$ and satisfying the condition $|O_1O| : |OO_2| = n : m$, we have $\vec{mOO}_1 + n\vec{OO}_2 = \vec{0}$. (3)

Let us make sure that the point $O$ is the centrode of the system of all $m + n$ points. In fact, since $O_1$ is the centrode of the system of the point $A_1, \dots, A_m$, then according to (2) we have

$$\vec{OA}_1 + \vec{OA}_2 + \dots + \vec{OA}_m - m \cdot \vec{OO}_1 = \vec{0}. \quad (4)$$

Similarly, from the fact that $O_2$ is the centrode of the system of the point $B_1, \dots, B_n$, we obtain

$$\vec{OB}_1 + \vec{OB}_2 + \dots + \vec{OB}_m - n \cdot \vec{OO}_2 = \vec{0}. \quad (5)$$

Adding the correspondences (3), (4), (5) term by term, we obtain

$$\vec{OA}_1 + \dots + \vec{OA}_m + \vec{OB}_1 + \dots + \vec{OB}_n = \vec{0},$$

and this means that $O$ is the centrode of the system of point $A_1, \dots, A_m, B_1, B_2, \dots, B_n$.

Consequence. Let $A_1, \dots, A_m$ be some systems of the point $k$ be a natural number less than $m$. Let us choose some $k$ points from $A_1, \dots, A_m$, and let $O'$ be their centrodes, and $O''$ be the centrodes of the remaining $m - k$ points. Then all the segments $O'O''$) obtained in this way pass through one point $O$ (the centrode of the system of the point $A_1, \dots, A_m$) and are divided at this point in the ratio $(m - k) : k$.

From the proven theorem and this corollary, a number of conclusions can be drawn. First of all, from Theorem 1 for $m = n = 1$ it is found that the centrode of two points $A, B$ coincides with the midpoint of the segment connecting them. Further, for $m = 2, n = 1$ we obtain from Theorem 1 that the centrode $O$ of three points $A_1, A_2, B$ lies on the segment connecting $D$ of the segment $A_1A_2$ with the point $B$, and $|DO| : |OB| = 1 : 2$. It follows, in particular, that if the points $A_1, A_2, B$ do not lie on the same straight line, then the centrode of this system of points coincides with the point of intersection of the medians of the triangle $A_1A_2B$ (see Fig. 2; this point is called the center of gravity of the triangle).

For the case of four points we obtain (for $m = 3, n = 1$) the following. Suppose that no three of the four points $A, B, C, D$ lie on the same line, and connect any of these points with the center of gravity of a triangle having vertices at the other three points; maybe these four points

⟦folio 41⟧

The re segments intersect at one point O and divide at it in a ratio of 3:1.
Three more segments pass through the same point O, which are obtained if the midpoints of the segments with endpoints at two points are connected to the midpoints of the segments with endpoints at two other points.

Note that these statements are true for four points not only on the plane, but also in space. From them, in particular, it follows that the two midlines of the quadrilateral and the segment connecting the midpoints of the diagonals intersect at one point O, which serves as the common midpoint of all three segments.
And for points in space, we can give the following formulation: the segments connecting the vertices of the tetrahedron with the centers of gravity of the opposite faces intersect at one point O (called the center of gravity of the tetrahedron) and are divided in it in a ratio of 3: 1, counting from the vertex; Three segments pass through the same point O, connecting the midpoints of opposite edges, and O serves as the common midpoint of these three segments.

Let us also note the case of five points.

Let A, B, C, D, E be the heels of points such that no four of them lie in the same plane.
By connecting each point with the center of gravity of the tetrahedron, which has vertices at the other four points, we obtain the heels of the segments intersecting at one point O; ten more segments will pass through the same point, each of which connects the middle of the segment with the ends at two points with the center of gravity of a triangle having vertices at the other three points.

Lagrange formula

Let O be the centroid of the system of points A₁, ..., Aₘ and M be an arbitrary point. Then, as we saw above, relation (2) is valid. Beria square *), we get

$$|\vec{M}O|^2 = \frac{1}{m^2} (\vec{M}A_1 + \dots + \vec{M}A_m)^2 = \frac{1}{m^2} \left[ |\vec{M}A_1|^2 + \dots + |\vec{M}A_m|^2 + 2 \sum_{i < j} \vec{M}A_i \cdot \vec{M}A_j \right].$$

But

$$2 \vec{M}A_i \cdot \vec{M}A_j = |\vec{M}A_i|^2 + |\vec{M}A_j|^2 - (\vec{M}A_j - \vec{M}A_i)^2 = |\vec{M}A_i|^2 + |\vec{M}A_j|^2 - |\vec{A}_i \vec{A}_j|^2.$$

Adding these relations for all pairs i, j, where i < j, we obtain

$$2 \sum_{i < j} \vec{M}A_i \cdot \vec{M}A_j = (m - 1) \left( |\vec{M}A_1|^2 + \dots + |\vec{M}A_m|^2 \right) - \sum_{i < j} |\vec{A}_i \vec{A}_j|^2.$$

Substituting (6') into relation (6), we find (after simplification):

$$|\vec{M}O|^2 = \frac{1}{m} \left( |\vec{M}A_1|^2 + \dots + |\vec{M}A_m|^2 \right) - \frac{1}{m^2} \sum_{i < j} |\vec{A}_i \vec{A}_j|^2.$$

Relation (7) is the well-known Lagrange formula, expressing the square of the distance from point M to the centroid O of the system of points A₁, ..., Aₘ through the square of the distance from point M to point Aᵢ and the square of the distance |Aᵢ Aᵢ|.

Centroid distance

Finally, let the given systems of points be A₁, ..., Aₘ and B₁, ..., Bₙ. Let us calculate the distance d between the centroids O₁ and O₂ of these systems, assuming that all mutual distances between points of the first system, all mutual distances between the centroids Aᵢ and Aᵢ are known.

*) The scalar product of a vector a and a vector b is denoted by a · b; equals |a| · |b| · cos α, where |a| is the length of the vector, and α is the angle between vectors a and b; therefore the scalar square is a, a = |a|² = |a|².

⟦folio 42⟧

Between the points of the second system and the mutual distances of each point of one system to each point of the other.
Let us introduce the following notation:
$$|A_i A_j| = a_{ij}, |B_s B_t| = b_{st},$$
$$|A_p B_q| = c_{pq}.$$
As clarified above (see (7)),
$$d^2 = |O_1 O_2|^2 = \frac{1}{n} |O_1 B_1|^2 + \dots$$
$$\dots + |O_1 B_n|^2) - \frac{1}{n^2} \sum_{s < t} b_{st}^2,$$
$$|O_1 B_h|^2 = \frac{1}{m} (|A_1 B_h|^2 + \dots$$
$$\dots + |A_m B_h|^2) - \frac{1}{m^2} \sum_{i < j} a_{ij}^2,$$
(where $k$ is any of the numbers 1, 2, ..., $n$). Substituting correspondences (8') into formula (8), we finally obtain (after further simplifications):
$$d^2 = |O_1 O_2|^2 = \frac{1}{mn} \sum_{p, q} c_{pq}^2 -$$
$$- \frac{1}{m^2} \sum_{i < j} a_{ij}^2 - \frac{1}{n^2} \sum_{s < t} b_{st}^2.$$

Using this formula, in the most general case, the distance between the centroids of two point systems is calculated.

Examples

1. Let triangle $A_1 B_1 B_2$ be given. The centroid $O_1$ of the system, consisting of one point $A_1$, coincides with $A_1$, the centroid $O_2$ of the system of points $B_1, B_2$ coincides with the middle $[B_1 B_2]$ (Fig. 3).

In this case, $[O_1 O_2]$ is the median of triangle $A_1 B_1 B_2$. We have
$$d^2 = \frac{1}{2} (|A_1 B_1|^2 + |A_1 B_2|^2) -$$
$$- \frac{1}{4} |B_1 B_2|^2.$$

2. Let the quadrilateral $A_1 A_2 B_1 B_2$ be given. The centroid $O_1$ of the point system $A_1, A_2$ coincides with the midpoint of the segment $A_1 A_2$, the centroid $O_2$ of the point system $B_1, B_2$ coincides with the midpoint of the segment $B_1 B_2$ (Fig. 4).

Let's use formula (9):
$$d^2 = \frac{1}{4} (|A_1 B_1|^2 + |A_1 B_2|^2 +$$
$$+ |A_2 B_1|^2 + |A_2 B_2|^2 - |A_1 A_2|^2 -$$
$$- |B_1 B_2|^2).$$ (10)

This formula, expressing the square of the distance between the midpoints of opposite sides of a quadrilateral through the squares of its sides and diagonals, is known as Euler's formula. Here the type of quadrilateral is arbitrary: it can be convex, self-intersecting, or non-planar.

If the centroids of the segments $A_1 A_2$ and $B_1 B_2$ coincide, then the quadrilateral is a parallelogram, and we obtain the well-known relationship between the sides and diagonals of the parallelogram. Note that (since $d^2 \geq 0$) it follows from formula (10) that $|A_1 B_1|^2 + |A_1 B_2|^2 + |A_2 B_1|^2 + |A_2 B_2|^2 \geq |A_1 A_2|^2 + |B_1 B_2|^2$, that is, the sum of the squares of all sides

⟦folio 43⟧

A quadrilateral is always not less than the sum of the squares of its diagonals. The discordance occurs only for $d = 0$, that is, if and only if $A_1A_2B_1B_2$ is a parallelogram.

3. Let us find the distance from the point $A_1$ to the center of the system of points $B_1, B_2, B_3$ (Fig. 5). In this case we have (by formula (7))

$$d^2 = \frac{1}{3} \left( |A_1B_1|^2 + |A_1B_2|^2 + |A_1B_3|^2 \right) - \frac{1}{9} \left( |B_1B_2|^2 + |B_2B_3|^2 + |B_1B_3|^2 \right).$$

This is a correspondence expressing the distance from the vertex $A_1$ of the tegrahedron $A_1B_1B_2B_3$ to the centroid. The opposites of the face $B_1B_2B_3$ through the squares of the edges of the tegrahedron is known as Leibniz's formula. In particular, all four points can belong to the same plane or even to the same line.

Exercises
1. Prove that the sum of the squares of the distances of any point on the circle, described by the counting relation expressing the distance from the vertex $A_1$ of the tegrahedron $A_1B_1B_2B_3$ to the centroid. Prove that the sum $|A_1|^2 + |A_2|^2 + |A_3|^2$ does not depend on the relative position of the point $P$ and $Q$ of the circle $\omega$, the sum $|PA|^2 + |PB|^2 + |PC|^2 + |QA|^2 + |QB|^2 + |QC|^2$ remains constant.

5. There are $n$ points on a circle. Through the centroid of each $n-2$ point a line is drawn perpendicular to the line passing through the other two points. Prove that $C_n^2$ of the constructed lines intersect at one point (the orthocentre of the given system of points).

Form and solve a similar problem for the case where the data $n$ points belong to the same sphere.

Tips for beginner tutors
(see p. 35)

But at the same time, take care of the reputation of a lackadaisical person. You can never emphasize several times that you are not driven by self-interest, but solely by the desire to be reasonable, kind and, if possible, eternal. There is no greater difference to your soul than the feeling that you have increased society by a few more worthy members.

After handing out the questions, go into another room and go about your business. Stronger students will complete their task first and then help those who are lagging behind. This will develop in them a sense of collectivism, which is necessary for a university.

By the middle of the lesson, a lively discussion on sports topics will break out. By no means less than ribs. Let them, when leaving you, look forward to the next meeting, during which they can continue the fascinating conversation.

At the end of the lesson, do not forget to distribute homework, copied in advance from old, long-forgotten textbooks and issued in the form of new exam papers. Ask students to keep the contents of their tickets confidential. It makes a strong impression.

Don't worry about quality when you're busy. Understand the main thing - the boys and girls came to you solely for the sake of their fathers and mothers, and this subject concerns them the least. The only thing you should take care of is that all payments with parents are completed before the exams.

To conclude this important point, there are two more useful tips. Since you are completely indifferent to which subject you use for financial support, we recommend sticking to mathematics.

(Continued on page 68.)
