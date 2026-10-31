---
id: 1973-10-ionin-kurlyandchik-okrestnost-figuryi-bce08ac7
issue: kvant_1973_10
year: 1973
number: "10"
title: Neighborhood of a figure
authors:
  - Ионин Ю. И.
  - Курляндчик Л. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 45
page_last: 47
page_labels: 43-45
tag: QBLC
lang: en
source: kvant_digital
extraction: vision
content_sha256: 87223cc1b57657b43dffcb85caa3949bbba7c8420af6bc180691e7d2044ee7ee
prompt_sha256: draft-1
translated_from: content/ru/1973/10/articles/13_ionin-kurlyandchik-okrestnost-figuryi-bce08ac7.md
source_content_sha256: dc0b442a4bd2a586fc239ebc0157cbdc6eb4a6dec7c3148e8e0683a34b954092
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 43⟧

Neighborhood of a figure
Yu. I. Ionin,
L. D. Kurlyandchik

Let us analyze two geometric problems.

Problem 1. 120 unit squares are thrown into a 20 × 25 rectangle. Prove that a circle of radius $1/2$ can be placed in a rectangle and does not intersect any of the squares.

Let us find out where the center of a circle of radius $1/2$ can be located that does not intersect the given unit square. The geometric locus of points distant from the square by no more than $1/2$ is the figure depicted in figure 1 (the distance from a point to a figure is the distance to the nearest point of this figure). Consequently, the center of a circle of radius $1/2$, which does not intersect the square, is located outside the depicted distance to the nearest point of this figure). Consequently, the center of a circle of radius $1/2$, which does not intersect the square, is located outside the depicted distance to the nearest point of this figure). Let us construct a $\frac{1}{2}$-neighborhood for each of the given 120 unit squares. The center of the desired circle must lie outside these neighborhoods. In addition, for the circle to be inside the rectangle, its center must belong to the smaller rectangle $19 \times 24$, which will be obtained if some side of the original rectangle is shifted inside by $\frac{1}{2}$.

The problem will be solved if we ensure that the constructed 120 neighborhoods do not completely cover the smaller rectangle.

Let's estimate the area and cover it with these surroundings. Each neighborhood consists of a square of state 1, four rectangles $1 \times \frac{1}{2}$ and four quarter circles of radius $\frac{1}{2}$. Therefore, the area of ​​one neighborhood is $1 + 4 \cdot \frac{1}{2} + \pi \cdot \left(\frac{1}{2}\right)^2 = 3 + \frac{\pi}{4}$. All 120 neighborhoods cover an area no larger than (neighborhoods may overlap) $120 \cdot \left(3 + \frac{\pi}{4}\right) = 360 + 30\pi$.

At the same time, the area of ​​the rectangle $19 \times 24$ is equal to 456. It remains to note that $360 + 30\pi < 456$, since $\pi < 3.2$.

Problem 2. A plane figure of area 1 is covered by a finite number of circles. Prove that from these circles one can choose one or more pairwise disjoint circles occupying an area of ​​at least $\frac{1}{9}$.

Let's choose the largest of these circles and denote it by $R_1$

⟦folio 44⟧

Fig. 2.

its radius. If the area of ​​this circle is not less than $\frac{1}{9}$, solve the problem. Let's assume that $\pi R_1^2 < \frac{1}{9}$. Since the radii of the remaining circles are not greater than $R_1$, then the centers of those that intersect with the selected circle lie in the $R_1$-neighborhood of this circle. The circles themselves lie in the $2R_1$-neighborhood of the selected circle (Fig. 2). Since the area of ​​this $2R_1$-neighborhood, equal to $9\pi R_1^2$, is less than 1, then there are circles that do not intersect with the one selected from such circles. If $\pi R_1^2 + \pi R_2^2 \geq \frac{1}{9}$, solution problem. If $\pi R_1^2 + \pi R_2^2 < \frac{1}{9}$, then $9\pi R_1^2 + 9\pi R_2^2 < 1$, therefore, there is a circle whose center lies outside the $R_1$-neighborhood of the first and outside the $R_2$-neighborhood of the second circle and which therefore does not intersect with these circles. Let us denote by $R_3$ the radius of the largest of the circles that do not intersect with one of the two selected circles. If $\pi R_1^2 + \pi R_2^2 + \pi R_3^2 \geq \frac{1}{9}$, solution problem, otherwise we repeat the reasoning. Thus, each time we either find several pairwise disjoint circles, the sum of which is not less than $\frac{1}{9}$, or we find another circle that does not intersect with any of the ones found. The latter will ultimately turn out to be impossible since there are a finite number of circles.

In both problems analyzed, the concept of a figure’s neighborhood turned out to be useful.

Definition 1. Let $\varepsilon$ be a positive number. The $\varepsilon$-neighborhood of the plane figure $F$ is called the set of all sinks of the plane, the distance $*$ of which to the figure $F$ does not exceed $\varepsilon$.

We can describe the $\varepsilon$-neighborhood of a plane figure a little differently.

Definition 2. Let us construct circles of radius $\varepsilon$ with centers at each point of the figure $F$. The set of sinks of all these circles is the $\varepsilon$-neighborhood of the figure $F$.

The concept of $\varepsilon$-neighborhood can also be applied to a body in space. It is only necessary to consider, together with circles, balls of radius $\varepsilon$ with centers at points of the body.

Let us find out what the $\varepsilon$-neighborhood of a convex polygon is. It is easy to understand that it consists of the polygon itself, rectangles of height $\varepsilon$, built on its sides as on the bases and located outside the polygon, and circular sectors of radius $\varepsilon$ with centers at the vertices of the polygon (Fig. 3). Central angle sec-

*) Point $O$ is said to be at a distance from figure $F$ if every circle with center $O$ and radius less than $\varepsilon$ does not intersect with figure $F$, and every circle with radius less than $\varepsilon$ does.

⟦folio 45⟧

Fig. 4.

the torus at each vertex of the polygon complements up to 180° the internal angle of the polygon at this vertex. Therefore, the sum of all central angles is equal to 180° $n$ - 180° ($n$ - 2) = 360°, ($n$ is the number of the side of the polygon, 180° ($n$ - 2) is the sum of its internal angles). This means that by arranging the sectors without overlap and aligning their centers, we get a circle of radius $e$. Now it is easy to calculate the area of ​​the $\varepsilon$-neighborhood of a convex polygon. It is equal to $S + P\varepsilon + \pi e^2$, where $S$ is the area of ​​the polygon, $a$ is its perimeter.

Let's consider another problem that can be easily solved if we use clear neighborhoods of the figure.

Problem 3. The point $A, B, C, D$ is located in the maximum space such that the lengths of the segments $AC$ and $BD$ do not exceed 1. Prove that for each point $M$ of the segment $AB$ one can find the maximum point $N$ of the segment $CD$, that the length of the segment $MN$ will not exceed 1.

The statement to be proved can be formulated as follows:

Each point of the segment $AB$ is no more than 1 from the segment $CD$, that is, it belongs to the 1-neighborhood of the segment $CD$. This neighborhood consists of a right circular cylinder of radius 1, the axis of which is the segment $CD$, and two hemispheres of radius 1, the axis of which is the segment $CD$, and two hemispheres of radius 1 with centers at points $C$ and $D$, the bases of which are the bases of the cylinder and which are located outside the cylinder (Fig. 4). From the conditions of the problem it follows that the points $A$ and $B$ belong to the 1-neighborhood of the segment $CD$, and since this neighborhood is convex, it contains the entire segment $AB$, which is what needed to be proved.

Exercises

1. The sides of the convex polygon perimeter $P$ are moved parallel to themselves outward by a distance of 1 and continued until they intersect. Prove that the area of ​​the polygon will increase by more than $P + \pi$.

2. Find the volume of the $\varepsilon$-neighborhood of the unit cube.

3. In the parallelepip $5 \times 10 \times 25$ there are 120 unit cubes arranged in an arbitrary manner. Prove that it is possible to place a ball of radius $1/2$ in a parallelepip that has no common points with any of the cubes.

4. There are several regular triangles on the plane covering area 1. Prove that from them one can choose one or more pairwise disjoint triangles with a total area of ​​at least $1/16$.

5. 100 convex polygons are thrown into a square with a side of 38 cm, the area of ​​each of which does not exceed $cm^2$; and perimeter is 2π cm. Prove that a circle of radius 1 can be placed in a square and does not intersect any of the polygons.

6. Prove that a circle of radius $\frac{S}{P}$ can be placed in a convex polygon of area $S$ and permeter $P$.

7. In a square on side 1 there are 6 segments of length $1/2$. Prove that on some two segments he will find points $M$ and $N$, located between which there are less than $1/4$.
