---
id: 1986-8-bendukidze-kak-dekart-provodil-kasatelnyie-cc446952
issue: kvant_1986_8
year: 1986
number: "8"
title: How Descartes drew tangents
authors:
  - Бендукидзе А. Д.
rubric: osnovnye-stati
page_first: 7
page_last: 8
page_labels: 5-6
tag: LJEU
lang: en
source: kvant_digital
extraction: vision
content_sha256: aed249be82b5922dd8d200ffc402ec52176d0a8ef39e9943797c9aa73b1dacba
prompt_sha256: draft-1
translated_from: content/ru/1986/08/articles/05_bendukidze-kak-dekart-provodil-kasatelnyie-cc446952.md
source_content_sha256: d9764de63a5834e5eac15e3027ea76469d3a2f921c870c169e7774260f457f47
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 5⟧

How Descartes drew tangents

Candidate of Physical and Mathematical Sciences
A. D. VENDUKIDZE

The problem of drawing tangents is one of the most important problems in geometry. This problem was dealt with by the ancient Greeks, who managed to solve it successfully in some cases. In particular, they knew how to construct tangents to a circle, ellipse, hyperbola, parabola... But they did not have a general method, and in each individual case they had to act accordingly - to apply one or another property of the tangent drawn (for example, in the case of a circle they relied on the well-known fact that the tangent is perpendicular to the radius drawn to the point of tangency).

In 1637, one of the most famous books in the history of science was published - “Geometry” by Descartes. In it, the author, along with other important results of his research, also presents an extensive method for drawing tangents - the so-called normal method. (Historians have established that Descartes owned it as early as 1629.) The purpose of this article is to introduce the reader to this method.

Let's start with the concept of normal. A normal line at a given point is a straight line passing through this point perpendicular to the tangent. In particular (and this is important for the Descartes method), if the given line is a circle, then the normal is a straight line running along the radius that has an end point of tangency. It is clear that if we are given a normal, we can easily construct a tangent. This is exactly what Descartes does: he first constructs the normal, and only then the tangent (hence the name of his method). To construct the normal, Descartes uses the coordinate method he himself developed, which gives him the opportunity to solve a geometric problem algebraically. (This, by the way, once again emphasizes the unity of mathematics.)

To construct the normal at the point $P(x_0; y_0)$ to the algebraic curve $L$ given by the equation $F(x, y)=0$ (Descartes was interested in constructing the normal rather than deriving its equation), the intersection point $C(c; 0)$ of the normal with the abscissa axis is sought. If $CP$ is a normal, then a circle with center at point $C$ and radius $CP$ touches the given curve $L$ at point $P$ (Fig. 1); if the center of the circle is at least slightly shifted from $C$ to another point on the x-axis $C'$, then the circle of radius $C'P$ will meet the given curve $L$ in the vicinity of point $P$ at least in one more point. Thus, the desired circle must, with a given curve $L$, have two or more common points merged into one. The coordinates of the intersection points of the curve $F(x, y)=0$ and the circle $(x-c)^2+y^2=(x_0-c)^2+y_0^2$ are found by jointly solving their equation, for which one of the coordinates is eliminated. If the intersection points at $P$ coincide, the root $x=x_0$ (or $y=y_0$) of the resulting equation must be at least double, and this imposes a certain condition on the desired quantity $c$.

Of course, to a modern reader, Descartes' method may seem artificial and ineffective. First of all, the equation of the tangent to the analytical given curve $F(x, y)=0$ is automatically written abscissa using arbitrary ones (however, it is desirable to be able to differentiate a function given non-left). But even if you don’t know arbitrary ones (and Descartes didn’t know them), it is more convenient to construct a tangent line, bypassing intermediate constructions: instead of using the method described above to construct a circle tangent to a given curve, it is possible (and even easier) to immediately construct a straight line tangent to a given curve. For us, Descartes' method is primarily of historical interest; secondly, it is interesting to us (as well as to Descartes) because it allows us to obtain the method of coordinates.

Descartes explains his method using examples, including the example of an ellipse. Let's consider this example.

⟦folio 6⟧

Fig. 2.

Recall that an ellipse is a line obtained by compressing a circle to its diameter. In particular, if the circle $x^2+y^2=a^2$ is rolled towards the x-axis, the result is an ellipse

$$\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1. \quad (1)$$

Here $b=ta$, where $t$ is the scatia coefficient (Fig. 2).

So, given an ellipse (1), the point $P=(x_0; y_0)$ is on it, and we need to check the tangent to the ellipse at this point.

Take a circle with center at point $C=(c; 0)$ and passing through point $P$. Its equation is

$$(x-c)^2+y^2=(x_0-c)^2+y_0^2$$

(here $c$ is a currently unknown parameter), or

$$x^2+y^2-2cx-x_0^2-y_0^2+2cx_0=0. \quad (2)$$

The parameter $c$ should be selected so that the circle (2) has two merged intersection points (Fig. 3) ​​with the ellipse (1) at $P$. For this it is necessary and sufficient that the system of equations

$$\left\{ \begin{array}{l} b^2x^2+a^2y^2-a^2b^2=0, \\ x^2+y^2-2cx-x_0^2-y_0^2+2cx_0=0 \end{array} \right.$$

had the solution $(x_0; y_0)$ and $(x_0; -y_0)$. (Here we take into account symmetry about the x-axis - see Fig. 3.)

Eliminating $y^2$, we obtain a quadratic equation with respect to $x$

$$(a^2-b^2)x^2-2a^2cx-a^2(x_0^2+y_0^2-2cx_0-b^2)=0.$$

Since it must have a single root, its discriminant must be zero, that is

$$a^4c^2+a^2(a^2-b^2)(x_0^2+y_0^2-2cx_0-b^2)=0.$$

Since $P=(x_0; y_0)$ is a point of the ellipse, that is

$$b^2x_0^2+a^2y_0^2=a^2b^2,$$

after simple transformations we arrive at the equation

$$(a^2c-(a^2-b^2)x_0)^2=0,$$

whence $c=\frac{(a^2-b^2)x_0}{a^2}$; find the center of the desired circle.

The radius $CP$ of the found circle lies on the normal of the given ellipse, and remains through $P$ draw a periodicour to $CP$. This will be the desired tangent. Let's find its equation.

Suppose that $0<x_0<a$ and $PT$ are tangent segments. Then from right triangle $CPT$ (Fig. 4)

$$PQ^2=CQ \cdot QT,$$

and since

$$PQ=y_0,$$

$$CQ=OQ-OC=x_0-\frac{(a^2-b^2)x_0}{a^2}=\frac{b^2x_0}{a^2},$$

we get $QT=\frac{a^2y_0^2}{b^2x_0^2}$, so

$$OT=OQ+QT=x_0+\frac{a^2y_0^2}{b^2x_0^2}=\frac{a^2}{x_0}$$

(we are talking about $b^2x_0^2+a^2y_0^2=a^2b^2$ again).

Thus, we have found the point $T$ of intersection of the desired tangent with the abscissa axis: $T=(a^2/x_0; 0)$. (The result is also true in the case of $-a<x_0<0$, check this!)

Knowing two points of the tangent $P$ and $T$, it is already easy to write its equation

$$y-y_0=k(x-x_0),$$

where the slope $k$ is found from the condition

$$k=\frac{y_0-0}{x_0-\frac{a^2}{x_0}}=\frac{x_0y_0}{x_0^2-a^2}=-\frac{b^2x_0}{a^2y_0}$$

(we again took advantage of the fact that $(x_0; y_0)$ is a point of the ellipse, so $x_0^2-a^2=-\frac{a^2y_0^2}{b^2}$).

Thus, the equation of the desired tangent has the form

$$y-y_0=-\frac{b^2x_0}{a^2y_0}(x-x_0).$$
