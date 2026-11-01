---
id: 1988-2-vasilev-gutenmaher-summa-uglov-sfericheskogo-mnogougolnika-3eeb551c
issue: kvant_1988_2
year: 1988
number: "2"
title: Sum of angles of a spherical polygon
authors:
  - Васильев Н. Б.
  - Гутенмахер В. Л.
rubric: shkola-v-kvante
page_first: 57
page_last: 57
page_labels: "55"
tag: 5RYQ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0cda8bfe2a4d4e005f8160d16b52453820145772c919172d6b6e98589a7a04cf
prompt_sha256: draft-1
translated_from: content/ru/1988/02/articles/17_vasilev-gutenmaher-summa-uglov-sfericheskogo-mnogougolnika-3eeb551c.md
source_content_sha256: a8ef19958915666a094418e0790ae483e0aba1d98884a8f1f3b651ea35235186
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 55⟧

ra. From the formula $B-P+M=1$ for the map we obtain the formula $B-P+\Gamma=2$ for the polyhedron.

Euler's general theorem

Using the sum of angles to prove Euler's theorem is a nice, but somewhat artificial, technique. In fact, Euler’s theorem is also true for a more general situation - for example, for an arbitrary map with $B$ vertices, $P$ edges and $\Gamma$ countries on a sphere, and any segments of curves can serve as “edges”, as long as each country has a border of several continuous edges (in particular, there should be no “holes” inside the country, applies to other countries). However, among the possible ideas for proving the theorem in such a larger generality is induction, based on “contracting” one of the countries to a point.

The following note is devoted to the sum of the angles of a polygon on a sphere and Euler’s theorem for a map on a sphere.

Sum of angles of a spherical polygon

On a sphere we will consider polygons whose sides are arcs of great circles. Such a polygon can be obtained as the intersection of a sphere with a polyhedral angle whose vertex lies at the center of the sphere $O$ (Fig. 1). The magnitude of the angle of a polygon on a sphere is naturally considered to be the angle between the tangents to its “sides” drawn from the vertex; since the tangents are perpendicular to the radius drawn to the vertex from the point $O$, the angle of the polygon on the sphere is equal to the two-angle angle at this radius.

The analogy between the “sum of angles” and area, which we briefly mentioned in the previous note, is made tangible here: one quantity is simply expressed through the other.

Theorem. The area of ​​a polygon on a sphere is proportional to the difference between the sum of its angles and $180^\circ(n-2)$, where $n$ is the number of vertices of the polygon.

The coefficient of proportionality depends only on the radius of the sphere. Taking the radius of the sphere as one (then the area of ​​the sphere is equal to $4\pi$) and let us agree

Fig. 1.

angles are measured not in degrees, but in radians ($180^\circ$ corresponds to $\pi$ radians). Then the area of ​​a $n$-gon on a sphere is equal to $\alpha_1+\alpha_2+\dots+\alpha_n-\pi(n-2)$, where $\alpha_1, \alpha_2, \dots, \alpha_n$ are its angles.

In particular, the area of ​​a triangle on the unit sphere with angles $\alpha, \beta, \gamma$ is equal to $\alpha+\beta+\gamma-\pi$.

Let's check the formula $S=\alpha+\beta+\gamma-\pi$ for the outline of a sphere cut out of it by mutually perpendicular planes passing through the center: this outline has three angles of $\pi/2$ each, and according to the formula its area is equal to $3\pi/2-\pi=\pi/2$ - indeed, this is $1/8$ part of $4\pi$, the area of ​​all spheres.

It is enough to prove this theorem for a spherical triangle: the general formula can be obtained from this particular case in the same way as when proving the theorem on the sum of angles of a plane $n$-gon - using cutting and mathematical induction.

Continuing the sides of the spherical triangle, we get three large circles that divide the sphere into 8 triangles (it is convenient to imagine three planes of these large circles intersecting in the center $O$, dividing the space into 8 triangular angles - each of them carves a triangle on the sphere). Let us denote the angles of our triangle by $\alpha, \beta$ and $\gamma$, its area by $S$, the areas of the triangles adjacent to it (adjacent to the sides lying opposite the angles $\alpha, \beta$ and $\gamma$, respectively) by $a, b$ and $c$ (Fig. 2). Together with each triangle, our three
