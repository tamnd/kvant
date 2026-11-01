---
id: 1988-6-schegolev-shkolnaya-evm-risuet-okruzhnost-9ce43cdb
issue: kvant_1988_6
year: 1988
number: "6"
title: School computer draws a circle
authors:
  - Щёголев А. Г.
rubric: raznoe
rubric_sub: Разное
page_first: 58
page_last: 60
page_labels: 56-58
tag: F4A8
lang: en
source: kvant_digital
extraction: vision
content_sha256: e2c3089e66050cad26e3c64c47e6b3aae248eb066b0989a87008829d146b27f9
prompt_sha256: draft-1
translated_from: content/ru/1988/06/articles/13_schegolev-shkolnaya-evm-risuet-okruzhnost-9ce43cdb.md
source_content_sha256: 2a4c924644e89440ec978013e6596b361dacc10c50d113f53bd337f975a16520
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 56⟧

School computer draws a circle

A. G. SHEGOLEV

In the previous issue «Kvant» we talked a little about the graphic capabilities of the Yamaha school computer (and the MSX language - BASIC), painted beautiful pictures - or rather, compiled algorithms that perform these figure. This time we will demonstrate the graphical capabilities of machines when solving geometric construction problems. We will limit ourselves to analyzing only one problem, but this analysis will be very detailed; it is based on the principles of systematic programming (see «Kvant», 1987, No. 10, 11). So, the task: draw a circle through three points, given coordinate properties.

Your task is to construct a circle circumscribed by a triangle. This construction can be done in a unique way if the three points are different and do not lie on the same line.

Let us carry out a complete systematic construction of the algorithm and program.

Let's construct a circle passing through three points.
Coordinates of the first point
Coordinates of the second point
Coordinates of the third point

A circle cannot be drawn through these points (and this is the only way!)!

Fig. 1.

⟦folio 57⟧

Staging:
Given: $(x_1, y_1)$ — coordinates of points $A, B, C$.
Required: $\sigma$ - image of a circle (or part of it located within the screen).
When: $A, B, C$ do not lie on the same straight line.
Contact: $A \in \sigma, B \in \sigma, C \in \sigma$.

Scenario:
At figure 1, the blue circles contain the variable elements of the future dialogue - specific numbers reported by a person in response to a computer request. The figures in the bracket contain two versions of the computer: the first will be seen if the points with the given coordinates lie on the same straight line, the second - if the coordinates of the points satisfy the formulation; in this latter case, the screen will display the point $A, B, C$ with the given coordinates and a circle passes through them.

Method:
The condition that three given points $A, B$ and $C$ lie on the same line is equivalent to the collinearity of the vectors $\overrightarrow{AB}$ and $\overrightarrow{BC}$ (Fig. 2) and has the form
$$(x_2 - x_1)(y_3 - y_2) = (y_2 - y_1)(x_3 - x_2).$$
Exercise 1. Make sure that this condition also covers cases where any two (or even all three) points coincide.
In order to draw a circle, we must tell the performer (the school computer) the coordinates of its center and radius.
As is known, the center $S$ of the circumscribed circle can be found as the point of intersection of the midpoint of the redistributions to the two sides of the triangle $(AB$ and $BC$ on figure 3).
 vector coordinates:
$$\overrightarrow{AB} = (x_2 - x_1, y_2 - y_1),$$
$$\overrightarrow{BC} = (x_3 - x_2, y_3 - y_2);$$
$M$ - the middle of the side $AB$ - has coordinates
$$(\frac{x_1 + x_2}{2}, \frac{y_1 + y_2}{2});$$
 coordinates of point $N$ - midpoint

sides $BC$
$$(\frac{x_2 + x_3}{2}, \frac{y_2 + y_3}{2}).$$

Any point lying on the straight line $MS$ has coordinates $(M_x + \lambda m_x, M_y + \lambda m_y)$, where $M_x$ and $M_y$ are the corresponding abscise and ordinata of the point $M$; $m_x = y_2 - y_1$ and $m_y = x_2 - x_1$ are the coordinates of the vector $m$; $\lambda$ is some number.
Exercise 2. Prove that $\vec{m} \perp \overrightarrow{AB}$.
 the coordinates of points on the line $NS$ are expressed similarly through the parameter $\mu$, the coordinates of the point $N$ and the vector perpendicular to $\overrightarrow{BC}$ (for example, the vector $n = (y_3 - y_2, x_2 - x_3)$). To find the point of intersection of lines $MS$ and $NS$, we equate the corresponding coordinates:
$$\begin{cases} M_x + \lambda m_x = N_x + \mu n_x, \\ M_y + \lambda m_y = N_y + \mu n_y. \end{cases}$$

Solving this system of linear equations for the unknowns $\lambda$ and $\mu$, we obtain, for example, the expression for $\lambda$:
$$\lambda = \frac{1}{2} \frac{(y_3 - y_2)(y_3 - y_1) - (x_2 - x_3)(x_3 - x_1)}{(y_2 - y_1)(x_3 - x_2) - (x_2 - x_1)(y_3 - y_2)}.$$
 coordinates of the circle center
$$S_x = M_x + \lambda m_x = \frac{x_1 + x_2}{2} + \lambda (y_2 - y_1),$$
$$S_y = M_y + \lambda m_y = \frac{y_1 + y_2}{2} + \lambda (x_1 - x_2).$$
The radius obtuis is determined by the Pythagorean theorem as the distance between the center and any of the given points (for example,

⟦folio 58⟧

meter $A$):

$$r = \sqrt{(S_x - x_1)^2 + (S_y - y_1)^2}.$$

Now, having a script and a calculation method, let's build an algorithm and translate it into MSX - BASIC. We use the “image” auxiliary algorithm (GOSUB 200 is a call to the corresponding subroutine).

Algorithm:

alg circle
beginning
output “Construct a circle”, “passing through three points.”
request “Coordinates of the first point”; $x_1, y_1$
request “Coordinates of the second point”; $x_2, y_2$
request “Coordinates of the third point”; $x_3, y_3$

if $(x_2 - x_1)(y_3 - y_2) = (y_2 - y_1)(x_3 - x_2)$
then the conclusion “It is impossible” to “draw a circle through these points” “(and the only one at that)!”

inchete image
All
con

alg image
beginning
graphics
dot $(x_1, y_1)$, pink
dot $(x_2, y_2)$, pink
dot $(x_3, y_3)$, pink

$$\lambda := \frac{1}{2} \frac{(y_3 - y_2)(y_3 - y_1) - (x_2 - x_3)(x_3 - x_1)}{(y_2 - y_1)(x_3 - x_2) - (x_2 - x_1)(y_3 - y_2)}$$

$$S_x := \frac{x_1 + x_2}{2} + \lambda(y_2 - y_1)$$

$$S_y := \frac{y_1 + y_2}{2} + \lambda(x_1 - x_2)$$

$$r := \sqrt{(S_x - x_1)^2 + (S_y - y_1)^2}$$

circle $(S_x, S_y)$, $r$, pink
con

Program:

10' circle
