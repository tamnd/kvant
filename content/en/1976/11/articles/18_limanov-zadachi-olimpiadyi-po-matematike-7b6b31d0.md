---
id: 1976-11-limanov-zadachi-olimpiadyi-po-matematike-7b6b31d0
issue: kvant_1976_11
year: 1976
number: "11"
title: Objectives of the Mathematics Olympiad
authors:
  - Лиманов Л. Г.
rubric: raznoe
rubric_sub: Разное
page_first: 62
page_last: 63
page_labels: 60-61
tag: NKA8
lang: en
source: kvant_digital
extraction: vision
content_sha256: eb53cbafc3bf5a170c3ca6441f7ee832c85e15e0378b30565abaa4a224164481
prompt_sha256: draft-1
translated_from: content/ru/1976/11/articles/18_limanov-zadachi-olimpiadyi-po-matematike-7b6b31d0.md
source_content_sha256: 69689008502478b57d3d0bef9c71c33cda50bc6d28fa8f33a764ab4092eb125e
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 60⟧

L. Limanov

Tasks
olympids
in mathematics

This article examines four problems of the final type of the X All-Union Mathematical Olympiad, which were not included in “Problem «Kvant». Solutions to problems published in “Zadachik” will appear in accordance with the issue of the magazine next year.

8th grade

1. Somehow there are 50 correctly running clocks on the table. Prove that at some moments the sum of the distances from the center of the table to the ends of the minute hands turns out to be greater than the sum of the distances from the center of the table to the centers of the clock.

Consider a triangle with the following vertices: the center of the table O, the end of the minute hand of i-x hours at time t - let’s denote it by the letter A_i - and the end of the minute hand of the same hours half an hour later - point B_i (Fig. 1). It is clear that the center of the i-x clock - point O_i - is the base of the median of the triangle A_i OB_i drawn from the vertex O. It is easy to prove that in an arbitrary triangle the double length of the median is less than the sum of the lengths of the ends of its sides (Fig. 2.)

Equality is possible only in the case when $A_iOB_i = 0$ (that is, when points A_i and B_i lie on a ray with its vertex at point O). But if at any moment of time $A_iOB_i = 0$, then i-e clocks are built, which contradicts the conditions of the problem, according to which all clocks are running correctly. Therefore, the moment of time t_0, when $A_iOB_i \neq 0$ and $2|OO_i| < |OA_i| + |OB_i|$, for the moment of time t_0 the requalification will be fulfilled

$$2(|OO_1| + |OO_2| + ... + |OO_{50}|) < (|OA_1| + |OA_2| + ... + |OA_{50}|),$$

or at time t_0 + 1/2 hour - $|OO_1| + |OO_2| + ... + |OO_{50}| < |OB_1| + |OB_2| + ... + |OB_{50}|$. And this is exactly what we needed to prove.

9th grade

2. Is it possible to line the vertices of a cube with various three-digit numbers made up of the digits 1 and 2 so that the numbers of any two adjacent vertices differ in at least two digits?

Let's consider the following coordinate system: the origin of coordinates is at the vertex of the lower base of the cube, and the positive directions of the coordinate axes coincide with the directions of the edges of the cube emerging from this vertex (Fig. 3). In this system, the coordinates of the cube vertices have the form: (0, 0, 0); (1, 0, 0), (0, 1, 0), (1, 1, 0), (0, 0, 1), (0, 1, 1), (1, 0, 1), (1, 1, 1), and only those vertices for which exactly two coordinates coincide are neighboring. Therefore, the question of the problem can be reformulated as follows: is there a mapping of the set of vertices of a cube onto itself such that all neighboring vertices of the cube change to be neighboring? Such a mapping exists; how it works can be seen from figure 4 (cube on

⟦folio 61⟧

This figure is depicted somewhat in the form of two “concentric” squares with “edges”). The blue arrows show where the vertices go (at figure 4 two vertices remain in place). Try to find out how many different such mappings there are.

10th grade

2. In a regular 1976-gon the midpoints of all sides and the midpoints of all diagonals are marked. What is the maximum number of cancellation points lying on one circle?

Answer: 1976. Let's prove it. The midpoints of all diagonals of the same length $l$ lie on the same circle, concentric with the circle in which the polygon is inscribed.

Since there are diagonals $\frac{1976}{2} = 988$ of different lengths (we also include side ones as “digogons”), all excellent points lie on 988 concentric circles, and the smallest of them is the radius of the field (expressed as a point - the center of our polygon). Therefore, a circle not from this family can contain no more than $1+2 \cdot 987=1975$ canceled points, since two “pole” circles intersect at two points, and we have another “non-pole” circle - a point that is the center of the polygon. The circle from the “concentric” family, passing through the middle side of our 1976-gon, contains 1976 cancellation points. In conclusion, we note that circles containing exactly 1975 cancellation points exist. However, one of them is depicted in figure 5 - this is a circle circumscribed around a regular 1976-gon, similar to the original one (with a coefficient of 1/2), in which one vertex coincides with the vertex of this polygon, and the remaining 1975 vertices are excellent: the midpoints of two sides and 1973 diagonals come out of this vertex.

3. On a square sheet of paper, $n$ rectangles are written on the side, parallel to the sides of the sheet. No two of these rectangles have common interior points. Prove that if you cut out these rectangles, then the number of pieces into which the remaining part of the sheet breaks up is no more than $n+1$.

The statement of the problem can be easily deduced from the following remark: the sum of the magnitude of the angles of a polygon adjacent to its internal angles is less than π, not less than 2π. (You can easily prove this fact yourself.) From the conditions of the problem it is immediately clear that the external angles of the resulting parts are either the internal corners of the cut rectangles (Fig. 6, a) or the external corners of our sheet of paper (Fig. 6, b), i.e. the sum of all external angles does not exceed 2π ($n+1$). But this also means that you will get no more than ($n+1$) pieces. From the proof it is clear that if there are ($n+1$) pieces, then all these pieces are convex.
