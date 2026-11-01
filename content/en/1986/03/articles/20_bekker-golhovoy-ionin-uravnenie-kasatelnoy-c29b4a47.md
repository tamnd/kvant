---
id: 1986-3-bekker-golhovoy-ionin-uravnenie-kasatelnoy-c29b4a47
issue: kvant_1986_3
year: 1986
number: "3"
title: Tangent equation
authors:
  - Беккер Б. М.
  - Гольховой В. М.
  - Ионин Ю. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 53
page_last: 56
page_labels: 51-54
tag: J3ND
lang: en
source: kvant_digital
extraction: vision
content_sha256: 86bfc6b917108ec4009e743b4bfab898bb65b25fd1374bf12498b935fa432422
prompt_sha256: draft-1
translated_from: content/ru/1986/03/articles/20_bekker-golhovoy-ionin-uravnenie-kasatelnoy-c29b4a47.md
source_content_sha256: 9f801c24003d94724823597f2a228b0bfefa4dbfd1e1ac313be2d8e790a66e7c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 51⟧

Tangent equation

V. M. BECKER,
V. M. GOLKHOVY,
Candidate of Pedagogical Sciences Yu. I. IONIN

In this article we will analyze several types of problems on the topic “Tangent”, which are often offered in specific mathematics exams.

Recall that the equation of a straight line with slope $k$ and passing through the point $M(x_0; y_0)$ can be written as $y = k(x - x_0) + y$. Since the angular coefficient of the tangent to the graph of the differentiable function $y = f(x)$ at the point with the abscissa $x_0$ is equal to $f'(x_0)$, the equation of the tangent has the form

$$y = f'(x_0)(x - x_0) + f(x_0).$$

Thus, to write the tangent equation, you need to know three numbers: $x_0$, $f(x_0)$ and $f'(x_0)$. Let's start with a problem in which the value $x_0$ is easily found from the condition, and then $f(x_0)$, $f'(x_0)$ are calculated.

Task 1 (MSU, Faculty of Psychology, 1980). Calculate the area of ​​the triangle bounded by the coordinate axes and the tangent to the graph of the function $y = \frac{x}{2x - 1}$, at the point with the abscissa $x_0 = 1$.

Solution. Let's find the tangent equation. To do this, we calculate $f(1)$, $f'(x)$, $f'(1)$ sequentially:

$$f(1) = 1, f'(x) = -\frac{1}{(2x - 1)^2}, f'(1) = -1.$$

The tangent equation has the form $y = -(x - 1) + 1$, that is, $y = -x + 2$.

This line intersects the coordinate axes at points $A$ (2; 0) and $B$ (0; 2). Thus, the required area is $S_{AOB} = \frac{1}{2} |OA| \cdot |OB| = 2$.

Problem 2 (Krasnoi State University, Faculty of Mathematics, 1980). The chord of the parabola $y = -a^2x^2 + 5ax - 4$ touches the curve $y = \frac{1}{1-x}$ at the point $x_0 = 2$ and is bisected by this point. Find $a$.

Solution. Our equation for the tangent to the graph of the function $f(x) = \frac{1}{1-x}$ at the point $M$ with the abscissa $x_0 = 2$:

$$f(2) = -1, f'(x) = \frac{1}{(1-x)^2}, f'(2) = 1,$$

so the tangent equation is $y = x - 3$.

Suppose that this tangent intersects the given parabola at points $A$ and $B$. The abscissas of the points $A$ and $B$ are the roots of the equation $-a^2x^2 + 5ax - 4 = x - 3$, or

$$-a^2x^2 + (5a - 1)x - 1 = 0.$$

The point $M$ is the midpoint of the segment $AB$ if and only if the abscissa is equal to the resulting abscissa of the points $A$ and $B$. Using Vieta's theorem, this condition can be written as the equality $\frac{5a - 1}{a^2} = 4$, which holds for $a = 1$ and for $a = \frac{1}{4}$. It remains to check whether, for these values, $a$ of the given parabolic line and straight line $y = x - 3$ intersect, that is, whether equation (1) has roots. For $a = 1$ we obtain the equation $-x^2 + 4x - 1 = 0$ with a positive descriptor, and for $a = \frac{1}{4}$ we obtain the equation $-\frac{1}{16}x^2 + \frac{1}{4}x - 1 = 0$ with a negative descriptor.

Thus, $a = 1$.

Problem 3. Our equation is the tangent to the parabolic $y = 2x^2 - x - 1$ at a point with ordinate 5, if it is known that this tangent does not pass through the point $M$ (1; -2).

Solution. The problem statement specifies not the abscissa, but the ordinata of the tangent point. To find the abscissa of the solution $2x^2 - x - 1 = 5$. We get two roots $x_1 = -\frac{3}{2}$, $x_2 = 2$. Let $f(x) = 2x^2 - x - 1$. Then $f'(x) = 4x - 1$, $f'(-\frac{3}{2}) = -7$, $f'(2) = 7$. Our tangent equations are $y = -7(x + \frac{3}{2}) + 5$ and $y = 7(x - 2) + 5$, that is, $y = -7x - 5,5$ and $y = 7x - 9$.

⟦folio 52⟧

Substituting the coordinates of the point $M$ into each of the equations, we find that the first tangent does not pass through the point $M$, but the second does pass through this point.

So the answer is: $y = -7x - 5, 5$.

In problems 4, 5, 6, the condition specified by the tangent allows us to find the value of an arbitrary one at the point of tangency, and then the abscissa and ordinate of this point.

Problem 4 (LSU, Faculty of Biology, 1977). A tangent is drawn to the graph of the function $y = x^3 - x^2 - 13x + 4$ at the point of the second quarter, where the slope is equal to 3. Find the points of intersection of this tangent with the coordinate axes.

Solution. Let $a$ be the abscissa of the point of tangency. By condition $f'(a) = 3$. Since $f'(x) = 3x^2 - 2x - 13$, to find $a$ we obtain the equation $3a^2 - 2a - 13 = 3$, which has roots $-2$ and $8/3$. The value $a = 8/3$ must be discarded (according to the conditions of the problem, the point of tangency lies in the second quarter). At $a = -2$ the tangent point has coordinates $(-2; 18)$ and lies in the second quadrant. The tangent equation is $y = 3x + 24$. This line intersects the coordinate axes at points $(-8; 0)$ and $(0; 24)$.

Problem 5 (LSU, Faculty of Mathematics and Mechanics, 1977). At what value of $a$ does the tangent to the graph of the function $y = a - x^2$ cut off from the first quarter an equilateral right angled triangle with area equal to $\frac{9}{32}$?

Solution. From the conditions of the problem it follows that the angle of inclination of the tangent to the abscissa axis is equal to $135^\circ$. Since $tg 135^\circ = -1$, the abscissa of the point of tangency is the root of the equation $-2x = -1$. Therefore, the tangent equation has the form $y = -x + a + \frac{1}{4}$. This straight line intersects the coordinate axes at points $A(0; a + \frac{1}{4}), B(a + \frac{1}{4}; 0)$.

According to the conditions of the problem, the points $A$ and $B$ lie on positive half-axes, so that $a + \frac{1}{4} > 0$. The area of ​​the triangle referred to in the conditions is $\frac{1}{2}(a + \frac{1}{4})^2$. Having solved the equation $\frac{1}{2}(a + \frac{1}{4})^2 = \frac{9}{32}$ (taking into account the fact that $a + \frac{1}{4} > 0$), we get the answer: $a = \frac{1}{2}$.

If a line is given to an equation of the form $y = kx + b$, then the coefficient $k$ is equal to the tangent of the angle of inclination of this line to the abscissa axis (we used this when solving problem 5). It follows that the lines given by equations $y = k_1x + b_1$ and $y = k_2x + b_2$ are parallel if and only if $k_1 = k_2$.

Problem 6 (Yerevan State University, Faculty of Applied Mathematics). At what point of the curve $y = \sqrt{1+x^2}$ is the tangent parallel to the line $y = 3x + 24$. This line intersects the coordinate axes at points $(-8; 0)$ and $(0; 24)$.

Solution. Let us calculate an arbitrary given function: $y' = \frac{x}{\sqrt{1+x^2}}$.

The angular coefficient of the tangent to the graph of the function at the point with the abscissa $a$ is equal to the value of the arbitrary function at this point. By condition, this slope must be equal to $\frac{1}{2}$. Thus, the abscissa of the desired point is the root of the equation $\frac{a}{\sqrt{1+a^2}} = \frac{1}{2}$. Solving this equation, we get $a = 1/\sqrt{3}$.

Answer: $(1/\sqrt{3}; 2/\sqrt{3})$.

Problem 7 (MAI, 1981). At what points in the graph of the function $y = (1-x)\times(1+x)^2$ should we check its tangents so that they pass through the point $(-1; 0)$?

Solution. Let us denote by $t$ the abscissa of the point of tangency. Since $y' = -(1+x)^2 + 2(1+x)(1-x) = (1+x)\times(1-3x)$, the tangent equation is $y = (1+t)(1-3t)(x-t) + (1-t)(1+t)^2$. The condition for the tangent passing through the point $(-1; 0)$ will now be written in the form of an equation for $t$:

$$0 = (1+t)(1-3t)(-1-t) + (1-t)(1+t)^2,$$

which can easily be converted to the form $(1+t)^2 \cdot 2t = 0$. The roots of this equation $t = 0$, $t = -1$ are the abscissas of the required points; We find their coordinates by calculating the corresponding values ​​of this function. Answer: $(0; 1), (-1; 0)$.

Problem 8 (Voronezh State University, Faculty of Mathematics). Find the equation of the tangent to the curve

⟦folio 53⟧

$$y = \frac{x+1}{x},$$
if it is known that the tangent passes through the point $M(a; b)$.
How many solutions are there depending on the point $M(a; b)$?

Solution. The answer to the second question of the problem is easy to imagine if you look at the graph of this function. On figure the hyperbola $1 + \frac{1}{x}$ and its asymptotes (except for their intersection point) are shown in red. One tangent can be drawn through each red dot. Areas from which two tangents to one branch of the hyperbola can be drawn are shown in blue. Two tangents also pass through the points of the green area, but one to each branch of the hyperbola. From the point of the area shaded in yellow, tangent lines are drawn to this hyperbole.

Let us now denote by $t$ the abscissa of an arbitrary point of this hyperbola and write the equation of the tangent at this point: $y = -\frac{1}{t^2}x + \frac{2}{t} + 1$. This line passes through the point $M(a; b)$ if and only if $b = -\frac{1}{t^2}a + \frac{2}{t} + 1$. This condition is equivalent to the system
$$\begin{cases} (b-1)t^2 - 2t + a = 0, \\ t \neq 0. \end{cases}$$

First, consider the case $b=1$ (in which case equation (2) is linear) and $a=0$ (this is the only case where equation (2) has the root $t=0$).

For $b=1$, equation (2) has a single root $t = \frac{a}{2}$, which is nonzero for $a \neq 0$. The equation for the only tangent in this case is $y = -\frac{4}{a^2}x + \frac{4}{a} + 1$.

For $a=0$ and $b \neq 1$, equation (2) has a unique root $t = \frac{2}{b-1}$ from zero. The equation for the only tangent in this case is $y = -\frac{(b-1)^2}{4}x + b$.

Finally, for $a=0, b=1$ equation (2) has no nonzero roots.

Let now $b \neq 1, a \neq 0$. The discriminant of the quadratic equation (2) is $4(1+a-a b)$. If $1+a-a b < 0$, then equation (2) has no roots, and, therefore, equation $M(a; b)$ cannot be drawn tangent to the graph of this function. Note that the inequality $1+a-a b < 0$ can be written as $b > \frac{1+a}{a}$ for $a > 0$, and as $b < \frac{1+a}{a}$ for $a < 0$. Thus, this inequality sets the yellow areas to figure.

If $1+a-a b = 0$ (that is, the point $M(a; b)$ lies on a hyperbola), then equation (2) has a single root $t = a$, and the tangent equation has the form $y = -\frac{1}{a^2}x + \frac{2}{a} + 1$.

If $1+a-a b > 0$, then equation (2) has two roots $t = \frac{1 \pm \sqrt{1+a-a b}}{b-1}$. Substituting these roots into the equation $y = -\frac{1}{t^2}x + \frac{2}{t} + 1$, we obtain the equation of two tangents passing through the point $M(a; b)$. Inequality $1+a-a b > 0$ together with inequalities $b \neq 1, a \neq 0$ defines the regions colored on figure in blue and green.

Task 9 (MIPT, 1982). From the point $M(1; 1)$ tangents are drawn to two branches of the hyperbola $y = \frac{k}{x} (k < 0)$, tangent to these branches at points $A$ and $B$, and the triangle MAB is regular. Find the coefficient $k$ and the area of ​​triangle MAB.

Solution. Let $t$ be the abscissa of an arbitrary point of a given hyperbola. The tangent at this point is given

⟦folio 54⟧

equation $y = -\frac{k}{t^2}x + \frac{2k}{t}$ is formed and passes through the point $M(1; 1)$ if and only if $1 = -\frac{k}{t^2} + \frac{2k}{t}$ or $t^2 - 2kt + k = 0$. This equation at $k < 0$ has two roots $t_1, t_2$ - the abscissa of the point $A$ and $B$. By Vieta's theorem $t_1 + t_2 = 2k, t_1t_2 = k$. Since the branches of this hyperbola are symmetrine with respect to the line $y = x$, and the point $M$ lies on this line, the points $A$ and $B$ are symmetrine with respect to the line $y = x$. However, you can verify this this way: $t_1t_2 = k$, that is, the abscissa of the point $B$ is equal to the ordinate of the point $A$, and the ordinata of the point $B$ is equal to the abscissa of the point $A$. Thus, point $A$ has coordinates $(t_1; t_2)$, and point $B$ has coordinates $(t_2; t_1)$. It follows that $|MA| = |MB|$ for any $k < 0$. Thus, $k$ must be found from the equality $|MA| = |AB|$. Let's calculate $|MA|^2$ and $|AB|^2$:

$$|AB|^2 = (t_1 - t_2)^2 + (t_2 - t_1)^2 = 2(t_1 - t_2)^2 = 2((t_1 + t_2)^2 - 4t_1t_2) = 8k^2 - 8k;$$

$$|MA|^2 = (t_1 - 1)^2 + (t_2 - 1)^2 = t_1^2 + t_2^2 - 2(t_1 + t_2) + 2 = (t_1 + t_2)^2 - 2(t_1 + t_2) - 2t_1t_2 + 2 = 4k^2 - 6k + 2.$$

We have obtained for $k$ the equation $8k^2 - 8k = 4k^2 - 6k + 2$, which has a single negative root $k = -\frac{1}{2}$. To find the plane of the correct triangle $MAB$, we substitute the found value $k$ into the expression for $|AB|^2$. We get $|AB|^2 = 6$ and therefore $S_{MAB} = \frac{3\sqrt{3}}{2}$.

Task 10 (MISiS, 1978). Begin the equation of the common tangent to the parabolas $y = x^2 + 4x + 8$ and $y = x^2 + 8x + 4$.

Solution. Let us denote by $u$ and $v$ the abscissas of the points of tangency. The equation of the tangent to the first parabola at the point with abscissa $u$ is $y = (2u + 4)x - u^2 + 8$, and the equation of the tangent to the second parabola at the point with abscissa $v$ is $y = (2v + 8x - v^2 + 4$. Since both equations are equations of the same line, we have $2u + 4 = 2v + 8$, $-u^2 + 8 = -v^2 + 4$. From the resulting system of equations we find $u = 2$, $v = 0$. Therefore, the equation of the desired tangent is $y = 8x + 4$.

Task 11 (2nd round of the Leningrad Mathematical Olympiad). Find the equation of the line tangent to the graph of the function $f(x) = x^4 - 2x^3 + x^2 + x - 2$ at two points.

Note that $f(x) - (x - 2) = x^2(x - 1)^2$. It turns out that if the polynomial $f(x)$ is represented in the form $f(x) = (x - a)^2g(x) + l(x)$, where $l(x)$ is a linear function and $g(x)$ is an arbitrary polynomial, then the line $y = l(x)$ is tangent to the graph of the function $y = f(x)$ at the point with the abscissa $a$. Indeed, in this case $f(a) = l(a)$, $f'(a) = l'(a)$, so the line $y = l(x)$ passes through the point $(a; f(a))$ and has a slope $f'(a)$. In our case, it immediately follows that straight line $y = x - 2$ touches the graph of this function at points with abscissas 0 and 1. Thus, straight line $y = x - 2$ touches the graph of this function at two points. Prove on your own that no other line touches the graph of this function at two points. So, the equation of the desired tangent is $y = x - 2$.

Exercises

1 (LSU, Faculty of Mathematics and Mechanics, 1977). At what value of $k$ will the tangent to the graph of the function $y = kx^2$ make an angle equal to $\frac{\pi}{3}$ with the abscissa axis and cut off a triangle with an area equal to $\frac{8\sqrt{3}}{3}$ from the fourth quadrant?

2 (Kazan State University, Faculty of Physics, 1978). On the curve $y = x^3 - 3x^2 + 2$, find the points at which the tangent is parallel to the line $y = 3x$.

3 (MSU, Faculty of Computational Mathematics and Cybernetics, 1978). Find the equation of a line passing through a point with coordinates $\left(\frac{1}{2}; 2\right)$, tangent to the graph of the function $y = -\frac{x^2}{2} + 2$ and intersecting the graph of the function $y = \sqrt{4 - x^2}$ at two different points.

4 (MSU, Faculty of Mathematics and Mathematics, 1980). tangent to the graph of the function $y = \sqrt{3x^2}$ also that the abscissa $c$ of the point of tangency belongs to the segment $\left[\frac{1}{2}; 1\right]$. At what value of $c$ will the area of ​​the triangle bounded by this tangent, the x-axis and the vertical line $x = 2$ be the smallest and what is this smallest area equal to?

5 (2nd round of the Leningrad Mathematical Olympiad, 1984). Prove that if two tangents to the parabola $y = x^2$ are mutually perpendicular, then the distance between the tangents is at least 1.
