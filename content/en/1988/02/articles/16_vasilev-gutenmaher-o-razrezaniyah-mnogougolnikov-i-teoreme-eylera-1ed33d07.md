---
id: 1988-2-vasilev-gutenmaher-o-razrezaniyah-mnogougolnikov-i-teoreme-eylera-1ed33d07
issue: kvant_1988_2
year: 1988
number: "2"
title: On cutting polygons and Euler's theorem
authors:
  - Васильев Н. Б.
  - Гутенмахер В. Л.
rubric: shkola-v-kvante
page_first: 54
page_last: 56
page_labels: 52-54
tag: TWNF
lang: en
source: kvant_digital
extraction: vision
content_sha256: e8be19bd7bc616f7345702ca224c6e5828bdfb90c52a26d556394affe8f5e036
prompt_sha256: draft-1
translated_from: content/ru/1988/02/articles/16_vasilev-gutenmaher-o-razrezaniyah-mnogougolnikov-i-teoreme-eylera-1ed33d07.md
source_content_sha256: ed694020abeaa445f6c5d4e58a4915c960f88c7b0f76a605b0b1bf2b714f960c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 52⟧

nickname: the sum of its external angles is 360° (Fig. 4).

Since each exterior angle plus its adjacent interior angle adds up to 180°, the sum of all interior angles of an n-gon is 180°n−360°=180°(n−2).

This result is proved differently in the textbook: a convex n-gon can be divided into n−2 triangles by diagonals drawn from one vertex; the sum of all their angles, which is obviously equal to the sum of all n angles of an n-gon, is (n−2) times greater than the sum of the angles of one triangle.

Any, not necessarily convex, n-gon has the same sum of angles. But the proof is somewhat more complicated.

If you are trying to go around a “complex” polygon along a contour and calculate the sum of external angles - rotation angles, then, firstly, you will need to take into account the directions of rotation: counterclockwise rotation angles are considered positive, and clockwise rotations are considered negative (such rotations correspond to internal angles greater than 180°); secondly, it is not so obvious that as a result of traversing the polygon (a non-self-intersecting polygonal line), the total rotation will be one full rotation of 360°. Note that when going around the self-intersecting broken line at figure 5 - the spot of the angular star - the ruler makes two full revolutions, i.e. the sum of the external angles at the vertices of the star

Fig. 3.

Fig. 4.

Fig. 5.

720° is right (which means the sum of its internal angles is always equal to 180°×5−720°=180°; check this result by examining the triangles and the convex spot angle that make up the star).

You can prove the theorem on the sum of the angles of any polygon (not necessarily convex) using the cutting method. But more on that in the next post.

About polygon resolutions and Euler's theorem

By polygon we now mean a piece of a plane cut out by a non-intersecting broken line. Let's start with the fact that, as we did in the previous note, we will prove the theorem on the sum of the angles of any polygon (not necessarily convex) using the cutting method.

Of course, in the general case it is no longer possible to find a vertex from which all other vertices are “visible” (as for a convex polygon). It is not even entirely obvious that it is possible to find at least one diagonal that lies entirely inside the n-gon. But this fact is true.

Lemma. From any vertex of a newgon, the angle at which is greater than 180°, you can draw a diagonal that lies entirely inside this polygon.

Let us consider all possible rays coming from such a vertex inside the polygon (Fig. 1). They “illuminate”, perhaps partially, by

⟦folio 53⟧

at least two sides of the polygon. In fact, all rays that illuminate one side will fill an angle less than 180°. So, an angle of a polygon (greater than 180°) is divided into at least two angles, which are formed by rays illuminating different sides of the polygon. Then the ray separating two such angles is directed to the vertex of the polygon - along a diagonal that is entirely inside the polygon.

By using the lemma repeatedly, any $n$-gon can be cut into triangles. But we also need to keep an eye on the number of triangles. Like many other theorems that involve an arbitrary natural number $n$, the most convenient way to formulate the proof is using mathematical induction.

About mathematical induction

Here we use the principles of mathematical induction in this form. Let a certain statement, in the formulation of which the natural number $n$ is involved, be true for $n=n_0$, and from the fact that it is true for all $n$ such that $n_0 \leq n < N$, it follows that it is true for $n=N$. Then it is true for all natural $n \geq n_0$.

Let us prove the statement we need by induction.

Theorem. The sum of the angles of an arbitrary (not necessarily convex) $n$-gon is 180°($n-2$).

For $n=3$ this is true. Let our statement be true for all $n<N$ ($n \geq 3$). Consider a neoctorium $N$-gon. According to the lemma, it can be cut diagonally into two polygons. Let one of them have $K$ sides from a large $N$-gon - i.e. it is a $(K+1)$-gon, the other has $N-K$ of the remaining sides - and it is thereby an $(N-K+1)$-gon. By the induction hypothesis, their angle sums are $180^\circ(K-1)$ and $180^\circ(N-K-1)$. Adding, we find that the sum of all angles of a $N$-gon is $180^\circ(K-1)+180^\circ(N-K-1)=180^\circ(N-2)$. The theorem has been proven.

In hindsight, we can draw the following conclusion: for any cutting

⟦folio 54⟧

Fig. 2.

Euler's map theorem. Let B points be selected on the plane, and they are connected by P segments so that a polygon is formed, divided into M other polygons in the correct way (Fig. 2). Then B—P+M=1.

Proof. Let a large (external) polygon have n sides (and n vertices), and the number of sides of the M polygons into which it is cut is n1, n2, ..., nM. Of the B vertices of the map, n vertices lie on the boundary, and (B-n) lie inside the large polygon. Calculating the total sum of the angles of all M polygons in two ways, we obtain the equality $180^\circ(n_1-2)+...+180^\circ(n_M-2) = 180^\circ(n-2)+360^\circ(B-n)$,

where
$$n_1+n_2+...+n_M-2M=2B-n-2.$$

Let us now note that in the sum $n_1+n_2+...+n_M+n$ each of the P segments participates twice - it serves as the sides of two polygons (linear
<table><thead><tr><th></th><th>B</th><th>P</th><th>Γ</th></tr></thead><tbody><tr><td>Cube</td><td>8</td><td>12</td><td>6</td></tr><tr><td>Tetrahedron</td><td>4</td><td>6</td><td>4</td></tr><tr><td>5-gonal pyramid</td><td>6</td><td>10</td><td>6</td></tr><tr><td>Octahedron</td><td>6</td><td>12</td><td>8</td></tr><tr><td>Dodecahedron</td><td>20</td><td>30</td><td>12</td></tr></tbody></table>

Fig. 3.

Fig. 4.
