---
id: 2024-5-6-bakaev-magzhanov-zadacha-o-zamknutoy-lomanoy-014023b7
issue: kvant_2024_5-6
year: 2024
number: 5-6
title: Closed polyline problem
authors:
  - Бакаев Е. В.
  - Магжанов Д.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 27
page_last: 34
page_labels: 25-31
lang: en
source: kvant_digital
extraction: vision
content_sha256: df73eec3fcca44a1e35c42d0261ae2b65498e0bda33bc89be3ca643f03a3f6e7
prompt_sha256: draft-1
translated_from: content/ru/2024/05-06/articles/07_bakaev-magzhanov-zadacha-o-zamknutoy-lomanoy-014023b7.md
source_content_sha256: cbf156c4e6e7f1f7bcb0aed3dcf958a15286bf9bc1bc1f663302ba606afac834
translation_model: draft
translation_run: en-draft-2026-11-03
translation_quality: draft
---

⟦folio 25⟧

Problem about a closed broken line

E. BAKAEV, D. MAGZHANOV

In this article we will present the solution to problem M2785 of the Quaent Problem Book and discuss some related issues. We are grateful to P.A. Kozhevnikov, before
who provided the fourth and fifth solutions to point a) of this problem and problem 5.

Problem M2785

On the given plane there is a finite set $S$ of $n > 2$ points in general position (i.e.

DOI: https://doi.org/10.4213/kvant20240504

no three points lie on the same line). Number of non-self-crossings -
for closed $n$-link broken lines with vertices at these points will be denoted
part $f(S)$. Prove that

a) $f(S) > 0$ for any $S$;

b) $f(S) = 1$ if and only if all points $S$ lie on the convex hull of the set $S$;

b) if $f(S) > 1$, then $f(S) \ge n - 1$; this value is achieved when inside you-

⟦folio 26⟧

---
running_head:
folio:
---

the convex hull of the set $S$ contains exactly one of its points;
d) if inside the convex hull of the set $S$ there are two of its points, then
$$f(S) \geq \frac{(n-2)(n-3)}{2}.$$
Let $n > 2$. We will denote $F(n)$ by-
the largest possible value of the function $f(S)$
over all sets $S$ of $n$ points in general
provisions.
e) Prove that $F(n) \geq 3 \cdot 2^{\frac{n-8}{3}}$.

Solutions to point a)
Each of the closed broken lines about which
where we are talking about the conditions of the problem, we will
name the provisions.

First decision.
Order by coordinate
Lemma 1. On a given plane, a finite
set of points in general position. Then you can connect all the points with segments
poppy to get a non-self-intersecting broken line (not closed).
Proof. Let us introduce Cartesian co-
ordinates. Let's order the points in ascending order of the abscissa, and in case of equality, in ascending order of the ordinal. We denote the ordered points as $A_1, A_2, \ldots, A_n$, and the values ​​of their abscissas as $x_1, x_2, \ldots, x_n$, respectively (Fig. 1).
Let's connect consecutive points from -
cuts, then the projection of each segment $A_i A_{i+1}$ is $[x_i, x_{i+1}]$. This means that segments can have common points only at the vertices of the broken line. The broken line is built.
Lemma 2. Let the points $X, Y \in S$ be
you that $XY - \delta$氨erm of the set $S$ (m.e.
lobes $X$ and $Y$ – maximum removal
points from each other in this set).

Let us introduce Cartesian coordinates such that the x-axis contains $XY$. Then, in the notation of the previous lemma, $X$ and $Y$ are the points $A_1$ and $A_n$.

Proof. Let the projection $P'$ onto the segment $XY$ of some point $P \in S$ (different from $X$ and $Y$) not lie on the segment $XY$ (Fig. 2). Then $PX > P'X \geq XY$ or $PY > P'Y \geq XY$, which means $XY$ is not a diameter, we get a contradiction. Sledova-
Consequently, the projections of all points lie inside $XY$, therefore the coordinates of the point $X$ and $Y$ are the minimum and maximum of the coordinates
nat all points. The lemma is proven.

Using these lemmas we obtain a solution to point a) of the problem. Let $A, B \in S$ be such that $AB - \delta$氨erm $S$. Let's draw a coordinate line containing the diameter - it will divide the plane into two half-planes (Fig. 3). Consider the points lying in

Fig. 3
the first half-plane, including the boundary. Let us arrange them and construct a broken line, as in the proof of Lemma 1. By Lemma 2, the points $A$ and $B$ are the extreme points of the resulting broken line, and all the segments lie in the first half-plane, including the straight line $AB$.

Let's do the same for points lying in the second half-plane, including the boundary. As a result, by Lemma 1 we obtain a closed broken line whose links do not intersect within the half-plane. Obviously, links from different half-planes also do not intersect.

Second solution.
Order by polar angle
Consider the point $X \notin S$ lying inside or on the convex hull $S$

⟦folio 27⟧

---
running_head:
folio:
---

(Fig. 4). Let us introduce polar coordinates centered at this point and denote the points of the set $S$ by $A_1, \ldots, A_n$ so that $0 \leq \varphi_1 < \varphi_2 < \ldots < \varphi_n < 2\pi$ are the corresponding polar angles. Then the broken line $A_1A_2 \ldots A_nA_1$ is a belt. Moreover, it is clear that $X$ is contained in the region bounded by this pole. We will call the belt obtained by such a construction a non-inclusive pole vecrue $X$.

Let us now consider the point $X \in S$ lying inside the convex hull $S$ (Fig. 5), introduce polar coordinates centered at $X$ and order the remaining points of the set in the same way, denoting them as $A_1, \ldots, A_{n-1}$. Then the broken line is $A_iA_{i+1} \ldots A_{n-1}A_1 \ldots A_{i-1}XA_i$, where $i \in \{1, 2, \ldots, n-1\}$ is the belt. It is clear that there are $n-1$ such belts.

If $X \in S$ lies on a convex hull, then in this way we can construct only one belt $A_iA_{i+1} \ldots A_{i-1}XA_i$.

We will call the belts that can be obtained in the second way (taking the point from $S$ as the center of polar coordinates) as including the polar vector $X$.

Third solution.
Connection of convex hulls

Consider the convex hull of the set $S$. Let's call it first. Next, for the remaining set of points (enclosed inside the first convex hull), we will also consider the convex hull, which we will call the second (an example is shown in figure 6). We will continue this operation as long as possible. (It might turn out that the last step was performed with a set consisting of one or two points.)

Fig. 6

Lemma 3. Let a segment connect points from the $i$th and a point from the $(i+1)$th convex hulls. Then it does not intersect the $i$th convex hull.

Proof. This is so because the entire segment lies inside the convex polygon formed by the $i$th convex hull (which means it does not intersect it).

Lemma 4. The ends of any segment $AB$ (not the last one) of the $i$-th convex hull can be connected to the ends of a segment of the $(i+1)$-th convex hull (or from a point in the case when the convex hull consists of one point) by two segments so that they do not intersect the convex hulls and each other.

Proof. The case when the $(i+1)$-th shell consists of one point is very clear - we simply draw two segments from $A$ and $B$ to it. The case when the $(i+1)$-th shell consists of two points $C$ and $D$ is also identified: the segments $AC$ and $BD$ do not intersect or the segments $AD$ and $BC$ do not intersect.

Let us consider the remaining case when the $(i+1)$-th shell consists of more than two points. We will assume that $AB$ passes horizontally and the point $A$ is located to the left of $B$ (Fig. 7). Let $X$ be a point close to line $AB$ from the $(i+1)$-th shell (if there are several of them, then choose the leftmost one). Then the segments $AX$ and $BX$ do not intersect the $(i+1)$th convex hull (otherwise $X$ is not a close point).

Consider lines containing segments that connect $X$ with neighboring vertices from the $(i+1)$-th convex hull. Let's call them $m$ and $n$ so that $m$ intersects line $AB$ to the left than $n$ intersects line $AB$. The point of intersection of $m$ with line $AB$ is called $M$ (if one of the lines $m$ and $n$ is parallel to $AB$, then we will designate it as $m$, and the other as $n$; in this case we will take the point $M$ left endless

⟦folio 28⟧

---
running_head:
folio:
---

point at $AB$). The intersection point $n$ with line $AB$ is called $N$.
The neighbor vertex of $X$, lying on $m$, is called $M_1$. The neighbor vertex of $X$, lying on $n$, is called $N_1$. Let $P, Q \in AB$ be any points such that $P$ is to the left of $A$, $Q$ is to the right of $B$.
Let's consider three comparisons.
1) Point $A$ lies on ray $MN$ (Fig. 8; in the case where $M$ is left infinitely
remote point, ray $MN$ is the entire straight line).
Let's draw the segments $AX$ and $BM_1$.
2) Point $B$ lies on ray $NM$ (Fig. 9). This case is “symmetrical” to the first. Let's draw segments $AN_1$ and $BX$.
3) Point $A$ lies on ray $MP$, mochika $B$ lies on ray $NQ$ (Fig. 10). Then you can connect $A$ with $X$, and $B$ with $M_1$ without intersections.
In all cases, there will be no intersections with the $i$-th shell according to Lemma 3.
Lemma 4 is proven.

Fig. 8

Now choose any segment $A_1B_1$ in the 1st shell and connect it with a segment from the 2nd (Fig. 11). Then we connect the segment $A_2B_2$ from the 2nd shell, which was not connected to the first, with a segment from the 3rd, etc. In each convex hull with an odd number, fill in the part between two consecutive convex hulls, excluding the quadrilateral formed by two connecting segments. In each shell with an odd number, fill in this quadrilateral. The outline of the shaded figure is the outline of the set.

Fourth solution.
Breaking minimum length
It is clear that the set of closed broken lines that can be drawn through $S$ is finite. Let us prove that the polygonal line has the minimum length.
Let there be some intersection $X$ of two links $AB$ and $CD$ of a broken line (Fig. 12). Replacement
If these two segments are on $AC$ and $BD$ or on $AD$ and $BC$, in one of the two cases the broken line will remain connected. But at the same time, its length will decrease, due to two triangle inequalities: $AC < AX + XC$ and $BD < BX + XD$, from which it follows that $AC + BD < AB + CD$. Likewise, $AD + BC < AB + CD$. This means that a closed broken line of minimum length is non-self-intersecting, i.e. is posyaom.

⟦folio 29⟧

---
running_head:
folio:
---

Fifth decision. Induction
Let us first prove the following lemma.
Lemma 5. Given a polygon M and a point A, there is also a line l separating M from A (i.e. M and A lie on opposite sides of l). Then some side M is entirely visible from point A (we will say that side PQ is completely visible from point A if there are no other points of the polygon inside the triangle APQ).
Proof. Let's paint each side of the polygon a different color. Let's consider the central projection of the polygon from point A to line l (an example is shown in figure 13). On straight line l

will be displayed as the polygon is visible from point A. For example, if a fragment of the red side obscures a fragment of the blue side, then the projection of the red side is shown on straight line l. If a vertex is projected to a point on line l, then we will draw in the projection the direction (arrow) in which one side blocks the other, i.e. the end of which side is the projection of the vertex.

Let the projection result in k segments. There are k-1 points between them, some of which indicate directions. Since there are more segments than points, no arrow points to any segment. This means that this is a projection of the entire side, i.e. the entire side is visible from point A.
The lemma is proven.
Let us prove point a) using this lemma. We will solve by induction on n. The base for n=3 points is very. Let's take point A - the vertex of the convex hull and remove it from the set. Point A can be separated by a straight line from the set of other points. Let us apply the induction hypothesis to it: through this set we can check the belt. By lemma, one side PQ

the belt is visible entirely from point A. Replacing the side PQ in the polygon with the broken line PAQ, we obtain the required polygon.

Solution to point 6)
Let us first prove that if all points lie on a convex hull, then f(S)=1. Let's assume the opposite. Then, in addition to the belt that coincides with the convex hull, there is at least one more belt. It contains link AB, which is a diagonal of the convex hull. The plane containing AB divides the plane into two half-planes, each of which contains points S. Points of one half-plane cannot be connected to points of the other, since otherwise they will intersect AB. This means that the belt cannot be closed. Contradiction.

Now we will prove that if f(S)=1, then all points lie on the convex hull. Let's assume the opposite. Inside the convex hull there is a point A from the set S. Consider the inclusion of a circle around A. There are n-1>1 of them, since A lies inside the convex hull. Contradiction.

Solution to point c)
Let us use the construction from the solution to the second part of paragraph 6). For n points, in the case where there is a point inside the convex hull, it gives the estimate f(S)≥n-1.

Let us prove that if there is only one point inside a convex hull, then f(S)=n-1. Let X denote a point inside the convex hull. It is connected to two points A and B from the convex hull, and the neighboring one. Otherwise, the belt is self-intersecting, since the link connecting the parts of the belt, composed of the group between A and B, must intersect AXB. Each of the neighbors, in turn, can only be connected to its neighbors, otherwise the network is self-intersecting from the same messages. We get that all possible constructions give a set of included zones around X. This means there are n-1 of them.

Solution to point d)
Let the points P and Q of a given set lie inside the convex hull. Consideration

⟦folio 30⟧

---
running_head:
folio:
---

rim two arbitrary sides $AB$ and $CD$ of the convex hull. figure 14 shows the case when these two sides do not have a common vertex, figure 15 – when they do. The number of ways to choose them is $\frac{(n-2)(n-3)}{2}$, since there are $n-2$ segments in the convex hull.

Let us show that it is possible to do at least one of two things in a convex hull:
1) replace $AB$ with segments $AP$ and $BP$, and $CD$ with segments $CQ$ and $DQ$ so that you get a polygon (i.e. there will be no self-intersections),
2) replace $AB$ with the segments $AQ$ and $BQ$, and $CD$ with the segments $CP$ and $DP$ so that you get a polygon.

Let $X$ be the point of intersection of lines $AB$ and $CD$, and $Y$ be a point on the segment $PQ$. Then the segments $AB$ and $CD$ lie in different half-planes relative to $XY$ (their vertices can lie on $XY$ only if this is their common vertex, and it will coincide with $X$), and the points $P$ and $Q$ too. (If there are no points $X$, because $AB$ and $CD$ are parallel, then we will consider together the straight line $XY$, the line passing through $Y$ and parallel $AB$ and $CD$.)

First consider the case where $P$ and $Q$ do not lie on $XY$. Then if $AB$ and $P$ are in the same half-plane, then the segments $AP$ and $BP$ lie in the same half-plane, and the segments $CQ$ and $DQ$ - in another. Therefore, the segments $AP$, $BP$, $CQ$, $DQ$ do not intersect and construction from point 1) is possible. If $AB$ and $Q$ are in the same half-plane, then the construction from point 2) is similarly possible.

If $P$ lies on $XY$, then $Q$ also lies on $XY$. The reasoning above also works in this case, if the segments $AB$ and $CD$ do not have a common vertex. If they have a common vertex, then it coincides with the point $X$, but then it turns out that the points $X$, $P$ and $Q$ from our set are collinear, but we consider only points in general position.

The proof is complete.

Comment. Everyone that may be interested to think about the following question to which we do not have an answer.

Let there be $k$ points inside the convex hull. What grades can there be for $f(S)$? We can look at the small values ​​of $k$ first:

1) Is it true that if there are at least two points inside the convex hull of the set $S$, then there is a quadratic lower bound on $f(S)$ (i.e., you can estimate $f(S)$ by a polynomial of the second degree)?

2) Is it true that if inside a convex hull the set $S$ contains exactly three points, then there is a cubic lower bound on $f(S)$?

Solution point d)

Let us first consider the case $n \leq 5$. It is easy to understand that $F(3) = 1$, $F(4) \geq 2$, $F(5) \geq 2$, while the value of the expression $3 \cdot 2^{\frac{n-8}{3}}$ is less than 1 for $n=3$ and less than 2 for $n=4$ and $n=5$, so the inequality is satisfied.

For $n \geq 6$, consider successive nested convex hulls, as in the third solution of part a). Let a point set be chosen such that the first hull contains 3, 4 or 5 points, and the remaining $k-1$ convex hulls are triangles (respectively, $n$ equals $3k$, $3k+1$ or $3k+2$, $k \geq 2$). Then there are at least 3 options for choosing the first segment. When connecting convex hulls, as in the third solution, there are two ways to choose a segment in each triangle (in each of the $k-1$ triangles, except the last one). Using inequality $3k+2 \geq n$, we get

$$F(n) \geq 3 \cdot 2^{k-2} \geq 3 \cdot 2^{\frac{n-8}{3}}.$$

Solution problem.

⟦folio 31⟧

---
running_head:
folio:
---

In fact, it has been proven that the function $F(n)$ grows as $b^n$, where $4,642 \leq b \leq 56$.
Well-known results about this can be read in the chapter “Problems about points in general position” of the book by P. Brass, W. Moser, J. Pach “Discovery of the problem of discrete geometry” (MCNMO, 2021), as well as on the Erik Demaine website: https://erikdemaine.org/polygonization/

Related tasks
1. Let the given polygon and the point $P$ be inside it. Is any side of the polygon necessarily visible in its entirety from point $P$? What if point $P$ is outside the polygon?
2. There are several non-intersecting segments on the plane. Is it always possible to connect the ends of some of them with segments so that a closed non-self-intersecting polyline is obtained?

3. Triangulation of a set of points is a planar graph, where the vertices are all the points of the set, the edges are the segments connecting the points, and all the faces, except the outer one, are triangles. Consider the triangulation of the set $S$. Is it true that any triangulation of the set $S$ can be turned into fields by removing some edges?

4. Consider the set $S$ of points in general position. Let's look at all kinds of belts. Let there be more than one. Could they all have a common link?

5 (P. Kozhevnikov, Cup in memory of A.N. Kolmogorov, 2013). On the given plane there is a finite set $S$ of $n > 2$ points in general position (i.e., no three points lie on the same line). Consider all polygons whose vertex set coincides with $S$. Is it true that the union of all such polygons necessarily coincides with the convex hull of the set $S$?

MONGOL LETTER
(see page 2 of the cover)
You can see that each word is written as a sequence of characters located on a common vertical line. Two words that begin with the sound $t$ begin with the same sign $y$.
From here we can suggest that the letter is alphabetical and its direction is from top to bottom. It is not difficult to establish what some signs correspond to:
sr kn m

The vowel $y$ is written as $q$ in all cases. If it is at the beginning of a word, then it is preceded by a “c” sign, identical to the sign for $a$ in the middle of the word. This sign is always placed at the beginning of a word if it begins with a vowel; if words begin with $a$, the sign is repeated twice.

Then o is written as $q$.

Task 1
“Crisis” – kimural, 2 – mark, 3 – Altai.
Word 2 apparently means "stamp" (in Mongolian it is the word for "postage stamp"). Word 3 means Altai (geographical region or Altai Mountains).

Task 2
Söri “stack” aimural “depravity” italy “Italy”

(at the end of the words $a$ and $n$ are not distinguished).

⟦folio none⟧

---
running_head:
folio:
---

To study an event in the world of physical phenomena, you must first know where and when it occurred. Answer the question where? - means to indicate the place of enlightenment...

Arthur Chernin

The fact that three points on the plane arose to associate such weights so that the given fourth point turned out to be their center ... led me to a new method for specifying points on the plane.

August Mobius

Let's draw two lines (coordinate axes) intersecting at right angles and set the position of the particle... by the distances from it to each of the axes.

Richard Feynman

...the law of nature does not allow us to know both the position and the velocity of a particle with any accuracy that we would like.

Werner Heisenberg

This happened in the phase space of one of many closed systems. Coordinate after long journeys I was tired and completely exhausted.

Lev Blumenfeld
