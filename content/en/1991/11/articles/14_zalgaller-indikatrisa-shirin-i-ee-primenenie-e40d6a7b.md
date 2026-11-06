---
id: 1991-11-zalgaller-indikatrisa-shirin-i-ee-primenenie-e40d6a7b
issue: kvant_1991_11
year: 1991
number: "11"
title: Width indicatrix and its application
authors:
  - Залгаллер В. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 40
page_last: 41
page_labels: 38-39
lang: en
source: kvant_digital
extraction: vision
content_sha256: 175523189d2849f43c6c399797beccfbfc7ad00d8db8841af8a267f9ca0782b3
prompt_sha256: draft-1
translated_from: content/ru/1991/11/articles/14_zalgaller-indikatrisa-shirin-i-ee-primenenie-e40d6a7b.md
source_content_sha256: 5b8727eba3255adf4cb79a0ee81907f09cb15a77432f85228f2d93fbe07fe990
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 38⟧

---
running_head:
folio:
---

Indicatrix
width
and its application

Doctor of Physical and Mathematical Sciences
V. ZALGALLER

Let's start with the task

Task. In the square $70 \times 70$ there are measured without overlapping paths of figures: square $30 \times 30$, rectangles $25 \times 15$ and $20 \times 10$ and two circles with radii 5. Prove that there is a place to measure another circle with radius 5 without interfering with the existing figure.

Solution. The center of the new circle will represent itself in the square $Q$ of size $60 \times 60$ resulting from the square $70 \times 70$ after eliminating the edge border of width 5 (Fig. 1). In this case, the desired center must be at least 5 away from the already placed figures. We surround each of the heels of the figures with a border of width 5 (Fig. 2). The total area of ​​these "extended" figures is $2775 + 275 \pi < 3642$. It would seem that they could exhaust the $Q$ area. But if there is no place for an exclusive center, then, in particular, none of the vertices $Q$ is such a place, i.e., which of them is covered by one of the “extended” figures. Then although one of the vertices $Q$ is covered precisely by a circle of radius 10 (see Fig. 1).

Exercise 1. Prove that the area of ​​the part of the circle located outside $Q$ is not less than the area of ​​two 90-degree segments of this circle, i.e. not less than

$$\left( \pi - 2 \right) \frac{10^2}{2} > 57.$$

It remains to note that the area of ​​the part $Q$ covered by our figures is no more than $3642 - 57 < 3600$. So, "extended" figures cannot exhaust the area $Q$.

Generalization of the problem

Now the main thing. How would you approach the same problem if you were asked to prove that there is room for not only one, but two circles of radius 5?

We will propose a solution plan. In a square $70 \times 70$ there are 16 centers of possible circles, as indicated in figure 3. (These centers serve as nodes of a square lattice with a pitch of 20.) A simple physics experiment with paper templates of “extended” figures supports us,

⟦folio 39⟧

---
running_head:
folio:
---

that the square $40 \times 40$ (open, that is, without including a boundary) cannot simultaneously cover more than 5 nodes, open polygons $35 \times 25$ and $30 \times 20$ - respectively, no more than 4 and 3, and open circles with radii 10 - no more than one each. In total, with any placement of our extended figures, out of 16 excellent centers, we managed to cover no more than 14. So, two obviously remain uncovered. Therefore, it will be possible to add two circles to the placed figures, moreover, from the number of 16 circles indicated in advance.

Exercise 2. Carry out the experiments described above with the templates, cutting them out of paper.

To turn these “experimental” messages into rigorous proof, let us turn to new concepts.

Figure width

We will consider only closed (containing their boundary points) bounded figures F. For example, segments, triangles, rectangles. Let's give three definitions.

1. The width of the figure Ф in the direction $\vec{u}$ is called the minimum width of a closed (i.e., including its own circle) strip, directed forward-

pendicular to $\vec{u}$ and containing the figures F.

2. The width of the figure Ф is simply called the smallest of the widths Ф in different directions.

3. If from an arbitrarily fixed point Q in each direction $\vec{u}$ we plot a segment whose length is equal to the width of the figure Ф in the direction $\vec{u}$, then these segments (we call them “radii” of the “indicatrice”) fill the figure, which is called the indicatrix of the widths of the figure Ф.

Exercise 3. Find the width of a square with radius 1.

4. Prove that the width of a triangle is equal to the smallest of its heights.

5. Make sure that for a segment of length $d$ the indicatrix of widths looks like two tangent circles at point $O$, each with a diameter of $d$ (Fig. 4).

6. Prove that the indicatrix of the widths of a rectangle coincides with the union of the indicatrixes of its two diagonals. (On figure 5 the indicatrix of the widths of the rectangle $40 \times 20$ is shown. The dotted line indicates a circle with a radius of 40 and the angle within which the “radii” of the indicatrix is ​​shorter than 40 is highlighted.)

7. Prove that the indicatrix of the widths of a triangle coincides with the union of the indicatrixes of its three sides. (On figure 6 the indicatrix of the widths of an equilateral triangle $T_1$ with a base of 40 and a height of 40 is depicted, and on figure 7 - an isosceles triangle $T_2$ with a base $2\sqrt{2}$ and lateral sides $2\sqrt{5}$. As on figure 5 the circle of radius is indicated with a dotted line 40 and the angle within which the “radii” are shorter than 40 is highlighted.)

Given the above definitions of estin, the following statement is true.

In order for a closed bounded figure Φ to be covered with an open (not containing its edges) positions of width $h$, it is necessary and sufficient that the width Φ be less than $h$.

That a closed bounded figure Ф could be covered with an open (not containing its own contour) square from the side $a$, not
