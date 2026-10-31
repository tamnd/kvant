---
id: 1975-8-resheniya-zadach-m301-m303-507c0bcb
issue: kvant_1975_8
year: 1975
number: "8"
title: Solutions to problems M301—M303
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 53
page_last: 55
page_labels: 51-53
tag: UA7O
lang: en
source: kvant_digital
extraction: vision
content_sha256: 297fa3b6e623872da861399d9939c2b01753652f89bdb3fc13417ed9284d2a9c
prompt_sha256: draft-1
translated_from: content/ru/1975/08/articles/12_resheniya-zadach-m301-m303-507c0bcb.md
source_content_sha256: df58e870ef87f5a4bb4591ae7a7780b9224156ca8106da58af6017f4810933b1
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 51⟧

in the forward direction it is zero, and in the reverse direction it is infinitely large).
(9-10 grades)

Fig. 2.

F351. When a soccer ball weakly hits a wall, it is deformed, as shown in figure 3. In this case, the deformation $x$ of the ball is much less than its radius, and we can, with a good approximation, assume that the pressure $p$ of the impact in the ball does not change during the impact.

Neglecting the elasticity of the tire, estimate the time of impact of the ball with the wall. Carry out a numerical calculation for the case when the mass of the ball is $m=0,5$ kg, the pressure in it is $p=2$ atm and the radius is $R=12,5$ cm. (10 cells)

Fig. 3.

F352. To regulate the voltage across the load, a circuit is assembled, shown in figure 4. The resistances of the load and the regulating resistor are equal to $R$. The load is connected to the polyvin resistor. The voltage $U_{bx}$ at the input of the circuit is doubled. How to change the position of the resistor so that the voltage across the load remains the same? (8 grades)

Fig. 4.

Problem solutions
M301—M303

M301. There are 2n lobes on the plane - n blue and n red, and no three lobes lie on the same straight line. Prove that it is possible to check n segments, that each segment has one end in a red hole, the other in a blue hole, and no two segments have common points.

Let us call the system the opening of $n$ segments such that each segment has one end in the red segment, the other in the blue segment, and no two segments extend from the same point. To build a system, we need to somehow divide our 2n points into $n$ pairs - one red and one blue in each pair - and connect the points of each pair with a segment.

We need to find a system whose segments do not have common points with each other. Let us prove that a system is suitable for which the sum of the lengths of the segments is the minimum of all possible (for given 2n points). Indeed, let us have such a system with a minimum sum of the length of the segment -

⟦folio 52⟧

cov. Let us prove that all its segments have no common points. Let us assume the opposite: let two of its segments $K_1C_1$ and $K_2C_2$ have a common point $O(K_1, K_2)$ are red, $C_1, C_2$ are blue points, Fig. 1). Let us prove that then the sum of the lengths of segments of this system can be reduced.

By condition, the bottom three from the point $K_1, K_2, C_1, C_2$ do not lie on the same line. Then the points $K_1, K_2, C_1, C_2$ are the vertices of a convex quadrilateral. Of course, the sum of the lengths of its two opposite sides is less than the sum of the lengths of the diagonals, for example, $|K_1C_2| + |K_2C_1| < |K_1C_1| + |K_2C_2|$ (see Fig. 1).

By replacing the segments $K_1C_1$ and $K_2C_2$ in our system with the segments $K_1C_2$ and $K_2C_1$, we will reduce the sum of the lengths of the segments, which contradicts the assumption.

Let us present another solution to the problem, proposed by its author S. Ohimny (Orenburg), as well as several readers.

Let us first prove the following lemma:

for any set of $n$ synchy and $n$ red points, which is mentioned in the conditions, you can check the straight line $l$马克 that in each of the half-planes on which we climb the plane, there are equal numbers of synchy and red points, and not all $2n$ points lie in the same half-plane and the lower one does not belong $l$.

Consider the convex hull of the set of our $2n$ points: the smallest convex polygon containing them. Several of these $2n$ points serve as its vertices. Let's look at two cases.

a) Among the vertices there are both red and blue points. In this case, it will find two neighboring vertices of different colors: $K_0$ and $C_0$. Let's draw a straight line $l$ parallel to the segment $K_0C_0$ so that all the other $2n-2$ points lie on the other side of $l$. This is the required straight line (Fig. 2).

b) All vertices are the same color, say blue. Let's choose some direction so that no straight line in this direction passes through the points of our set. We can assume that this direction is vertical (Fig. 3). We will move a uniformly vertical line (from left to right) and mark those moments of time $t_1, \dots, t_{2n}$ when it passes the points of our set. Let us denote by $f(t)$ the difference between the number of synchy and red points of the left half-plane of our line at time $t$. On each segment on which the points $t_1, t_2, \dots, t_{2n}$ are divided by the axis $-\infty < t < +\infty$, the function $t \rightarrow f(t)$ is constructed, in part, $f(t) = 1$ for $t_1 < t < t_2$ (to the left of the straight line there is one blue point and 0 red ones), $f(t) = -1$ for $t_{2n-1} < t < t_{2n}$, and for each the transition through $f(t)$ changes for food and nothing. It is clear that on some segment $]t_h, t_{h+1}$ the value $f(t)$ must be equal to 0.

Any vertical line corresponding to the moment of time $t$ between $t_h$ and $t_{h+1}$ can be taken as $l$. The lemma is proven.

Now the statement of the problem is easy to prove by induction on $n$. For $n = 1$ (the given points are blue and red) it is obvious. Suppose that for all sets of $2k$ points ($k$ blue and $k$ red), where $k < n$, the statement is true. Then it is also true for a set of $2n$ points: using the lemma, we can split such a set into two, to each of which the induction hypothesis applies. Segments lying in one and the other half-plane, of course, will not intersect.

A. L. Toom, N. B. Vasiliev

⟦folio 53⟧

M302. Let $O$ be the intersection point of the diagonals of the boundary $ABCD$ (($AB$)||(CD)), $A'$ and $B'$ the points symmetrical to the points $A$ and $B$ with respect to the bisector of the node $AOB$. Let us prove that $\triangle ACA' \cong \triangle BDB'$ (Fig. 4).

Fig. 4.

M303. Rectangle $300 \times 1000$ is cut into squares $1 \times 1$, and identical symbols are placed at some 30 corners of the squares. Let us prove that it is possible to choose two non-intersecting groups of sireks - no more than 10 in each - so that their centers of gravity coincide.

Since $ABCD$ is a trapezoid, then $\frac{|OB|}{|OA|} = \frac{|OD|}{|OC|}$.

Let us denote this relation by $k$. Let $F$ be a composition of two transformations: symmetry with respect to the bisector of angle $AOB$ and horothetine (a similar transformation) with center $O$ and coefficient $k$. It's not hard to see that

$$F(A) = B, F(C) = D, F(A') = B'$$

i.e.

$$F(\triangle ACA') = \triangle BDB'$$

poseable $\triangle ACA' \cong \triangle BDB'$.

Plan for another solution: since $|OB| \cdot |OC| = |OA| \cdot |OD|$, then $|OB'| \cdot |OC| = |OA'| \cdot |OD|$,

and points $C, D, B'$ and $A'$ lie on the same circle.

Let us introduce the coordinate system $Oxy$ so that the vertices of the straight skier receive coordinates $(0, 0), (0; 300), (1000; 300), (1000; 0)$. If some 10 weights are located at points $(x_1, y_1), (x_2, y_2), \dots, (x_{10}, y_{10})$, then the coordinates of their center of gravity are $\frac{x_1 + x_2 + \dots + x_{10}}{10}, \frac{y_1 + y_2 + \dots + y_{10}}{10}$.

Thus, the coordinates of the center of gravity of any 10 weights located at the “integer points” of the straight skier - at the vertices of the squares of the constructed grid - necessarily have the form $(k/10, l/10)$, where $k$ and $l$ are integers, and $0 \leq k \leq 1000$ and $0 \leq l \leq 3000$. This type of point exists.

$$1001 \cdot 3001 = 30013001$$

(1)

On the other hand, 10 weights from the given 30 can be selected

$$C_{10}^{10} = \frac{30 \cdot 29 \cdot 28 \cdot 27 \cdot 26 \cdot 25 \cdot 24 \cdot 23 \cdot 22 \cdot 21}{10 \cdot 9 \cdot 8 \cdot 7 \cdot 6 \cdot 5 \cdot 4 \cdot 3 \cdot 2 \cdot 1} =$$

$$= 29 \cdot 23 \cdot 13 \cdot 11 \cdot 7 \cdot 5 \cdot 3^2 = 30015 \cdot 1001 = 30045015$$

ways *). Since (1) is less than (2), the centers of gravity of some two different groups of 10 weights must fall at the same point.

The problem would have already been solved if the conditions did not require that the groups of weights be non-intersecting, so that the weights $C'$, $C''$ constitute their weight from $k$ and $(10-k)$ weights, and divides this segment in the relative $(10-k)/k$. Since the centers of gravity for both groups of 10 weights coincide, the centers of gravity of both weights of $(10-k)$ weights also coincide.

N. B. Vasiliev

*) See the article by N. Ya. Vilenkin “Combinatorics” in «Kvant», 1971, No. 1, or the textbook for the 9th grade by B. E. Weizza and I. T. Demidov, ch. I.
