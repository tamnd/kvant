---
id: 1981-7-boltyanskiy-ploskie-grafyi-4bd19b1a
issue: kvant_1981_7
year: 1981
number: "7"
title: Planar graphs
authors:
  - Болтянский В. Г.
rubric: osnovnye-stati
page_first: 13
page_last: 18
page_labels: 11, 13, 14, 15, 16
tag: 1T1R
lang: en
source: kvant_digital
extraction: vision
content_sha256: 15bb1af3c37a3d80ec48c69f5dcfb53471527803311e4b52ed0f380b5ee421ee
prompt_sha256: draft-1
translated_from: content/ru/1981/07/articles/04_boltyanskiy-ploskie-grafyi-4bd19b1a.md
source_content_sha256: 0d0680b1199c527ef64b0b52edab650227c703aac0b8d27db39bc83b948125a8
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 11⟧

V. Boltyansky

Plockian graphs

In this article we continue the study of topological properties of graphs, begun in the previous issue of the journal. This time we will talk about some deep properties of planar graphs. Studying them will require the combination of the “devil of abstract algebra” and one of his minions - an invariant called the intersection index.

Three houses and three wells

A graph $A$ is said to be embeddable in a plane if there is a graph $A'$ on the plane that is geometric $A$. Thus, a graph composed of the edges of a tetrahedron and a graph composed of the edges of a cube are embeddable in the plane (Fig. 1).

Let us give two examples of graphs that cannot be embedded in a plane.

Example 1 (“houses and wells”). Six points are given on the plane: $D_1, D_2, D_3$ (houses) and $K_1, K_2, K_3$ (wells); Is it possible to draw tropics on a plane from each house to each well so that no two tropics intersect?

Fig. 1.
Fig. 2.

⟦folio 13⟧

that each cycle is a union of a finite number of broken lines, each of which is on a circle (and these broken lines in pairs do not have common links).

It is enough for Pozny to establish a fairly provable statement in the case when each of the cycles $x, y$ consists of one broken, home-sharing circle. By slightly moving the vertices of the cycles $x$ and $y$, we can ensure that the index $I(x, y)$ does not change and no segment included in the cycle $x$ is parallel to any segment included in $y$. Let us choose a territorial straight line $l$, not parallel to any straight line connecting any vertex of the cycle $x$ with any vertex of the cycle $y$, and we will continuously move the cycle $x$ (as a rigid whole) parallel to the straight line $l$ (Fig. 5). The intersection index $I(x, y)$ could change only at those moments when the vertices of the double cycle $x$ pass through the edges of the fixed cycle $y$ or when the edges of the cycle $x$ pass through the vertices of the cycle $y$ (the vertices of the cycle $x$ cannot get into the vertices of the cycle $y$ due to the choice of the straight line $l$). However, as figure 6 shows, at the moment when some edge $a$ of the cycle $x$ passes through the vertex $q$ of the cycle $y$, the number of intersection points does not change its parity, and therefore the intersection index $I(x, y)$ does not change. The same thing happens when the vertices of cycle $x$ pass through the edges of cycle $y$.

So, during the entire movement the intersection index does not change and is invariant. But eventually the cycle $x$ gets into a position where it has no points in common with $y$ (see Fig. 5), so the intersection index becomes zero. Consequently, it was originally $I(x, y) = 0$.

Non-embeddability of a complete pativertex graph

Now we are able to prove that the graph $P_2$ considered in Example 2 cannot be embedded in the plane. Let’s connect 5 points on the plane in pairs with broken lines, not paying attention to the intersections for now. Broken edges that do not have common ends are called non-stem conditions. Let us denote by $J$ the sum of intersection indices over all parameters of the RES edges. Of course, the number $J$ depends on how the edges are drawn on the plane. If they could be drawn without intersections, the number $J$ would turn out to be zero. However, we will prove that for any

⟦folio 14⟧

The way to check edges is that the number J is odd. This will prove that the graph $P_2$ cannot be embedded in the plane.

Suppose we change the position of one edge, say $M_1M_2$. We denote the initial position of this edge by $x$, and its new position by $x'$. Non-adjacent to edge $M_1M_2$ are three edges ($M_3M_4$, $M_4M_5$, $M_5M_3$). The closed polyline $M_3M_4M_5$ (possibly intersecting itself) is a cycle; let's denote it by $y$ (Fig. 7). The broken lines $x$ and $x'$, taken together, also form a cycle. Since the intersection index of any two cycles is zero:

$$I(x \cup x', y) = 0,$$

the number of points of intersection of the edge $x$ with the cycle $y$ (that is, with all edges not adjacent to it) has the same parity as the number of points of intersection of the edge $x'$ with the cycle $y$.

Thus, when replacing the edge $x$ with the edge $x'$, the number $J$ does not change its parity.

From what has been proved it follows that for any arrangement of edges on the plane, the number $J$ always has the same parity. Indeed, if two different arrangements of edges are given, then, sequentially noticing first one edge of the first arrangement with the corresponding edge of the second arrangement, then another, another, etc., we will gradually replace the first arrangement with the second, and the parity of the number $J$, by virtue of what has been proven, will not change.

So, either for all edge arrangements the number $J$ is even, or for all edge arrangements it is odd. There is only one intersection point on figure 3 (of course, the curved edges on this figure can be replaced by broken ones). Thus, on figure 3 the number $J$ is equal to one, and therefore for any arrangement of edges it is odd and, therefore, $P_2$ cannot be embedded in the plane.

Tasks

1. Prove that the graph $P_1$ from Example 1 cannot be embedded in the plane.
2. The edges of the graph are the sides and most diagonals of a regular $n$-gon

$(n > 3)^*$. Prove that for even $n$ this graph can be embedded in a plane, but if it is odd, it cannot.

3. The edges of the graph are the sides and most diagonals*) of a regular $2n$-gon. Prove that for $n \geqslant 3$ this graph cannot be embedded in the plane.
4. The edges of the graph are the sides and most diagonals*) (their $2n+1$ regular $(2n+1)$-gon. Prove that this graph cannot be embedded in the plane.

Couldn't it be simpler?

Above (see figure 5, 6) we proved that the intersection index of any two cycles in the plane is equal to zero. Perhaps the reader will suggest the following simpler proof: we will follow the closed broken line $x$; at each point of intersection with the closed broken line $y$ we will either enter the internal region of the broken line $y$ or leave it into the external region; since entry points and exit points through a point, the number of entry points is equal to the number of exit points; This means that the total number of intersection points of the broken lines $x$ and $y$ is even.

However, this proof can be considered correct only if the meaning of the concept “internal region” is already clear, and this concept is not at all as simple as each at first glance. The meaning of this concept is clarified.

Jordan's theorem

A closed line homeomorphic to a circle is called a simple closed line.

*) Moreover, the “diagonals” of the teacher are raised into space and therefore do not intersect in pairs.

⟦folio 15⟧

minced line. Jordan's theorem is that any simple closed line located on a plane divides this plane into two regions (internal and external). Let us explain the meaning of this theorem. Let $l$ be a simple closed line on the plane. Let us take points, $p, q$, that do not lie on the line $l$. If $p$ and $q$ can be connected by a broken line that does not intersect with $l$, then the points $p$ and $q$ are considered to lie in the same region relative to the line $l$. If any broken line connecting the points $p$ and $q$ necessarily intersects $l$, then we consider that $p$ and $q$ lie in different areas. Jordan's theorem states that the line $l$ defines two plane regions.

One should not think that Jordan's theorem states something perfect. Each of its “obviousness” is explained only by the fact that very simple lines usually come to mind (a circle, the contour of a convex polygon, etc.). In the general case, the statement

Fig. 8.

The end of Jordan's theorem is not very clear. figure 8 shows a simple closed polyline (this can be checked by tracing the line with a pencil). However, it is not at all very clear that the plane is cut by this line into two regions; for example, it is not immediately clear in which area (internal or external) the points $a, b, c, d$ lie.

We will give a proof of Jordan's theorem based on the application of the intersection index. In this case, we restrict ourselves to the case when $l$ is not an arbitrary simple closed line on the plane, but a simple closed broken line.

Let $b_1, b_2, \dots, b_n$ be successive links of the broken line $l$. Let's draw a segment intersecting link $b_1$ at point $a$, and take two points $p, p'$ on this segment, located on opposite sides of link $b_1$ at the same distance from it. Through points $p$ we draw a segment parallel to link $b_1$ to the point of its intersection with the bissertric of the angle between links $b_1$ and $b_2$ (Fig. 9). From this intersection point we draw a segment parallel to $b_2$ until it intersects with the bissertric of the angle between links $b_2$ and $b_3$, etc. As a result, we obtain a broken line $x$, the links of which are at the same distance from the corresponding links of the broken line $l$. If at the same time the point $p$ was taken close enough to $a$, then the constructed line $x$ does not intersect $l$, and walking along the line $l$ should return either to the point $p$ or to $p'$. It is easy to understand, however, that the broken line $x$ belongs to the point $p'$ if the broken line $x$ connected the points $p$ and $p'$, then by adding the segment $pp'$ to $x$, we would obtain a cycle that intersects with the cycle $l$ at a single point $a$, that is, the intersection index of these two cycles was equal to 1, which is impossible. So, $x$ is a closed polyline coming from the point $p$, passing once along the broken line $l$ and returning to the point $p'.$ Similarly, we get a closed polyline $x'$, leaving from $p'$, once passing along the broken line $l$ and returning to the point $p'$.

⟦folio 16⟧

Now let $c$ be an arbitrary point not lying on the line $l$. Then it can be facilitated without intersecting $l$, either with point $p$, or with point $p'$: it is enough to check from point $c$ the ray intersecting lines $x, x'$, and from point $c$ go to the first point of intersection of this ray with any of the line $x, x'$, and then along this line to the point $p$ or $p'$.

It is not difficult to understand that if two different broken lines $y, z$ are drawn from the point $c$, not intersecting $l$ and ending up at one of the points $p, p'$, then both of them end up at the same point. In fact, if the broken line $y$ connected the point $c$ with $p$, and the broken line $z$ connected the point $c$ with $p'$ (Fig. 10), then the broken line $y \cup z$ together with the segment $pp'$ would constitute a cycle whose index of intersection with cycle $l$ was equal to 1, which is impossible.

Now it is not difficult to prove Jordan's theorem. Let us denote by $U$ the set of all points of the plane that can be connected to the point $p$ without crossing $l$, and by $V$ the set of points that can be connected to the point $p'$ without crossing $l$. Then $U$ and $V$ will be the two areas on which the line $l$ divides the plane. In fact, if the points

$c_1, c_2$ belong to the same region (say $U$), then there are broken lines $y_1, y_2$, not intersecting $l$, that connect $c_1$ and $c_2$ to the point $p$. Their union is a broken line connecting $c_1$ and $c_2$ and not intersecting $l$. So, two points belonging to the same region can be connected by a polyline that does not intersect $l$ (otherwise, as above, we would get a cycle with intersection index 1 with $l$).

Thus, Jordan's theorem (for the case of a simple closed broken line) is proven.

Sweeping. All “far” points of the plane are located in the same area relative to the line $l$ (Fig. 11). Therefore, one of the two regions defined by the lines $l$ is not bounded, and the other is bounded. The unbounded region is called external, and the limited region is called internal. The points of the outer region are characterized by the fact that from these points one can check broken lines that do not intersect $l$ and go as far away from $l$ as desired; points in the interior region do not have this property.

Exercise.

5. If the broken line $l$ is very complex, then it is difficult to determine “by eye” in which area (internal or external) the point $a$ lies: for this you need to find out whether, starting from the point $a$, it is possible to exit the “labyrient” formed by the line $l$ (see Fig. 8). Prove that if a ray emanating from the point $a$ and not passing through the vertices of the broken line $l$ intersects $l$ in an even number of points, then the point $a$ lies in the external region (that is, it is possible to get out of the “labyrient”), and if in an odd number, then the point $a$ lies in the internal region.

6. $k$ broken lines are drawn on the plane, each of which connects two given points $p$ and $q$. Prove that if there are no other broken lines in pairs, then the plane is divided into $k$ regions.
