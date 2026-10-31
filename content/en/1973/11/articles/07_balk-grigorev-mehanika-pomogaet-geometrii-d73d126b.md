---
id: 1973-11-balk-grigorev-mehanika-pomogaet-geometrii-d73d126b
issue: kvant_1973_11
year: 1973
number: "11"
title: Mechanics helps geometry
authors:
  - Балк М. Б.
  - Григорьев Н. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 36
page_last: 41
page_labels: 34-39
tag: ZNG9
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3f9e1879c39ae1fe8850ada0cb9e0a052f786e121d78108dc749d3cda139e352
prompt_sha256: draft-1
translated_from: content/ru/1973/11/articles/07_balk-grigorev-mehanika-pomogaet-geometrii-d73d126b.md
source_content_sha256: 0453d25e0a2a3c05042ce32c4db7232bf4aae1c8470aa1d38707266774e2f7ac
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 34⟧

Mechanics
helps geometry
M. B. Balk, N. A. Grigoriev

... I considered it necessary to write to me and ... state some
a special method by which we received
the ability to use mechanics to find some
torus mathematical theorems. I'm sure this method will
dem is no less useful to me for proof
simkh theorem.

Archimedes. "Epistle to Eramosthenes.
On mechanical theorems".

Since the time of Archimedes, the simplest
concepts of mechanics - and, first of all,
However, the concept of the center of gravity of a system of material points is indi-
repeatedly and with great success
attractive for proving geometric theorems. So, with the help of some
mathematical considerations, Archimedes was the first to prove the theorem about three medians of a triangle and found a formula for calculating the volume of a ball.
Mechanical considerations are used to calculate the volumes of various bodies of revolution, find the geometric locations of points, prove inequalities and solve many other problems in geometry and algebra *).

This article was written based on materials from activities conducted with students of the 10th grade at the Smolensk city physics and mathematics circle (October 19, 1972) and at the Ivanovo Youth School (December 1, 1972). In it we will discuss one mechanical theorem, which belonged to the famous French mathematician Lagrange (1736-1813), and show how this theorem allows us to easily solve difficult problems in the field of elementary geometry. As we will see, this theorem is essentially
*) See also M. B. Balk, Geometric applications of the concept of the center of gravity, M., Fizmatiz, 1959 (“Library of the mathematical circle,” issue 9), and V. A. Uspensky, Some applications of mechanics to mathematics, M., Fizmatiz, 1958 (“Popular lectures on mathematics,” issue 27).

procession is a direct consequence of the Pythagorean theorem.

Center of gravity

Let there be (see Fig. 1) two material points (exact masses): A mass $m_1$ (we will write in short as follows: $(A, m_1)$) and B mass $m_2$ $(B, m_2)$.

The center of gravity C of two material points $(A, m_1)$ and $(B, m_2)$ is a point located on the segment AB and satisfying the following relationship (“the lever rule” of Archimedes):

$$m_1 \cdot AC = m_2 \cdot CB.$$

If at point C we place the masses of both material points $m_1$ and $m_2$, then the material point $(C, m_1 + m_2)$ that arises will be called the material center of the points $(A, m_1)$ and $(B, m_2)$. The material center of three material points $(A_1, m_1), (A_2, m_2), (A_3, m_3)$ (Fig. 2) is determined as follows: first one should find the material center $(C, m_1 + m_2)$ of points $(A_1, m_1)$ and $(A_2, m_2)$, and then - the material center $(Z, m_1 + m_2 + m_3)$ of points $(C, m_1 + m_2)$ and $(A_3, m_3)$. Point Z will be the center of gravity of the system of three material points $(A_1, m_1), (A_2, m_2), (A_3, m_3)$.

Fig. 1.

⟦folio 35⟧

In a similar way, the material center and center of gravity of the system are determined from any number (n) of material points*).

Now let's solve one problem.
Problem 1. In triangle ABC (Fig. 3), the lengths of the string BC, CA and AB are equal to the correspondence a cm, b cm and c cm. Place the masses a e, b e and c at the vertices A, B, C with the correspondence. Find the center of gravity of these material points.

Let us denote by Z the center of gravity of the material points (A, a), (B, b), (C, c), and by C₁ the center of gravity of the material points (A, a) and (B, b).

Then
$$a \cdot AC_1 = b \cdot C_1B,$$
where
$$AC_1 : C_1B = b : a = AC : CB.$$

It follows that CC₁ is a bisector of angle C. Let us replace the points (A, a) and (B, b) with their material center (C₁, a + b). Then the center of gravity Z should be on the segment CC₁. In the same way, you can make sure that point Z should be on the bisector AA₁. Therefore, Z is the point of intersection of the bisector of tresargon ABC.

Let us note here one useful property of the center of gravity.

*) It can be proven that the position of the center of gravity does not depend on the point number, that is, that our definition is “correct”.

Fig. 2.

Fig. 3.

Let Z be the center of gravity of n material points (A₁, m₁), (A₂, m₂), ..., (Aₙ, mₙ), located on the plane on the same side of some straight line α (Fig. 4). Let y₁, y₂, ..., yₙ and z be the distances from the point A₁, A₂, ..., Aₙ, Z to the straight line α. Then
$$z = \frac{m_1y_1 + m_2y_2 + \cdots + m_ny_n}{m_1 + m_2 + \cdots + m_n}.$$ (1)

It is easy to verify the validity of this formula for n = 2 by using the lever rule. Then it is easy to prove formula (1) for n = 3, reducing this case to the case n = 2. For arbitrary n, formula (1) is proved by the method of mathematical induction. Try checking this proof yourself.

Moment of inertia

The concept of “moment of inertia” was introduced by Leonhard Euler (1707–

Fig. 4.

⟦folio 36⟧

Fig. 5.

1783) more than 200 years ago. Let there be a system of $n$ material points $(A_1, m_1), (A_2, m_2), \dots, (A_n, m_n)$, and let another point $S$ be chosen. The moment of inertia of a given system of points relative to point $S$ is called the quantity

$$J_S = m_1 \cdot SA_1^2 + m_2 \cdot SA_2^2 + \dots + m_n \cdot SA_n^2$$

(the sum of the products of the masses of the material points of the system by the squares of their distances from the point $S$). In short, we write formula (2) like this:

$$J_S = \sum_{i=1}^{n} m_i \cdot SA_i^2.$$

Problem 2. A circle (Fig. 5) is described near the prey $ABC$ from the side $a, b, c$. Let us denote by $Z$ the point of intersection of the medians of the transverse, and by $S$ the center of the circumcircle. Calculate the moments of inertia of the system of material points $(A, 1), (B, 1), (C, 1)$ relative to point $Z$ and relative to point $S$.

Let $AA_1, BB_1, CC_1$ be the medians of the triangle, $Z$ their intersection point. Then

$$J_Z = 1 \cdot ZA^2 + 1 \cdot ZB^2 + 1 \cdot ZC^2 = \frac{4}{9} \left( AA_1^2 + BB_1^2 + CC_1^2 \right) = \frac{1}{3} \left( a^2 + b^2 + c^2 \right),$$

$$J_S = 1 \cdot SA^2 + 1 \cdot SB^2 + 1 \cdot SC^2 = 3R^2,$$

where $R = \frac{abc}{4S_{\triangle ABC}}$ ($S_{\triangle ABC}$ is found by Heron’s formula).

**Lagrange's theorem**

In 1783, Lagrange drew attention to the validity of the following statement.

Let $J_S$ be the moment of inertia of the system of material points $(A_1, m_1), (A_2, m_2), \dots, (A_n, m_n)$ relative to an arbitrary given point $S$, $J_Z$ be the moment of inertia of this system relative to its center of gravity Z. Then

$$J_S = J_Z + M \cdot SZ^2,$$

(4)

food

$$M = m_1 + m_2 + \dots + m_n.$$

Proof *. Let $\alpha$ be a line such that all points $A_1, A_2, \dots, A_n$ lie on the same side of it and $\alpha \perp SZ$ (see Fig. 4). Let $B_1, B_2, \dots, B_n, B$ be the projection of the point $A_1, A_2, \dots, A_n, Z$ onto the line $\alpha$; $A_1B_1 = y_1, A_2B_2 = y_2, \dots, A_nB_n = y_n, BZ = z, BS = s$. From trapezoids $A_1B_1BZ$ and $A_1B_1BS$ we have:

$$SA_1^2 - ZA_1^2 = (y_1 - s)^2 - (y_1 - z)^2 = [(y_1 - z) - (s - z)]^2 - (y_1 - z)^2.$$

Simplifying the part rule and multiplying both parts by $m_1$, we get:

$$m_1 \cdot SA_1^2 - m_1 \cdot ZA_1^2 = m_1 \cdot SZ^2 - 2(s - z)(m_1y_1 - m_1z).$$

*) We limit the case when all given material points lie in the same plane; however, the statement is also true for an arbitrary location of the point in space (see the book mentioned above: M. B. Balk, Geometric applications of the concept of the center of gravity, pp. 75-76).

⟦folio 37⟧

Likewise

$$m_2 \cdot SA_2^2 - m_2 \cdot ZA_2^2 = m_2 \cdot SZ^2 - 2(s - z)(m_2y_2 - m_2z),$$

$$m_n \cdot SA_n^2 - m_n \cdot ZA_n^2 = m_n \cdot SZ^2 - 2(s - z)(m_ny_n - m_nz).$$

Adding these equalities term by term and taking into account the certain moment of inertia (2) and formula (1), we obtain the required equality:

$$J_S - J_Z = M \cdot SZ^2.$$

Task 3. The edge of a regular metrahedron SABC is equal to a. Calculate the radius R of the ball circumscribed about the metrahedron.

Let us place masses of 1 gram at the four vertices of the tetrahedron. Then the center of gravity of the formed four material points coincides with the center Z of the circumscribed sphere. We have $J_S = 3a^2$, $J_Z = 4R^2$, $M = 4$ and by formula (4) we obtain: $3a^2 = 4R^2 + 4R^2$, whence $R = \frac{a\sqrt{6}}{4}$.

Task 4. Knowing the lengths a, b, c of the side of triangle ABC, calculate the length of the bisector CC$_1$ (Fig. 6).

Let us place such masses at points A and B that point C$_1$ turns out to be their center of gravity. To do this, we note that by the well-known property of the bisector AC$_1$: C$_1$B = AC:CB, that is, $a \cdot AC_1 = b \cdot C_1B$. This means that a mass of a grams must be placed at point A, and b grams at point B, the center of gravity of the materials of points (A, a) and (B, b) will be point C$_1$.

According to formula (4) we have $(a + b) \times CC_1^2 = J_C - J_{C_1}$, that is, $(a + b) CC_1^2 = (a \cdot CA^2 + b \cdot CB^2) - (a \cdot C_1A^2 + b \cdot C_1B^2)$.

From the equalities AC$_1$: C$_1$B = b: a, AC$_1$ + C$_1$B = c we find:

$$AC_1 = \frac{bc}{a + b}, \quad C_1B = \frac{ac}{a + b}.$$

From (5) it follows:

$$CC_1^2 = ab \left[ 1 - \frac{c^2}{(a + b)^2} \right].$$

Task 5. Knowing the sides a, b, c of triangle ABC, calculate the distance between the point Z of the intersection of the medians of the triangle and the point H of the intersection of its heights.

Let's place equal masses (1 gram each) at vertices A, B, C (Fig. 7). According to formulas (3) and (4) we have:

$$3HZ^2 = J_H - J_Z = HA^2 + HB^2 + HC^2 - \frac{1}{3}(a^2 + b^2 + c^2).$$

To calculate the distances HA, HB, HC, we construct a triangle A'B'C', the sides of which are parallel to the sides of the given triangle ABC and pass through its vertices. In triangle A'B'C', point H is the center of the circumscribed circle (check!),

⟦folio 38⟧

Fig. 8.

and therefore $HA' = HB' = HC' = R'$, where $R'$ is the radius of the circle circumscribed about $\triangle A'B'C'$. Because
$$\frac{A'B'}{AB} = \frac{B'C'}{BC} = \frac{C'A'}{CA} = 2,$$
then $R' = 2R$, where $R$ is the radius of the circle circumscribed about the triangle $ABC$. Hence $HA^2 = C'H^2 - a^2 = 4R^2 - a^2$, $HB^2 = 4R^2 - b^2$, $HC^2 = 4R^2 - c^2$. That's why
$$HZ^2 = 4R^2 - \frac{4}{9}(a^2 + b^2 + c^2),$$
where $R = \frac{abc}{4S}$, and the area $S$ of the triangle $ABC$ is calculated through its sides using Heron’s formula.

Another formula for moment of inertia
Let us now dwell on another formula for the moment of inertia, which is widely used in mechanics (especially in celestial mechanics in the study of the so-called “problem of $n$ bodies”). This formula also turns out to be very useful for solving purely geometric problems.

Let there be $n$ materials of points $(A_1, m_1), (A_2, m_2), \dots, (A_n, m_n)$ (Fig. 8). The distance between points $A_i$ and $A_k$ is denoted by $r_{ik}$. (For example, $r_{24}$ is the distance of $A_2A_4$.) Expression
$$\sum_{i \leqslant k \leqslant n} m_i m_k r_{ik}^2$$
denotes the sum of all possible terms of the form $m_i m_k r_{ik}^2$, where $i$ and $k$ are any integers between 1 and $n$,

$i$ is less than $k$. (For example,
$$\sum_{1 \leqslant i < k \leqslant 3} m_i m_k r_{ik}^2$$
stands for $m_1 m_2 r_{12}^2 + m_1 m_3 r_{13}^2 + m_2 m_3 r_{23}^2$.)
It turns out that the moment of inertia $J_Z$ of a system of material points relative to its center of gravity Z can be expressed through the mutual distances between these tones and their masses:
$$J_Z = \frac{1}{M} \sum_{1 \leqslant i < k \leqslant n} m_i m_k r_{ik}^2$$
($M = m_1 + m_2 + \dots + m_n$ is the total mass of the entire system$)$.
We will carry out the proof only for the case $n = 4$, but from further discussion it will be clear that it is suitable for any $n$.
According to Lagrange's theorem we have:
$$m_1 \cdot J_{A_1} = m_1 J_Z + m_1 \cdot M \cdot ZA_1^2,$$
or, in more detail:
$$m_1 m_2 r_{12}^2 + m_1 m_3 r_{13}^2 + m_1 m_4 r_{14}^2 = m_1 J_Z + m_1 \cdot M \cdot ZA_1^2.$$
Likewise
$$m_2 m_1 r_{12}^2 + m_2 m_3 r_{23}^2 + m_2 m_4 r_{24}^2 = m_2 J_Z + m_2 \cdot M \cdot ZA_2^2,$$
$$m_3 m_1 r_{13}^2 + m_3 m_2 r_{23}^2 + m_3 m_4 r_{24}^2 = m_3 J_Z + m_3 \cdot M \cdot ZA_3^2,$$
$$m_4 m_1 r_{14}^2 + m_4 m_2 r_{24}^2 + m_4 m_3 r_{24}^2 = m_4 J_Z + m_4 \cdot M \cdot ZA_4^2.$$
Adding these equalities along the rays:
$$2 \sum_{1 \leqslant i < k \leqslant 4} m_i m_k r_{ik}^2 = M \cdot J_Z + M \cdot J_Z,$$
that equality to the required equality (6) (for $n = 4$).
Task 6. In a circle of radius $R$, a right 100-wallnik $A_1A_2A_3 \dots A_{100}$ is placed. Calculate the sum σ of the squares of the length of all its diazons and all its sides.

⟦folio 39⟧

Fig. 9.

Let us place 1 gram of mass at each vertex of the polygon. The center of gravity of the emerging system of material points coincides with the center O of the circle. According to formula (6) we have
$$\sigma = \sum_{1 \leq i < k \leq 100} A_i A_k^2 = M J_0 = (100R)^2.$$
Task 7. Knowing the radius R of the circle described around a given triangle ABC, and the radius r of the circle described in the same triangle, calculate the distance d between their centers.

Let S be the center of the circumscribed circle, Z the center of the inscribed circle, a, b, c (cm) the lengths of the sides of the triangle. Let us place the masses of the corresponding a, b and c grams at vertices A, B, C. The center of gravity of this system will be point Z. According to formula (4) we have
$$J_S - J_Z = (a + b + c) d^2.$$
Using formulas (2) and (6) we find:
$$J_S = a \cdot SA^2 + b \cdot SB^2 + c \cdot SC^2 = (a + b + c) R^2,$$
$$J_Z = \frac{abc^2 + bca^2 + cab^2}{a + b + c} = abc.$$
In addition, according to the well-known formulas for the area of ​​a triangle, we have
$$S_{\Delta ABC} = \frac{abc}{4R} = \frac{1}{2} (a + b + c) r,$$
where
$$abc = 2Rr (a + b + c).$$
From formulas (7) - (10) it follows that
$$d^2 = R^2 - 2Rr.$$
This is the desired formula (“Euler’s formula”).

Task 8. It is known that in a parallelogram the difference between the sum of the squares of the length of all points of the plane for which the sum of the squares of the distances from the vertices of the square A_1 A_2 A_3 A_4 given in this plane on side a is a constant of c^2, if c^2 > 2a^2?

Let us place equal masses (1 gram each) at the vertices of the quadrilateral A_1 A_2 A_3 A_4, and let Z be the center of gravity of the resulting system of material points. By definition (2) and formula (6) we have
$$J_Z = ZA_1^2 + ZA_2^2 + ZA_3^2 + ZA_4^2 = \frac{1}{4} \left( A_1 A_2^2 + A_2 A_3^2 + A_3 A_4^2 + A_1 A_4^2 + A_2 A_4^2 \right).$$
Let us now consider a system of two material points (A_1, 1) and (A_3, 1) (their center of gravity is the middle P of the segment A_1 A_3). Let us accept formula (4):
$$ZA_1^2 + ZA_3^2 = PA_1^2 + PA_3^2 + 2ZP^2 = \frac{1}{2} A_1 A_3^2 + \frac{1}{2} PQ^2.$$
Likewise
$$ZA_2^2 + ZA_4^2 = \frac{1}{2} A_2 A_4^2 + \frac{1}{2} PQ^2.$$
From (11), (12) and (13) the desired Euler formula follows:
$$(A_1 A_2^2 + A_2 A_3^2 + A_3 A_4^2 + A_4 A_1^2) - (A_1 A_3^2 + A_2 A_4^2) = 4PQ^2.$$
Exercises
1. Solve problem 4 in other ways using formula (6).
2. Let Z be the center of the circle inscribed in triangle ABC (BC=a, CA=b, AB=c). Prove that
$$a \cdot ZA^2 + b \cdot ZB^2 + c \cdot ZC^2 = abc.$$
3. What formula represents the set of all points of the plane for which the sum of the squared distances from the vertices of a square A_1 A_2 A_3 A_4 given in this plane on side a is a constant of c^2, if c^2 > 2a^2?
4. In some triangles, the distance between the intersection point of the medians and the center of the circumscribed circle is three times less than the radius of this circle. Prove that the triangle is right.
