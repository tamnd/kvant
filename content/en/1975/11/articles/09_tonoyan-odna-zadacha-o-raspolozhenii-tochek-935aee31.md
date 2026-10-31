---
id: 1975-11-tonoyan-odna-zadacha-o-raspolozhenii-tochek-935aee31
issue: kvant_1975_11
year: 1975
number: "11"
title: One problem about the location of points
authors:
  - Тоноян Г. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 28
page_last: 30
page_labels: 26-28
tag: PBTR
lang: en
source: kvant_digital
extraction: vision
content_sha256: acfbb43ded0cdbac971aea68b6d16463e17ef097e07ecab95918815149da1d92
prompt_sha256: draft-1
translated_from: content/ru/1975/11/articles/09_tonoyan-odna-zadacha-o-raspolozhenii-tochek-935aee31.md
source_content_sha256: 1e86773748850f4a3fd4c2d4b14f1e398c3edbecb84abf3627d1d6cba9225095
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

One problem about the location of points

G. A. Tonoyan

Let there be $n$ points on the plane, no three of which lie on the same line (we will only consider such sets of points). It is clear that if $n \geq 3$, then we can find the simplest convex *) polygon - a triangle - with vertices at three of these points.

Is it always possible to find a convex quadrilateral with vertices at these points for $n > 3$? If $n = 4$ and the points are the vertices of a non-convex quadrilateral, then this follows. If $n \geq 5$, then for any arrangement of points it is possible to find a convex quadrilateral. Indeed, if the convex hull of our set **) is a $k$-gon, where $k > 3$, everything is fine - any four vertices of this $k$-gon are the vertices of the required quadrilateral. Let $k = 3$ be the convex hull of triangle $ABC$. then there are at least two points - $D$ and $E$ - lying inside this triangle (see Fig. 1). Prima $DE$ does not pass through the vertices of triangle $ABC$. Therefore two of

*) Recall that a polygon is called convex if, together with each two points, it contains a segment connecting them.
**) The convex hull of a set of points on a plane is the minimal convex polygon that contains them. Since the intersection of two convex polygons is a convex polygon, this definition is correct.

Fig. 1.

⟦folio 27⟧

Fig. 2.
the locus of the set $N \setminus K$ - the set obtained by removing from $N$ its subset $K$, and through $M$ - the set $(N \setminus K) \setminus L$.

Let us consider the following possibilities: 1) the set $M$ is empty; 2) the set $M$ consists of a single point; 3) the set $M$ contains at least two points.

1) The set $M$ is empty. Then $N$ contains only the vertices of the polygons $K$ and $L$, that is, at most 8 points (since each of the polygons $K$ and $L$ is a triangle or quadrilateral).

2) The set $M$ contains a single point; let's denote it by $P$. If $L$ is a quadrilateral, then by drawing one of its diagonals, we divide it into two triangles; the point $P$ lies inside one of them (Fig. 3). Let us denote the vertices of this triangle by the letters $A, B, C$. If $L$ is a triangle, then we denote

Fig. 3.

its vertices through $A, B, C$; point $P$ lies inside this triangle.

In any case, among the vertices of the polygon $L$ will also find three vertices $A, B, C$, such that $P$ is the interior point of the triangle $ABC$.

Let us draw rays $PA, PB, PC$ from point $P$. They divide the plane into three angles $APB, BPC, CPA$. It is easy to see that each of these angles contains at most one vertex of the polygon $K$. In fact, let, for example, the angle $APB$ contain two vertices of the polygon $K$, and therefore contain some side $RQ$ of the polygon $K$. Then the points $A, P, B, Q, R$ are the vertices of a convex pentagon (Fig. 4), which is impossible. Therefore $K$ has at most three vertices (one in each of the considered corners). Since $L$ has at most four vertices, and $M$ is assumed to consist of a single point $P$, the set $N$ contains at most eight points.

3) The set $M$ contains at least two points. Let us denote by $E$ and $F$ any two points of the set $M$.

Let us first assume that $L$ is a quadrilateral. Let us assume that $EF$ does not pass through the vertices of the polygon $L$ and intersects its two sides. If $EF$ intersected two adjacent sides of the quadrilateral $L$ (Fig. 5), then the other three vertices $B, C, D$ of the quadrilateral $L$, along with $E$ and $F$, were the vertices of the convex pentagon. Therefore, $EF$ intersects

⟦folio 28⟧

shows two opposite sides of the quadrilateral $L$.

For example, let ray $EF$ intersect side $AB$, and ray $FE$ intersect side $CD$ (Fig. 6). Let's draw the rays $FA$, $FB$, $EC$ and $ED$. Together with the segment $EF$ they divide the plane into 4 parts. If inside the angle $AFB$ (which is one of these four parts) there were two vertices of the polygon $K$, and therefore also the other side $TR$ of the polygon $K$, then the points $A$, $F$, $B$, $T$, $R$ were the vertices of a convex pentagon (Fig. 7). Therefore, inside the angle $AFB$ there is at most one vertex of the polygon $K$. Similarly, inside the angle $CED$ there is at most one vertex of the polygon $K$. As for the remaining two parts, the vertices of the polygon $K$ cannot be located in them (otherwise, together with the points $A$, $F$, $E$, $D$ or $B$, $F$, $E$, $C$ they would be formed by a convex pentagon, Fig. 6).

Fig. 5.

Fig. 6.

Fig. 7.

it turns out that $K$ has no more than two vertices (one each inside the corners $AFB$, $CED$), which is impossible, since $K$ is a triangle or a quadrilateral.

Finally, suppose that $L$ is a triangle. Let's use $EF$ to separate one vertex of this triangle.

For example, let ray $EF$ intersect side $AB$, and ray $FE$ intersect side $AC$ (Fig. 7). Reasoning, as before, we find that the angles $AEC$ and $AFB$ contain no more than one vertex of the polygon $K$, and the part of the plane bounded by the rays $EC$, $FB$ and the segment $EF$ does not contain the vertices of the polygon $K$ at all.

So, the assumption that $M$ contains at least two points leads to a contradiction. If $M$ is empty or contains one point, then $N$ has at most all points. This completes the proof.

Exercises

1. Prove that if all quadrilaterals with vertices at some $n$ points are convex, then these $n$ points are the vertices of a convex $n$-gon.
2. On the plane given $n$ points. Prove that there are at least $\frac{C_n^3}{n-4}$ convex quadrilaterals with vertices at these points.
3. There is an infinite number of points on a given plane. Prove that for any $k$ there is a convex $k$-gon with vertices at these points.
(We remind you that only polygons in which no three points lie on the same line are considered.)
