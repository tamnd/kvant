---
id: 1983-10-pryamyie-na-krivoy-poverhnosti-77a3a2ea
issue: kvant_1983_10
year: 1983
number: "10"
title: Straight lines on a curved surface
rubric: raznoe
rubric_sub: Разное
page_first: 28
page_last: 29
page_labels: 26-27
tag: HDME
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7445e1f0ed7c45cf46ee63f385c905e00ebeeb3988126769465c66e53c1e62d8
prompt_sha256: draft-1
translated_from: content/ru/1983/10/articles/08_pryamyie-na-krivoy-poverhnosti-77a3a2ea.md
source_content_sha256: 418540d3abe6876ae2376d56a4b1de769c870f7f8e83f5cc34dadde9893b390a
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 26⟧

Straight on a curved surface

The fact that straight lines can fit entirely on a strongly curved surface will not surprise the reader who examined the cover of the previous issue «Kvant». We will refer to this phenomenon more than once in our geometric pages; today we will talk about surfaces on which there are especially many of these straight lines.

A surface is called ruled if a straight line contained in it passes through each of its points; straight lines lying on a ruled surface are called its rectilinear generators. A surface is called doubly ruled if at least two different rectilinear generators pass through each of its points.

The simplest example of a non-planar doubly ruled surface is a “single-sheet rotation hyperbolide”. This is a surface that, when rotated, receives hyperbolas around an axis of symmetry (Fig. 1) that does not intersect it. In the OXYZ coordinate system with the origin at the center of the hyperbola and with the OZ axis passing along the axis of rotation, the equation of our surface has the form

$$x^2 + y^2 = a^2z^2 + b^2,$$

(1)

where $a$ and $b$ are the lengths of the segments offset by figure 1. We are not deriving this equation, and we will not be able to fix it. The only important thing is that our surface is given by a polynomial of the second degree in $x, y, z$, that is, our hyperbolide is, as they say, a surface of the second order: if a straight line has at least three common points with a hyperbola, then it is contained in it.

Proof. Let $l$ be any line and $A_1(x_1,y_1,z_1)$, $A_2(x_2,y_2,z_2)$ any two of its points. The vector $\overrightarrow{A_1A_2}$ has coordinates $(x_2-x_1; y_2-y_1; z_2-z_1)$. Let $A$ be an arbitrary point of the line $l$. Then the vector $\overrightarrow{A_1A}$ count

linear $\overrightarrow{A_1A_2}$; this means that it has coordinates $(\lambda(x_2-x_1); \lambda(y_2-y_1); \lambda(z_2-z_1))$, where $\lambda$ is some number. This means that the point $A$, in turn, has coordinates $(x_1+\lambda(x_2-x_1); y_1+\lambda(y_2-y_1); z_1+\lambda(z_2-z_1))$. For the point $A$ to lie on our surface, it is necessary that its coordinates satisfy the surface equation. Substituting these coordinates into equation (1) and rearranging all terms to the left side, we obtain a relative equation $\lambda$ of the form $\alpha\lambda^2 + \beta\lambda + \gamma=0$, where the coefficients $\alpha, \beta, \gamma$ are easy to calculate (they depend on $u$, $x_1, x_2, y_1, y_2, z_1, z_2$), but we do not need their explicit expression. If at least one of these coefficients $\alpha, \beta, \gamma$ is not equal to zero, the last equation has no more than two solutions, that is, the straight line has no more than two points in common with the surface, which is impossible according to the conditions. This means $\alpha=\beta=\gamma=0$, and for any $l$ the point $A$ lies on the surface.

By the way, it is proved in exactly the same way that a second-order curve (that is, a curve on the plane defined by a second-degree polynomial in the unknowns $x, y$) intersects a straight line (not contained in it) at most two points. (In school notebooks you sometimes want to see careless figure hyperboles of this kind:

The red straight line intersects this hyperbola at 4 points, which is impossible: after all, a hyperbola is a second-order curve!)

⟦folio 27⟧

Let's return to our hyperbole. Let's take the point $A$ on the throat circle (that is, on the line of intersection of the hyperbolide with the plane $XOY$), draw the tangent $t_1$ to this circle and the tangent $t_2$ to the corresponding position of the rotated hyperbola, and then draw the plane through the straight lines $t_1$ and $t_2$ $T$. Note that the circle and hyperbola that touch the lines $t_1$ and $t_2$ lie on opposite sides of the plane $T$. Therefore, in any of the four quadrants into which the lines $t_1$ and $t_2$ divide the plane $T$, there is a common point of the hyperbolide and the plane. Let $B$ be one of these points (Fig. 2). Since, obviously, our hyperbolide is symmetric with respect to the plane drawn through $t_1$ and $t_2$ perpendicular to $T$, its intersection with $T$ is symmetric with respect to $t_1$ and $t_2$ and together with the point $B$ it belongs to the points $B_1, B_2$ and $B_3$, forming with $B$ a rectangle with center $A$. Each of the diagonals $l_1, l_2$ of this rectangle has three common points with the hyperbolide ($B, A, B_2$ and $B_1, A, B_3$, respectively). This means, according to what was proven above, each of them is contained in our hyperbolide. It remains to note that this reasoning is applicable to any point $A$ of the throat circle. Straight $l_1$ and separately straight $l_2$ will notice the entire hyperbole. Thus, a one-sheet hyperbolide of revolution is a doubly linear surface.

In conclusion, two comments. The first correspondence is that a one-sheet hyperbolide of revolution is also a surface of revolution of one straight line around each other, if not parallel (prove it!). From this it can be seen that constructing a hyperbolide is easier than drawing a hyperbolide: it is enough to tie two identical hoops with threads, as shown in figure, and rotate one hoop relative to the other, keeping all the threads taut (Fig. 3). By replacing the hoops with cardboard circles mounted on a common axis, you can build such a model for a school math classroom. A quick-witted question: is it possible to make a hyperbolide with two identical hoops?

Second note. It consists in the fact that there are few doubly linear surfaces. If we extend a hyperbolide to any plane, then it will, of course, retain its twofold linearity; the resulting surface is called a one-sheet hyperbolide (not “rotation”, but simply). Another example of a second-order linear surface is a hyperbolic paraboloid. This surface will be obtained if at each point a parabola, the axis of which is vertical and directed upward, is suspended by the vertex of a parabola perpendicular to it (see figure at the beginning of the “page”); suspended parabolas are all the same; the suspended parabola may have different dimensions). A hyperbolic paraboloid is also a second-order surface; in a suitable coordinate system it has the equation $z=xy$. There were no other connected (that is, consisting of one piece) doubly linear surfaces.

Assignment for the next lesson of the geometric page.

A torus (the surface of rotation of a circle around an axis that does not intersect it and lies in the same plane with it) is produced by parallel lines, which then intersect the plane (“screen”). We will consider only those lines that touch the torus. We mark the points of contact with it with a pencil, the points of intersection of our straight lines with the screen - in red. A merger appears on the torus, red appears on the screen. Try drawing them. (A particularly interesting result will be obtained if the angle of inclination of the straight lines to the plane of the axial circle of the torus is non-verlik - less than 45° - and if the distance from the axis of rotation to the rotated circle does not exceed the radius of the circle.)
