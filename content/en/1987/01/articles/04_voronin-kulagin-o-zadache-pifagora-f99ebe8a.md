---
id: 1987-1-voronin-kulagin-o-zadache-pifagora-f99ebe8a
issue: kvant_1987_1
year: 1987
number: "1"
title: About the Pythagorean problem
authors:
  - Воронин С. М.
  - Кулагин А. Г.
rubric: raznoe
page_first: 15
page_last: 16
page_labels: 13-14
tag: 48BZ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 39eb8870e99a3bbf2e72fa1c16fd7ade5c5581794ceb4eb0ce980d1168622670
prompt_sha256: draft-1
translated_from: content/ru/1987/01/articles/04_voronin-kulagin-o-zadache-pifagora-f99ebe8a.md
source_content_sha256: a0edeecbeba8694bac35d0edea42376d607b9e3fce324a2befd924acd0a20920
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 13⟧

looks like
$$y = k(x + 1),$$
where $k$ is the slope of the line.
Thus, the coordinates of the point $(x_2; y_2)$ will satisfy the system of equation
$$\begin{cases} x^2 + y^2 = 1, \\ y = k(x + 1). \end{cases}$$
Let us solve this system for $x$ and $y$. Substituting the value $y = k(x + 1)$ from the second equation into the first equation of the system, we obtain
$$x^2 + k^2(x + 1)^2 = 1,$$
or
$$(1 + k^2) \cdot x^2 + 2k^2 \cdot x + k^2 - 1 = 0.$$
If $x$ satisfies the last equation, then $x$ is the abscissa of the point of intersection of line $y = k(x + 1)$ with circle $K$, i.e. either $x = x_1 = -1$ or $x = x_2$. From Vieta's theorem it follows that
$$x_1 + x_2 = -\frac{2k^2}{1 + k^2},$$
where
$$x_2 = \frac{1 - k^2}{1 + k^2}.$$
Since the point $(x_2; y_2)$ lies on the line $y = k(x + 1)$,
$$y_2 = \frac{2k}{1 + k^2}.$$
The last two formulas correspond to each number $k$ with a dot
$$(x_2; y_2) = \left(\frac{1 - k^2}{1 + k^2}; \frac{2k}{1 + k^2}\right),$$
lying on the circle $x^2 + y^2 = 1$. Conversely, each point $(x; y) \neq (-1; 0)$ lying on the circle $K$ corresponds to one and only one value of the slope $k$:

$$k = \frac{y}{x + 1}.$$

Note here that if $k$ is a rational number, then the point $(x_2; y_2)$ is defined by formula (6) and has rational coordinates, and conversely, if $x_2$ and $y_2$ are rational, then by formula (7) $k$ is rational. Thus,

a one-to-one correspondence is established between points with rational coordinates of a circle of uniform radius (except for the point $(-1; 0)$) and rational points of the real line.

By forcing the quantities $k$ to run through all rational values ​​of the interval from $-\infty$ to $+\infty$, we will enumerate all points with rational coordinates on the circle $K$ of a single radius (except for the point $(-1; 0)$) and thereby find all primitive solutions to the Pythagorean problem.

Let us present the corresponding formulas. Let $k = p/q, q > 0$, GCD $(p, q) = 1$. Then from formula (6) it follows that

$$\left(x_2; y_2\right) = \left(\frac{q^2 - p^2}{q^2 + p^2}; \frac{2pq}{q^2 + p^2}\right).$$

We have essentially obtained formulas (*) again! To get the same result exactly, all you have to do is tinker a little with four.

In the case of different parities $p$ and $q$, formula (**) corresponds to the primitive Pythagorean triple $(a, b, c) = (q^2 - p^2, 2pq, q^2 + p^2)$. If $p$ and $q$ are both odd, then, passing to new variables $q_1 = (q + p)/2, p_1 = (q - p)/2$, GCD $(p, q) = 1$, we obtain $q^2 + p^2 = 2(q^2 + p^2), q^2 - p^2 = 4p_1q_1, 2pq = 2(q^2 - p^2)$. After reduction by 2 in (**) we get

$$\left(x_2; y_2\right) = \left(\frac{2q_1p_1}{q_1^2 + p_1^2}; \frac{q_1^2 - p_1^2}{q_1^2 + p_1^2}\right).$$

Note that formula (8) differs from formula (**) by the permutation of $x_2$ and $y_2$. If it turns out that $p_1$ and $q_1$ are both odd, then we move on to the variables $q_2 = (p_1 + q_1)/2, p_2 = (q_1 - q_1)/2$, GCD $(q_2, p_2) = 1$, etc. As a result, we obtain either a formula of type (**) or a formula of type (8), in which $p_1$ and $q_1$ have different parities, GCD $(p_2, q_2) = 1$. Thus, the primitive solution corresponding to the rational point $(x_2; y_2) \neq (-1; 0)$ is given either by a formula of type (**) or a formula of type (8), in which $p_1$ and $q_1$ are one-to-one correspondences between the primitive solutions of the Pythagorean equation and the rational points of the circle $x^2 + y^2 = 1$ (excluding the point $(-1; 0)$) from formula (**) and (8) follows assertion(*).

⟦folio 14⟧

Rational parameterization of finite sections

To find rational points lying on a circle with equation $x^2 + y^2 - 1 = 0$, we derived formula (6). It establishes a one-to-one correspondence between the parameter $k$, which takes all possible real values, and the points of the circle (except for the point $(-1; 0)$), and the coordinates $(x; y)$ of points lying on the circle are rational functions of $k$. The question arises: is it possible to similarly define points lying on other curves, say on an ellipse, parabola or hyperbola? (Ellipse, parabola and hyperbola are finite sections; hence the name of this section.)

To answer this question, consider a curve in the plane given by the equation $K(x, y) = 0$, where $K(x, y)$ is a quadratic polynomial in $x$ and $y$. Points lying on a parabola, ellipse and hyperbola satisfy this kind of correspondence. Let $(x_1; y_1)$ be some fixed point of such a curve. Let us draw a straight line through this point with an angular coefficient equal to $k$ (Fig. 3). We will look for points $(x; y)$ of intersection of a curve and a straight line. the $(x; y)$ coordinates of these points satisfy the system of equations
$$\begin{cases} K(x, y) = 0, \\ y - y_1 = k(x - x_1). \end{cases}$$

Solving this system for $(x; y)$ in the same way as we did earlier for the circle, we express the coordinates $(x_2; y_2)$ of the second intersection point

straight line $y = y_1 + k(x - x_1)$ with curve $K$ through parameter $k$. It is easy to check that you get an expression like
$$\left(x_2; y_2\right) = \left(\frac{A(k)}{C(k)}; \frac{B(k)}{C(k)}\right),$$
where $A(k), B(k), C(k)$ are polynomials of degree no higher than 2 in the parameter $k$. This formula specifies a rational parametrization of the curve $K$, i.e., it expresses the coordinates of a point on the curve through rational functions of one parameter $k$.

Formula (***), like formula (**), allows you to find whole points on the curve $K$. However, now we are interested in another - completely unexpected - application of this formula, to which we move on.

Application to the calculation of integrals

It turns out that such seemingly hopeless integrals as
$$I = \int \frac{dx}{\sqrt{x^2 + 3x - 4}},$$
are taken if we use rational parameterization suitable for the selected curve. Namely, if in this case we take the curve
$$K(x, y) = y^2 - (x^2 + 3x - 4),$$
notice that point $(x_1; y_1) = (-4; 0)$ lies on the curve
$$y(x) = \sqrt{x^2 + 3x - 4}$$
and consider all possible straight lines
$$y = k(x + 4),$$
then you get the following parameterization (do the calculations yourself!):
$$\left(x; y\right) = \left(\frac{1 + 4k^2}{1 - k^2}; \frac{5k}{1 - k^2}\right).$$

Then $dx = \frac{10k}{(1 - k^2)^2} dk$, and therefore (after reduction) we get
$$I = \int \frac{dx}{\sqrt{x^2 + 3x - 4}} = \int \frac{dx}{y(x)} = \int \frac{2dk}{1 - k^2}.$$

The last integral is easy to calculate:
$$\int \frac{2dk}{1 - k^2} = \int \frac{dk}{1 - k} + \int \frac{dk}{1 + k} = \ln |1 + k| - \ln |1 - k| + C = \ln \left| \frac{1 + k}{1 - k} \right| + C.$$
