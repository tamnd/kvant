---
id: 1978-9-vavilov-setchatyie-nomogrammyi-6602a881
issue: kvant_1978_9
year: 1978
number: "9"
title: Grid nomograms
authors:
  - Вавилов В. В.
rubric: raznoe
rubric_sub: Разное
page_first: 24
page_last: 30
page_labels: 22-28
tag: 28QK
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8eea4d04841e19ddf9a738d30de88eb73d35b3ca401034c055f34553e44b9603
prompt_sha256: draft-1
translated_from: content/ru/1978/09/articles/07_vavilov-setchatyie-nomogrammyi-6602a881.md
source_content_sha256: b5e75f9ab24998274e3562d0d9edd4ec313b2b27b5160dbce090cdd885a19a20
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 22⟧

Grid nomographs

V. Vavilov.

Grid nomographs

In this lesson you will be given several tasks. The experimental part (execution of drawings) is available to everyone, and the justification requires knowledge of the arbitrary. Our advice is to teach from drawing work, and then work on proofs.

Note that the nomographs shown in the figures cannot be used effectively enough in practice (due to printing difficulties they are too small and not accurate).

Mathematicians are like the French: everything you say to them, they translate into their language, and it immediately becomes something completely different.

N. V. Goethe

1. Square trinomials and the phase plane

Consider the family of square trinomials $\{x^2+px+q\}$ (p and q are real numbers). On some plane π—we call it the phase plane—we associate the square trinomial $x^2+px+q$ with a point with coordinates p and q. For example, the trinomial $x^2+x+1$ corresponds to the point (1; 1), and the point (0; 0) corresponds to the trinomial $x^2$.

Let's find out which points of the phase plane correspond to trinomials that have the same roots. To do this, we equate the discriminant of the trinomial to zero; we get the equality

$$q = \frac{1}{4} p^2.$$

Equality (1) defines the so-called discriminant point of the parabola (Fig. 1) in the π plane; this parabola consists of points corresponding to trinomials of the form $(x-x_0)^2 = x^2-2x_0x+x_0^2$.

The inequality $q > \frac{1}{4} p^2$ defines a region in the π plane that lies “inside” the parabola (blue region on figure 1). The points in this region correspond to trinomials that do not have real roots. Square trinomials having two different real roots correspond to points whose coordinates satisfy the $q < \frac{1}{4} p^2$ correspondence. This is the pink area at figure1.

Consider the straight line on the plane π

$$ap+q+a^2=0$$

(2) (here p, q are variables, a is a fixed number). It is easy to say that points lying on line (2) correspond to trinomials having root a. Line (2) is called the root line. (Of course, there are many root lines; each potential root a has its own line.)

How is the root line located in relation to the discriminant parabola? It is clear that they touch each other. Indeed, the root line does not intersect the blue region and has one common point with the boundary of this region, namely the point corresponding to the trinomial $(x-a)^2 = x^2-2ax+a^2$. This conclusion can be easily verified by an undefined solution of the system

$$\begin{cases} q = \frac{1}{4} p^2, \\ ap+q+a^2=0. \end{cases}$$

Since the point $(-2a; a^2)$ belongs to both the line (2) and the parabola (1), the line (2) and the parabola (1) touch each other at this point.

Carrying out the reasoning in reverse order, we can prove that every line tangent to the discriminant parabola is a root line (prove it yourself!).

So, through each point of the discriminant parabola passes

⟦folio 23⟧

Fig. 1.

exactly one root line (tangent to the parabola). Not a single root line passes through the points of the blue region. This is consistent with the fact that from the “inside” of a parabola it is impossible to check a single tangent to it. Finally, since each point in the pink region corresponds to an equation that has two different real roots, two different root lines can be tested through each point. This is also consistent with the fact that through a point lying in the “exterior” of the parabolas, one can check to neurally two tangents.

The one-to-one correspondence between points of the plane and quadratic equations allows one to find a description of all equations with a given property of roots, indicating the corresponding set of points of the phase plane.

For example, let us describe all such points of the plane π that correspond to the quadratic equation $x^2+px+q=0$ with two different roots belonging to the integral ]—2; 1[.

It is easy to say that the quadratic equation $x^2+px+q=0$ may or may not have different real roots, belong to a given integral, when the triline $x^2+px+q$ has a positive discripant, at the ends of the integral takes positive values ​​and the abscissa of the vertex

paraboles $y=x^2+px+q$ belongs to the given integral.

For the one we are interested in, Lemma ]—2; 1[ thus obtaining the system:

$$\begin{cases} q < \frac{1}{4} p^2, \\ 4 - 2p + q > 0, \\ 1 + p + q > 0, \\ -2 < -\frac{p}{2} < 1. \end{cases}$$

On the plane π, system (3) defines a set of points colored pink on figure 2. Thus, square triplets having different real roots belong to the integral ]—2; 1[, corresponds to the interior points of this curved triangle.

The root lines $-2p+q+4=0$ and $p+q+1=0$ (corresponding to the root ]—2 and 1) divide the exterior of the discripant into six regions: $\alpha_1, \alpha_2, \beta_1, \beta_2, \gamma$ and $\delta$ (Fig. 2). The number of roots of the equation $x^2+px+q=0$ that fall into the integral ]—2; 1[, depends on which of the listed areas of the plane π contains the point $(p; q)$ corresponding to this equation. This dependence is reflected in the table shown at figure 2 (check it!).

Task 1

1. a) Find the set of all points $(p; q) \in \pi$ for which the equation $x^2+px+q=0$ has two real roots $x_1, x_2$, $a < x_1 < b$, $c < x_2 < d$ and $a < b \leqslant c < d$.

6) Make a table with the help of which, based on the position of the point $(p; q)$ on the plane π, one could answer the question of how many roots of the equation $x^2+px+q=0$ fall into the integrals $|a, b|$ $|c, d|$ (for given $a, b, c$ and $d$).

Consider, for example, the case when $a=-3$, $b=0$, $c=1$, $d=3$.

The next task is for independent research.

2. Consider on the interval $[0; \pi]$ the family of functions $\{\cos^2x+p \cos x+q\}$. As before, each function

⟦folio 24⟧

Fig. 2.

of this family we put in correspondence the point $(p; q) \in \pi$.

a) Examine the function $\cos^2 x + p \cos x + q$ for increasing and decreasing depending on the position of the point $(p; q)$ on the plane $\pi$.

6) Let $M_0 = (p_0; q_0)$ be a fixed point of the plane $\pi$, $M = (p; q)$ be a variable point; $f_0(x) = \cos^2 x + p_0 \cos x + q_0$, $f(x) = \cos^2 x + p \cos x + q$. For given points $M$ and $M_0$ we set

$$d(M, M_0) = \max_{[0; \pi]} |f(x) - f_0(x)|.$$

Let us find the set of the point $M = (p; q) \in \pi$ maximizing that

1) $d(M, M_0) = 1$;
2) $d(M, (2; 2)) = d(M, (-2; -2))$.

2. Nomograph for solving the equation $x^2 + px + q = 0$

Let us draw quite a lot of root straight lines $ap + q + a^2 = 0$ on the phase plane $\pi$, giving the parameter $a$, for example, the value 0; ±0.5; ±1; ±1.5; ±2; ±2.5; ±3; ±3.5.

Next to each drawn line we write the corresponding value $a$ (Fig. 3). The resulting “network” of straight lines is called a semiatom number (for solving quadratic equations).

In order to find the roots of a given equation $x^2 + px + q = 0$ using the constructed nomogram, it is necessary to establish which root lines pass through the corresponding point $(p; q) \in \pi$.

Let us solve, for example, the equation $x^2 + 0,5x - 3 = 0$. Through the point $(0,5; -3)$ there are root lines using $a = -2$ and $a = 1,5$; therefore, the numbers $-2$ and $1,5$ are the roots of our equation.

Let us now consider the equation $x^2 + x - 3 = 0$. It corresponds to the point $(1; -3)$ on the phase plane. The root lines passing through this point are not plotted on our nomogram. In this case, we will do this. Note that the point $(1; -3)$ lies inside the quadrilateral $ABCD$ formed by the root lines at $a = -2,5$; $a = -2$; $a = 1$ and $a = 1,5$ (Fig. 3).

⟦folio 25⟧

A point of this quadrilateral corresponds to an equation with two real roots, one of which falls in the interval ]1; 1.5[, and the other - in the interval ]-2.5; -2[. Consequently, the roots of the equation $x^2+x-3=0$ also lie in the indicated intervals. Taking their midpoints, we obtain approximate values ​​of the original roots:

$$x_1 \approx \frac{1,5+1}{2} = 1,25,$$

$$x_2 \approx \frac{-2-2,5}{2} = -2,25.$$

Substituting these values ​​$x_1$ and $x_2$ into this equation, we get:

$$(1,25)^2 + 1,25 - 3 = -0,1875,$$

$$(-2,25)^2 - 2,25 - 3 = -0,1875$$

the result is quite rough. In order to obtain more accurate values ​​of the roots using a nomogram, it is necessary, obviously, to increase the number of root lines on it, i.e., to increase the frequency of changes in the parameter $a$.

To approximately solve an equation with coinciding roots, it is convenient to program the discriminant paraboly $q = \frac{1}{4} p^2$. An equation with roots $x_1=x_2=a$ corresponds to a point $(-2a; a^2)$ on it. Giving the parameter $a$ different values ​​and marking the points $(-2a; a^2)$ discriminatory parabolic with these values, we obtain on it a scale for solving the equation with coinciding roots (Fig. 3).

Task 2

Draw a seven-dimensional nomogram on graph paper to solve the equation $x^2+px+q=0$.

3. Nomogram for solving the equation $x^3+px+q=0$

Let us now consider the family of cubic x trinomials $\{x^3+px+q\}$. Let us assign to each trinomial a point $(p; q)$ on the phase plane n.

Let us find out which points of the phase plane correspond to cubic trinomials that have coinciding roots.

Fig. 3.

⟦folio 26⟧

Let $a$ be the multiple root of the cubic trinomial $x^3+px+q$, i.e. $x^3+px+q=(x-a)^2(x-b)$, where $b$ is not necessarily different from $a$. Opening the brackets, we get the identity
$$x^3+px+q=x^3-
-(2a+b)x^2+(a^2+2ab)x-
-a^2b.$$
Hence $2a+b=0, a^2+2ab=p, a^2b=-q$. Eliminating $b$ from these equations, we obtain $p=-3a^2, q=2a^3$; finally, eliminating $a$, we obtain the desired correspondence
$$\left(\frac{p}{3}\right)^3+\left(\frac{q}{2}\right)^2=0,$$
(4)

It is a necessary and sufficient condition for the coincidence of at least two roots of the trinomial $x^3+px+q$. The set of points $(p; q) \in \pi$ whose coordinates satisfy equation (4) is the curve depicted in figure 4. Curve (4) is called the discriminant curve of equation $x^3+px+q=0$.

Straight
$$ap+q+a^3=0,$$
(5)

corresponds to the equation of trinomials having the root $a$, as before, called the root.

What is the relative position of the curve (4) and straight line (5) on the phase plane $x?$ Do they have intersection points, and, if so, how many?

To answer these questions, note that since there is no term with $x^2$ in the equations $x^3+px+q=0$, the sum of its roots $x_1, x_2$ and $x_3$ is zero: $x_1+x_2+x_3=0$ (prove this). The intersection point $(p; q)$ of curve (4) with straight line (5) corresponds to the cubic trinomial $x^3+px+q$, which $a$ either has a multiple root or does not. In the first case, $x_1=x_2=a$ and $x_3=-2a$. In the second case, $x_1=a$ and $x_2=x_3=-\frac{a}{2}$. This means that curve (4) and straight line (5) have two common points $(p_1; q_1)$ and $(p_2; q_2)$: one of them corresponds to the trinomial $x^3+p_1x+q_1=(x-a)^2 \times (x+2a)$, the other to the trinomial $x^3+p_2x+q_2=\left(x+\frac{a}{2}\right)^2(x-a)$. These two points coincide if and only if $a=0$.

Fig. 4.

Fig. 5.

Let us now find the intersection points of straight line (5) and curve (4) purely algebraically. To do this, from (5) we express $q$ in terms of $p$ and substitute it into (4). We have obtained the cubic equation to determine $p$
$$\left(\frac{p}{3}\right)^3+\left(\frac{a^3+pa}{2}\right)^2=0.$$

It is easy to verify that
$$\left(\frac{p}{3}\right)^3+\left(\frac{a^3+pa}{2}\right)^2=
\frac{1}{27}(p+3a^2)^2\left(p+\frac{3a^2}{4}\right).$$

It follows that the numbers $p_1=-3a^2$ and $p_2=-\frac{3a^2}{4}$ are the roots of equation (6), and $p_1$ is a multiple root.

The multiple root of equation (6) corresponds to the “coincidence” of the intersection point of curve (4) and straight line (5). At this “double” intersection point, the root straight line touches the discriminant curve (unfortunately, we cannot provide a proof of this statement here; the intuitive idea of ​​the proof is clear from figure 5).

⟦folio 27⟧

Fig. 6.

Carrying out all the reasoning in reverse order, we obtain that every tangent to the discriminant of the curve is a root line.

Having drawn quite a lot of root lines (5) on the plane l, we obtain a grid nomogram for solving cubic equations $x^3+px+q=0$. Such a nomogram is shown in figure 6.

The number of roots of a particular equation $x^3+px+q=0$ depends on how many tangents can be drawn from point $(p; q) \in \pi$ to the discriminant curve (4) (each tangent is a root line, and each root line has its own root value).

The discriminant curve divides the plane l into two parts: internal (containing the negative semi-axis of change $p$) and external.

Since the discriminant curve consists of two symmetrical convex arcs $^*$), then through any point of the external region only one tangent to it can be drawn (Fig. 7, a): if the point $(p; q)$ lies above the axis $Op$, then to the lower arc, and if below the axis $Op$, then to the upper one; the axis $Op$ itself touches the curve (4) at its singular point (0; 0). Thus, the points of the outer region correspond to those cubic equations that have only one (real) root. In this area

$$\left(\frac{p}{3}\right)^3 + \left(\frac{q}{2}\right)^2 > 0. \tag{7}$$

Inequality (7) is a necessary and sufficient condition for the equation $x^3+px+q=0$ to have exactly one real root.

At any point in the interior region the opposite inequality holds

$$\left(\frac{p}{3}\right)^3 + \left(\frac{q}{2}\right)^2 < 0. \tag{8}$$

On the other hand, from any point in the internal region, three different tangents to curve (4) can be drawn (Fig. 7, b). Indeed, for

⟦folio 28⟧

points located on the $Op$ axis, this follows from the symmetry of the curve (Fig. 7, $\theta$); the number of tangents cannot change if we move to other points without intersecting the curve. Thus, inequality (8) is a necessary and sufficient condition for the equation $x^3+px+q=0$ to have three different real roots.

If the point $(p; q)$ lies on the upper arc of the curve (4), then through it you can check the tangent to the curve at this point itself and, in addition, the tangent to the lower arc (Fig. 7, $\varepsilon$). Likewise for the point of the lower arc. Therefore, in the case of $\left(\frac{p}{3}\right)^3+\left(\frac{q}{2}\right)^2=0$ ($p \neq 0, q \neq 0$), the equation $x^3+px+q=0$ has one root of multiplicity 2 and one root of multiplicity 1.

Point $(0; 0)$ is an exceptional case; it is answered by equation $x^3=0$ with the third coincidence of roots.

Task 3

1. Let us draw a seed nomogram on graph paper to solve the equation $x^3+px+q=0$.

2. Find the set of all points $(p; q) \in \pi$ for which the equation $x^3+px+q=0$ has three different real roots belonging to the given integral $la; b[$. Make a table with the help of which, based on the position of the point $(p; q)$ on the plane $π$, it would be possible to determine how many roots of the equation $x^3+px+q=0$ fall into the given integral $la; b[$.

Consider, for example, the case when $a=-2, b=4$.

As a task for independent research, we propose to construct (and justify) mesh nomograms to solve the following degree:

a) $x^4+px+q=0$,
b) $x^4+x^2+px+q=0$,
b) $x^4-x^2+px+q=0$.

Books will help you do this:

1. A. N. Kolmogorov and others. Summer school on Lake Rubskoye (M., “Prosveshchenie”, 1971).
2. F. Klein. Elementary mathematics from the point of view of calculation (M. - Leningrad, Gostekhtoridat, 1933).

Application

(for readers who know what complex numbers are).

Here we will consider quadratic equations $x^2+px+q=0$ with real $p$ and $q$ and a negative discriminant, i.e. equations for which $q > \frac{1}{4} p^2$ (these equations on the phase plane $π$ correspond to the “interior” of the discriminant parabola). Such equations have two conjugate roots: $a+bi$ and $a-bi$. By Vieta's theorem

$$\begin{cases} 2a = -p, \\ a^2+b^2 = q, \end{cases}$$

where

$$q = \frac{p^2}{4} + b^2.$$

Let us find all points $(p; q) \in \pi$ corresponding to an equation with complex roots of the form $a+ni$ ($n \in Z$).

From correspondence (10) it follows that equations with roots of this type correspond to points of the plane $π$ lying on the parabolas

$$q = \frac{p^2}{4} + 1, q = \frac{p^2}{4} + 4, q = \frac{p^2}{4} + 9, \dots$$

(Fig.8); these parabolas turn out to be parallel
