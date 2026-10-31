---
id: 1972-7-brzhozovskiy-uravneniya-ornamentov-ed417a03
issue: kvant_1972_7
year: 1972
number: "7"
title: Ornament equations
authors:
  - Бржозовский М. И.
rubric: osnovnye-stati
page_first: 16
page_last: 20
page_labels: 14, 16, 18
tag: 6QCT
lang: en
source: kvant_digital
extraction: vision
content_sha256: 23c43d3c7096d522c6af7588fb5d9b6378252a68ab3fdf7e521187e85636b4e3
prompt_sha256: draft-1
translated_from: content/ru/1972/07/articles/06_brzhozovskiy-uravneniya-ornamentov-ed417a03.md
source_content_sha256: dc0048aed7d81355b9d8b00a490b83d86e40b70d221a1f567da671b62d58bab2
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

ORNAMENT EQUATIONS
M.I.Brzhozovsky

By choosing the equations properly, you can get a wide variety of, sometimes very bizarre, pictures. For example, you can get the "rozicia" shown at figure A. How to do this? First, we will have to remember that the number plane is called the set of all pairs of real numbers (see the article by A. N. Kolmogorov “What is the graph of a function”, «Kvant» No. 2, 1970). Any set of points in the number plane of the condition is called a geometric figure described by the equation $f(x, y)=0$.

In particular, we can consider the set of all pairs of real numbers $(x, y)$ for which $f(x, y)=0$, where $f(x, y)$ is a given expression. In this case, the resulting geometric figure is said to be described by the equation $f(x, y)=0$.

Thus, the equation $x^2-y=0$ describes a parabolic; equation $x^2-y^2=0$ - two lines ($y=x$ and $y=-x$) intersecting at point $(0, 0)$; equation $x^2+y^2=2$ is a circle with center at point $(0, 0)$ and radius $\sqrt{2}$; equation $|x|+|y|=1$ is a square with center at point $(0, 0)$ and vertices lying on the coordinate axes.

Now consider the following equations:

$$\left(x+y\mathrm{ctg}\frac{\pi n}{32}\right)\sqrt{\frac{x^2}{25}+\frac{y^2}{49}-1} = 0$$

(1)

Fig. A.
Fig. B.
Fig. V.

⟦folio 16⟧

Fig. 1). The equation of the circle $F_1$ in the same coordinate system is written in the form

$$ (x - 2)^2 + y^2 = 1. $$

Similarly, we can obtain the circle integer $F_{-1}, F_2, F_{-2}, \dots, F_k, F_{-k}, \dots$. They form a linear ornament.

This entire integer circle can be described by one equation if the distance of the function $[x]$ is the integer part $x^*$).

Here's the equation:

$$ (x - 2 \left[ \frac{x + 1}{2} \right])^2 + y^2 = 1. $$

If $x$ is in the interval $[2k - 1, 2k + 1)$, then this equation, as can be easily verified, defines one of the circles:

$$ (x - 2k)^2 + y^2 = 1. $$

In general, if $f(x, y) = 0$ (at $a \leqslant x < a + T$) is the equation of some geometric function, which we call the main function $F_0$, then the linear ornament obtained from $F_0$ by translations of $kT$ units along the $Ox$ axis (where $T > 0$, $k = 0, \pm 1, \pm 2, \dots$) is described by the equation

$$ f \left( x - T \left[ \frac{x - a}{T} \right], y \right) = 0. $$

Now let the main function $F_0$ defined in the strip $(b \leqslant y < b + S)$ be transferred (diagonally) to $kT$ units along the $Ox$ axis and to $kS$ units along the $Oy$ axis. then we obtain a linear ornament with links from the function $F_i$, located along the segment connecting the origin of coordinates $(0, 0)$ with the point $(T, S)$, and the equation

$$ * ) \text{ Функция } [x], \text{ называемая «целой часть } x», \text{ определяется равенством } [x] = k, \text{ если } k \leqslant x < k + 1, \text{ где } k - \text{ целое число (наибольшее целое число, не превысходящое } x). $$

Fig. 2.

this ornament will be

$$ f \left( x - T \left[ \frac{y - b}{S} \right], y - S \left[ \frac{y - b}{S} \right] \right) = 0 \quad (7) $$

(at $S \neq 0$). With $T = 0$, a linear ornament is obtained, located along the axis $Oy$. A combination of transitions (6) and (7) yields equations for two-dimensional ornaments.

It is interesting to note that if the function $y = f(x)$ is defined in the interval $a \leqslant x < a + T$, then the function

$$ y = f \left( x - T \left[ \frac{x - a}{T} \right] \right) $$

is defined on the entire real axis $-\infty < x < \infty$, is periodic with period $T$ and coincides with $f(x)$ in the interval $a \leqslant x < a + T$.

The function $f \left( x - T \left[ \frac{x - a}{T} \right] \right)$ is called the periodic continuation of the function $f(x)$. For example, if $y = |x|$ is in the interval $(-1, 1)$, then

$$ y = |x - 2 \left[ \frac{x + 1}{2} \right] | $$

is a periodic function with period $T = 2$, its graph is shown on figure 2.

figure 3 depicts a linear ornament composed of arcs of circles of radius $R = 1$. The basis of this ornament is the function $F_0$ (red part figure 3), given by the equation

$$ \left( x - \left[ \frac{x + 1}{2} \right] \right)^2 + \left( y - \left[ \frac{y + 1}{2} \right] \right)^2 = 1. $$

⟦folio 18⟧

Fig. 7. Fig. 8. Fig. 9.

$F_0$ is the set of all interior points of a hexagon with center at the origin, inscribed in a circle of radius $R = \frac{2}{\sqrt{3}}$ (Fig. 7).

The equation of this hexagon can be written as

$$\left| y \right| + \left| \frac{x \sqrt{3} - 1}{2} \right| + \left| \frac{x \sqrt{3} + 1}{2} \right| = 1,$$

since for these and only these points the inequalities are satisfied

$$1 \leqslant | y | + \left| \frac{x \sqrt{3} - 1}{2} \right| + \left| \frac{x \sqrt{3} + 1}{2} \right| < 2.$$

To get the blue part of the parquet, you can first make a series of translations over $F_0$ along the $Ox$ axis (at $T_1 = 2\sqrt{3}, a = -\frac{2}{\sqrt{3}}$), and then move a strip of figures $F_i$ (on the $Ox$ axis) diagonally (at $T_2 = \sqrt{3}, S = 3, b = -1$). The equation of the red part of the parquet is obtained from the constructed equation by replacing $y$ with $y - 2$, and the yellow part by replacing $y$ with $y + 2$.

Interesting circular patterns are obtained if you use polar coordinates.

In the polar coordinate system, each point $A$ has two coordinates (Fig. 8): the distance $\rho$ from this point to the origin $O$ and the angle $\varphi$, which forms the ray $OA$ with a fixed axis (at figure 8 - with

axis $Ox$); this angle is measured in the positive direction (counterclockwise) from the $Ox$ axis. The "origin" (point $O$) has coordinates $\rho = 0$ and any angle $\varphi$; any other point has a uniquely defined positive coordinate $\rho$ and a coordinate $\varphi$ defined from the point to multiples of $2\pi$.

In the polar coordinate system, as in the Cartesian one, figures can be described by equations. For example, the equation of a circle $F_0$ on figure 1 will be $\rho = 1$ (as we see, it is much simpler than an equation in the Cartesian coordinate system).

If $f(\rho, \varphi) = 0$ is the equation of the main figure contained in the sector $0 \leqslant \varphi < \frac{2\pi}{n}$, then, by analogy with formula (6), the equation

$$f(\rho, \varphi - \frac{2\pi}{n} \cdot \left[ \frac{n\varphi}{2\pi} \right]) = 0$$

specifies a circular pattern composed of figures $F_i$.

For example, one can write the equation of a regular $n$-gon inscribed in a circle of radius $R$. The equation $\rho \cdot \cos \left( \varphi - \frac{\pi}{n} \right) = R \cos \frac{\pi}{n}$ inside the sector $0 \leqslant \varphi \leqslant \frac{2\pi}{n}$ defines the side $AB$ (Fig. 9), and after a series of rotations of the segment $AB$ by angles divisible by $\frac{2\pi}{n}$, the weight $n$-gon is obtained.

Its equation according to formula (8) can be written in the form

$$\rho \cdot \cos \left( \varphi - \frac{\pi}{n} - \frac{2\pi}{n} \cdot \left[ \frac{n\varphi}{2\pi} \right] \right) = R \cos \frac{\pi}{n}.$$
