---
id: 1979-2-chernyavskiy-zadachi-na-geometricheskiy-smyisl-proizvodnoy-5b95e460
issue: kvant_1979_2
year: 1979
number: "2"
title: Problems on the geometric meaning of the derivative
authors:
  - Чернявский М.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 42
page_last: 45
page_labels: 40, 41, 43
tag: Z4Y5
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1a46f0132354e3b76bae524014339be833c7a5221e23d3d15ee1730bf11bef77
prompt_sha256: draft-1
translated_from: content/ru/1979/02/articles/12_chernyavskiy-zadachi-na-geometricheskiy-smyisl-proizvodnoy-5b95e460.md
source_content_sha256: 26ac8a720136214cbd2101bc7daf2de462a03fdee70d3e195d49db455ef3f189
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

M. Chernyavsky

Exercise
on the geometric meaning of the derivative

In § 10 of the textbook “Algebra and the beginnings of analysis” the equation of the tangent to the graph of a differentiable function is given and the geometric meaning of the derivative is explained *). The tasks discussed in this note use the opportunity to study the geometric facts of the analytical method.

From the physics course we know that the projector reflector is usually shaped like a parabolic of rotation. This is explained by the property of the parabola considered in the following problem:

Task 1. Prove that a ray of light emanating from the focus $F(0, 1/4a)$ of the parabola $y=ax^2$ is reflected at any point parallel to its symmetrical axis **).

Solution. Let $M(x_0; ax^2)$ be an arbitrary point of the parabola (Fig. 1). From the law of light reflection it follows that the angles formed with the tangent MP by the incident ray FM and the reflected ray MA are equal to each other. (On figure 1: $\hat{1}=\hat{2}$). We need to prove that MA | Oy, which is equal to the equality $\hat{2}=\hat{3}$ or, taking into account the previous one, the equality $\hat{1}=\hat{3}$. The latter follows from the equilaterality of the triangle PFM. So, it is enough to prove that $FM|=|FP|$.

$$|FM| = \sqrt{x_0^2 + \left(ax_0^2 - \frac{1}{4a}\right)^2} = \sqrt{a^2x_0^2 + \frac{1}{2}x_0^2 + \frac{1}{16a^2}} = \left|ax_0^2 + \frac{1}{4a}\right|.$$

To calculate $|FP|$ we write the equation for the tangent MP. Since $y'=2ax$, this equation is $y - ax_0^2 = 2ax_0(x - x_0)$. The field in it is $x=0$, let’s find the ordinate of the point $P$: $y = -ax_0^2$. Therefore, $|FP| = \left| \frac{1}{4a} - (-ax_0^2) \right| = \left| ax_0^2 + \frac{1}{4a} \right| = |FM|$.

They easily solve problems in which it is necessary to find the angle coefficient of a tangent or the equation of a tangent to the graph of a given function, if the point of tangency is known. However, in applied problems it is sometimes necessary to find this function from some additional conditions. We will encounter such a case in the next problem:

Task 2. The profile of the automaton site has the shape of a parabola (Fig. 2) with an axis passing vertically through the middle of the site with a height of the central part of 10 m and a base length of 120 m. What should be the saturation slope at the common ends of the site?

Solution. Note that the saturation slope is the slope of the tangent segments

Fig. 1.

⟦folio 41⟧

Fig. 2.

correlative to the parabola at points $A$ and $B$. Let us choose a coordinate system as indicated in figure 2. Then the parabola in this system is given by an equation of the form $y = ax^2 + 10$. Since the point $A(60; 0)$ lies on the parabola, $a = -\frac{1}{360}$.

Thus, the equation of the parabola is $y = -\frac{x^2}{360} + 10$. Hence $y' = -\frac{x}{180}$.

At point $A$: $tg\alpha = y'(-60) = \frac{1}{3}$, $\alpha = \arctg\frac{1}{3}$.

At point $B$: $tg\beta = y'(60) = -\frac{1}{3}$, $\beta = \pi - \arctg\frac{1}{3}$.

Sometimes you need to check whether a given straight graph concerns a given function. To do this, it is enough to check the following two conditions, which are necessary, and in

Fig. 3.

aggregate and sufficient to touch:

1. The straight line and the graph of the function have a common point.
2. At a general point, the value of an arbitrary given function is equal to the slope of the given line.

Problem 3. Do the straight line $x + 4y - 4 = 0$ touch the hyperbola $y = \frac{1}{x}$?

Solution. Having solved the system
$$\begin{cases} x + 4y - 4 = 0, \\ xy = 1, \end{cases}$$

we find the common point of the line and the hyperbola (2; 1/2). An arbitrary function $y = \frac{1}{x}$ is equal to $y' = -\frac{1}{x^2}$, and its value at the intersection point is $-y'(2) = -\frac{1}{4}$. But the slope of the straight line is the same. This means that this line touches the hyperbola at the point (2; 1/2).

Problem 4. Find the angle at which the parabola $y = x^2$ is visible from the point $A$. (2; -1).

Solution. Obviously, this angle is formed by two tangents to the parabola passing through the point $A$ (Fig. 3). Let us denote the desired angle by $\alpha$, and the angles of inclination of the tangents to the axis $Ox$ by $\alpha_1$ and $\alpha_2$. Then
$$tg\alpha = tg(\alpha_2 - \alpha_1) = \frac{tg\alpha_2 - tg\alpha_1}{1 + tg\alpha_1 \cdot tg\alpha_2} = \frac{k_2 - k_1}{1 + k_1 \cdot k_2},$$
where $k_1$ and $k_2$ denote the angular coefficients

⟦folio 43⟧

Pis. 5.

Pis. 6.

Pis. 7.

point with abscissa $x_0$, it is necessary and sufficient (compare with the conditions formulated before problem 3) that the following two conditions are satisfied:

1) $f(x_0) = \varphi(x_0)$;
2) $f'(x_0) = \varphi'(x_0)$.

Task 6. A circle of radius 1 with center on the positive strip Oy touches the parabolas $y = x^2$. Find the point of tangency $M$ and the position of the center of the circle $C$.

Solution. Let us denote the center of the circle by $C(0; a)$. Then the equation of the circle will be $x^2 + (y-a)^2 = 1$.

We are interested in the tangency of parabolas with the lower semicircle (Fig. 5, 6) whose equation has the form $y = a - \sqrt{1-x^2}$. Let us denote the abscissa of the tangent point by $x_0$. Using conditions 1), 2), we obtain

$$\begin{cases} a - \sqrt{1-x_0^2} = x_0^2, \\ \frac{x_0}{\sqrt{1-x_0^2}} = 2x_0, \end{cases}$$

that is

$$\begin{cases} \sqrt{1-x_0^2} = a - x_0^2, \\ x_0 \left(1 - 2\sqrt{1-x_0^2}\right) = 0. \end{cases}$$

One solution is obviously $x_0 = 0$, $a = 1$ (Fig. 6). The second equation has two more roots $x_0 = \pm \frac{\sqrt{3}}{2}$. They correspond to the same value $a = \frac{5}{4}$.

Thus we get a more interesting case: a circle centered at $C\left(0; \frac{5}{4}\right)$, tangent to the parabolas at points $M_1\left(\frac{\sqrt{3}}{2}; \frac{3}{4}\right)$ and $M_2\left(-\frac{\sqrt{3}}{2}; \frac{3}{4}\right)$ (Fig. 5).

Task 7. A point of motion in a straight line under the action of a constant force with acceleration $2 m/c^2$ and with zero initial speed. 3 seconds after the start of movement, the force stops acting, and the point begins to move uniformly at the same speed. Find the law of motion of a point and draw a motion graph.

Solution. Let us choose a coordinate system so that at the initial moment the point is at the origin of coordinates: $s = 0$ at $t = 0$. Then for $0 \leq t \leq 3$ we have $s = t^2$. For $t \geq 3$, the motion graph is part of the tangent to the parabola $s = t^2$, drawn at point (3, 9) in the direction of increasing $t$ (Fig. 7). Therefore his equation has the form

$$s - 9 = 6(t - 3)$$

or

$$s = 6t - 9.$$

Thus, the law of motion op-
