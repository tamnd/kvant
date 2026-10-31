---
id: 1974-12-vasilev-vokrug-formulyi-pika-607c9052
issue: kvant_1974_12
year: 1974
number: "12"
title: Around the Pick formula
authors:
  - Васильев Н. Б.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 41
page_last: 45
page_labels: 39-43
tag: 11SQ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4432e0aa51babb294acb2c5cb4089ea7187919817f6c9f0506175de995d0bd15
prompt_sha256: draft-1
translated_from: content/ru/1974/12/articles/11_vasilev-vokrug-formulyi-pika-607c9052.md
source_content_sha256: a0f19f83239ff3f9b463358045aeac9a1b4bcacb22471dc37f727ed3f3144ad6
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 39⟧

To estimate the area of ​​a polygon drawn on checkered paper, it is enough to count how many cells cover this polygon (we take the area of ​​a cell as one). More precisely, if $S$ is the area of ​​the polygon, $N_1$ is the number of cells that lie entirely inside the polygon, and $N_2$ is the number of cells that have at least one common point with the interior of the polygon, then $N_1 \leqslant S \leqslant N_2$. (This fact can be used to give precise definitions of the area of ​​a polygon and other functions.)

We will consider below only such polygons, all of whose vertices lie at the nodes of the checkered paper - at the points where the grid lines intersect. It turns out that for such polygons you can specify a simple formula:

$$S = \frac{r}{2} + i - 1,$$

where $S$ is the area, $r$ is the number of nodes that lie on the boundary of the polygon (that is, on the sides and at the vertices), $i$ is the number of nodes that lie strictly inside the polygon.

This formula is sometimes called the “Pick formula” - after the mathematician who discovered it in 1899. (However, we cannot be sure that no one has come up with this natural formula, which allows for a number of different proofs.)

⟦folio 40⟧

ke 1, you will see that the area is always equal to the “receiving” number - a number of the form $m/2$, where $m$ is an integer.

Let's call a triangle simple if there are no mesh nodes inside it or on its sides, with the exception of its vertices. (This name was chosen because any other triangle can be made from simple ones; this is one of the statements we come across below.) Note that all simple triangles on figure 1 have area 1/2. We will see that this is not accidental.

In the solution to Problem M226, published in «Kvant», 1974, No. 6, the reader was asked to think about such a problem. Three grasshoppers (at urine) at the initial moment of time sit at the three vertices of one cell, and then begin to “leapfrog”: each can jump through one zone of the other two, after which it ends up in a symmetrical relative neo-point (Fig. 2; it is clear that after any number of jumps the grasshoppers will end up in the nodes of the cell). In what projections can grasshoppers end up after a few jabs?

Let's call a triangle distributive if three grasshoppers can simultaneously appear at its vertices, which were initially at three vertices of one cell; we will call a jump a transformation of a triangle, which consists in the fact that one of the vertices goes to a point symmetrically relative to any of the other two vertices (these two vertices remain in place).

Theorem 1. The following three properties of triangles with vertices at checkered paper nodes are equivalent to each other:

1) a triangle has an area of ​​1/2;
2) the triangle is simple;
3) triangle is distributable.

You can be convinced of the validity of this theorem by proving the following theorem: those whose proof is indicated at the end of the course are marked. The rest are almost very good if you prove them in this order:

$$3 \Rightarrow 4 \quad 1 \Rightarrow 2 \quad 10$$

$$5 \Rightarrow 6 \Rightarrow 7 \Rightarrow 8 \Rightarrow 9 \Rightarrow 11 \Rightarrow 12$$

1. The area of ​​the triangle does not change when jumping.
2. Any available triangle has area 1/2.
3*. If you complete a simple triangle $ABC$ to a parallelogram $ABCD$, then there will be no nodes (not counting the vertices) either inside or on the sides of this parallelogram.
4*. From a simple triangle, when jumping, it turns into a simple one.
5*. A simple triangle has one of the angles - obtuse or straight (and the latter case is possible only for a triangle whose three vertices belong to one cell; we will call such a simple triangle with sides 1, 1, $\sqrt{2}$ minimal).
6. From any simple non-minimal triangle you can get in one jump a triangle whose most sides are smaller than the most sides of the original one.
7*. Any simple triangle can be converted into a minimal one with a finite number of jumps.
8. Any simple triangle is accessible.
9. Any simple triangle has area 1/2.
10*. Any triangle can be cut into simple ones.
11. The area of ​​any triangle is equal to $m/2$, and any time it is cut into primes, their number is equal to $m$.

⟦folio 41⟧

12. Any triangle with area 1/2 is simple.
It is clear that Statements 2, 8 and 12 imply Theorem 1.
Prove some more properties of triangles.
13. For any two lattice nodes A and B, on the segment between which there are no other nodes, there is a node C such that triangle ABC is simple.
14. Node C in the previous problem can always be chosen so that angle ACB is obtuse or right.
15. A parallelogram if and only if we generate a lattice consisting of all the nodes of checkered paper (see article by A. A. Egorov, p. 26) when each of the triangles into which the diagonal divides it is simple.
The same property can be formed like this.
16. Triangle ABC is simple if and only if all possible triangles obtained from ABC by parallel translations that take node A to different lattice nodes do not overlap each other (Fig. 3).

Let us now return to the problem about the three blacksmiths. Let the blacksmiths in the initial position occupy some specific (and not arbitrary) minimal triangle - in the original formulation of the problem this is exactly what we assume. Since each grasshopper will be mixed up when jumping by an even number of cells horizontally and vertically, it will necessarily end up in a node “within it” of a lattice with a cell size of 2x2. On figure 4, three of the four "sublattices" that make up the entire lattice are colored different colors (each grasshopper jumps into the nodes of its

Colors), and the fourth is the same color as the grid line.

According to Theorem 1, blacksmiths can simultaneously hit the vertices of a simple triangle.

This leads to another interesting property of these triangles.

17. If the lattice - the nodes of checkered paper - is divided into four sublattices with 2x2 cells (Fig. 4), then the vertices of a simple triangle will necessarily fall into three different sublattices (all three have different colors).

Now it is not difficult to prove the following two statements, which give the answer to the problem of three grasshoppers (in the case when the initial triangle is fixed; Fig. 4).

18. Three smiths can simultaneously hit those and only those point tracks that serve as the vertices of a simple triangle and have the same color as the corresponding vertices of the initial triangle.

19. Two blacksmiths can simultaneously hit those and only those nodes of the corresponding colors, on the segment between which there are no other nodes.

Polygon triangulation
We have studied in detail a particular form of polygons on checkered paper, which in the Pick formula corresponds to the values ​​i = 0, r = 3, S = 1/2. But from this particular case you can go straight to the most general one, using the theorem on the resolution of an arbitrary polygon to a triangle (checkered paper is no longer needed).

⟦folio 42⟧

Fig. 5.

Let there be some given on the plane
which (not necessarily convex)
polygon and some finite
set of $K$ points lying inside
polygon and on its boundary
(and all the vertices of the polygon belong to the set $K$).
Triangulation with vertices $K$ is a partition of a given polygon into triangles with vertices in the set $K$ also such that each point from $K$ serves as a vertex of each of those triangulation triangles to which this point belongs (that is, points from $K$ do not fall inside or on the sides of triangles, see Fig. 5).

Theorem 2. a) Any $n$-gon can be cut by diagonals into triangles, and the number of triangles will be equal to $n-2$.
(This partition is a triangulation with vertices at the vertices of a $n$-gon.)

6) Let there be $r$ points on the border of the polygon (including all vertices), and another $i$ points inside. Then there is a triangulation with vertices at offset points, and the number of triangles maximalmente will be equal to $r+2i-2$.

Of course, a) is a special case, 6), when $r=n$, $i=0$. We will again break down the proof of this theorem into a series of simple statements.

20*. From the vertex of the most angle of a $n$-gon ($n>3$) it is always possible to draw a diagonal that lies entirely inside the polygon.

21. If a $n$-gon is cut diagonally into a $p$-gon and a $q$-gon, then $n=p+q-2$.

22. Any $n$-gon can be cut by diagonals into $n-2$ triangles.

23. The sum of the angles of a $n$-gon is $180^\circ \cdot (n-2)$.

24. For any triangle, inside and on the border of which several points are offset (including all three of its vertices), there is a triangulation with vertices at the offset points.

25. The same is true for any $n$-gon.

26. The number of triangulation triangles is $r+2i-2$, where $i$ and $r$ are the number of offset points of the corresponding inside and on the border of the polygon.

This implies Theorem 2.

27. Derive Pick's formula from Theorems 1 and 2: $S=r/2+i-1$.

A technique that is convenient to use in the proof of Statement 26—calculating the sum of angles—also helps in solving other combinator problems in geometry, in particular, about dividing a polygon. Let's give two more examples.

We call a partition of a $n$-gon into several polygons correct if each vertex of one of the polygons of the partition serves as the vertex of all other polygons of the partition to which it belongs.

28. If from the vertices of $k$-gons on which a $n$-gon is divided in a regular way.

⟦folio 43⟧

Fig. 7

nick, $i$ vertices lie inside and $r$ vertices lie on the boundary of the $n$-gon, then the number of $k$-gons is

$$m = \frac{r + 2i - 2}{k - 2}.$$

29 (Variant of “Euler’s theorem”). If $N_0$ points in the plane and $N_1$ segments with endpoints at these points form a polygon, regularly divided into $N_2$ polygons, then (Fig. 6) $N_2 - N_1 + N_0 = 1$.

Multiple tasks

The main application of the Pick formula is not with calculating the areas of specific polygons, but with various problems and theorems about broken lines on checkered paper.

30. Let the ratio of the area of ​​a polygon to the square of one of its sides be irrational (this is the case, for example, for a regular triangle). Prove that a similar polygon cannot be placed on checkered paper so that the vertices lie at the nodes.

31. Let $A$ and $B$ be two knots of checkered paper, of which the second is $p$ cells to the right and $q$ higher than the first (that is, the distance between the nodes is $\sqrt{p^2 + q^2}$). What is the distance to the line $AB$ from the node closest to it that does not lie on this line?

32. The chess king walked around the board $8 \times 8$ squares, hitting each square exactly once and with the last move they returned to the original square. The broken line connecting the successive centers of the fields that the king passed through has no self-intersections.

Fig. 8.

a) What is the greatest length it can have?

6) What area can this broken line enclose? (The side of the cell is 1.)

Problem a) has already been dealt with in «Kvant» No. 5 for this year (p. 52) - it has number M220 in “Problem Book” «Kvant». Here we will give another solution. But let's start with task 6). From Peak’s formula it immediately follows that the area bounded by the broken line is equal to $64/2 - 1 = 31$ (the centers of 64 fields serve as the nodes of the checkered paper; according to the condition, they all lie on the boundary of the polygon). Let's move on to problem a). At figure 7 there is an example of a king's path in which 36 of the 64 moves are of length $\sqrt{2}$ (directed diagonally). Let us prove that there cannot be more than 36 such moves.

On each segment of length $\sqrt{2}$ included in the king’s path, we construct a square $1 \times 1$, as on a diagonal. However, the base of this square lies outside the polygon that limits the path of the king. But the total area occupied by such positions does not exceed 49 - 31 = 18, since they all extend beyond the square $7 \times 7$ of checkered paper. This means that the number of diagonal moves does not exceed 36.

So, the answers to problem 32:

a) $28 + 36\sqrt{2}$; 6) 31.

33. It is necessary to check, along the lines of the grid, a closed, non-self-intersecting broken line that would pass through all the nodes of the checkered paper lying inside the straight line $p \times q$ cells.

a) For what $p$ and $q$ is this possible?

b) What length will this broken line have?

b) What area will it enclose? (Fig.8).
