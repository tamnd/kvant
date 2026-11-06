---
id: 1991-12-gabovich-dva-resheniya-odnoy-zadachi-f92c1f32
issue: kvant_1991_12
year: 1991
number: "12"
title: Two solutions to one problem
authors:
  - Габович И. Г.
rubric: shkola-v-kvante
page_first: 44
page_last: 46
page_labels: 42-44
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1abde22ef5adf59558ba56bf0a9986f3084e95c0a214d5e816c99e9d655fa4f4
prompt_sha256: draft-1
translated_from: content/ru/1991/12/articles/13_gabovich-dva-resheniya-odnoy-zadachi-f92c1f32.md
source_content_sha256: db56217ce336e23b5cb75298a5488f2a021cdb2e48eb0abd202fd71e68a6d348
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 42⟧

Two solutions to one problem

It often happens that when solving geometric problems, two answers are obtained (as a rule, this is due to the presence of two roots in the quadratic equation). The question naturally arises: do both solutions satisfy all the conditions of the problem?

Let us illustrate this with a modern example.

Problem 1. Find side AB of triangle ABC if AC=6, BC=4, ∠BAC=30°.

Solution. Let AB=x. Having written the cosine theorem for triangle ABC, after transformation we obtain a quadratic equation for x:

$$x^2 - 6\sqrt{3}x + 20 = 0,$$

whence $x=3\sqrt{3} \pm \sqrt{7}$.

In this case, both roots of the equation are valid for us, since the existence of two triangles satisfies the conditions of the problem; it is easy to verify by performing the corresponding construction (Fig. 1).

The next task is somewhat more difficult.

Problem 2. A circle is inscribed in a triangle with perimeter 20. The tangent segment drawn to the circle parallel to the base, enclosed between the sides of the triangle, is equal to 2.4. Find the base of the triangle.

Solution. Let EF be the tangent segment to the incircle parallel to the base AC of triangle ABC (Fig. 2). From the similarity of triangles BAC and BEF it follows that their half-perimeters p and p' are related as corresponding sides, i.e.

$$\frac{p'}{p} = \frac{EF}{AC}.$$

(*)

At the same time $p' = BG = p - AC$.

Let AC=x. From equality (*) we get:

$$\frac{10-x}{10} = \frac{12}{5x}$$

(**)

whence $x=4$ and $x=6$.

Two answers again!

Here it is not possible to explain the appearance of two answers as simply as we did when solving problem 1. Therefore, we will try to use a different method.

Let's put EF=y. From correspondence (**) we get:

$$y = \frac{1}{10}x(10-x).$$

On the right side of this equality there is a square function, the graph of which is shown in figure 3. This function takes positive values ​​at $x \in (0; 10)$, has a maximum of 2.5 at $x=5$. The function takes any value from the interval (0; 2.5) twice - at points symmetrical with respect to the point $x=5$.

We see, therefore, that for $y=2,4$ there are two values ​​of $x$ that give a solution to the problem posed.

⟦folio 43⟧

---
running_head:
folio:
---

By the way, this simple study shows that for any given $y \in (0; 2,5)$ there are two solutions to the problem, for $y = 2,5$ there is one, and for $y > 2,5$ there is no solution. We can do all this in general form, assuming that the perimeter of the triangle is equal to $2p$, and the segment $EF$ is equal to $a$. As a result, we obtain conditions on $a$ and $p$ under which the problem has two, one, or no solutions.

Exercise 1. Do this yourself.

Let's look at another example.

Problem 3. The design of a raked trapezoid is 10, and the area is $S = 48$. Find the height $h$ of this trapezoid.

Solution. Let's draw the height $BE$ in our trapezoid. Let $AD = a, BC = b$ (Fig. 4). Then $S = \frac{a+b}{2}h, BE = (a+b)/2$ (see this for yourself), and $d^2 = h^2 + \left(\frac{a+b}{2}\right)^2$. Let's denote $(a+b)/2$ by $k$. The previously written correspondences give a system of equations:

$$\begin{cases} hk = S, \\ h^2 + k^2 = d^2, \end{cases}$$

solving which we obtain two values ​​of $h$:

$$h_{1,2} = \sqrt{\frac{d^2 \pm \sqrt{d^4 - 4S^2}}{2}}.$$

(In our problem $h_1 = 6, h_2 = 8$.) In this case, the necessary condition for the solvability of the problem is immediately visible: $d \geq \sqrt{2S}$.

Let us now express $d^2$ in terms of $h$:

$$d^2 = \frac{S^2}{h^2} + h^2.$$

The function on the right side of this equation returns at $h > \sqrt{S}$, decreases at $h < \sqrt{S}$, and reaches its minimum of $2S$ at $h \leq \sqrt{S}$.

Moreover, this function takes each value greater than $2S$ twice. Therefore, for $d > \sqrt{2S}$ there are two trapezoids that satisfy the conditions, for $d = \sqrt{2S}$ there is one, and for $d < \sqrt{2S}$ there are none.

Now let's look at two stereometric problems.

Problem 4. A cone is described around the ball. Find the angle of inclination of the generatrix of the cone to the plane of the base-

⟦folio 44⟧

---
running_head:
folio:
---

If the ratio of the volumes of the cone and the sphere is 3.6.

Solution. The axial section considered in the problem of a combination of figures is an equilateral triangle with a circle inscribed in it (Fig. 5), the radius of which is equal to the radius of the ball.

Putting $OO_1 = r$, $\angle SBA = \alpha$ ($0 < \alpha < \pi/2$), we find that $BO = r \text{ctg} \alpha/2$, $SO = r \text{ctg} \frac{\alpha}{2} \text{tg} \alpha$. Having written the ratio of the volumes of the cone and the ball, we obtain the equation of the relative $\alpha$:

$$\frac{1}{4} \text{ctg}^3 \frac{\alpha}{2} \cdot \text{tg} \alpha = 3,6.$$

To solve it, it is convenient to perform the substitution $t = \text{tg} \frac{\alpha}{2}$, leading to the equation

$$7,2t^4 - 7,2t^2 + 1 = 0,$$

whence $t_1 = \frac{\sqrt{6}}{6}, t_2 = \frac{\sqrt{30}}{6}$. As a result, we obtain two values ​​of the exclusive angle: $\alpha_1 = 2 \text{arctg} \sqrt{6}/6$ and $\alpha_2 = 2 \text{arctg} \sqrt{30}/6$.

Now let's explain what causes this. First, “on the fingers.” An infinite number of cones can be described around a ball. If the cone is “narrow and very high” or “very wide but not high” (Fig. 6), the ratio of the volumes of the cone and the ball is very large. It is intuitively clear that for some values ​​of the angle $\alpha$ this ratio is minimal. The path this minimum value is $k_0$. Then at $k > k_0$ there will be cones - “narrow and high” and “wide and low”, for which the volume ratio will be equal to $k$.

Now let's conduct an accurate study. We saw that

$$k = \frac{1}{4} \text{ctg}^3 \frac{\alpha}{2} \cdot \text{tg} \alpha.$$

Introducing a new variable $x = \text{tg}^2 \frac{\alpha}{2}$, we obtain $k = \frac{1}{2x(1-x)}$ for $0 < x < 1$. The denominator is a quadratic function of $x$. Therefore the function $k$ kills

from +∞ to 2 at $0 < x < 1/2$ and increases without limit at $1/2 < x < 1$. We see that at $k > 2$ there are two values ​​of $x$ for which our function is equal to $k$. And this means that for any $k > 2$ (in part, for $k = 3,6$) there are two cones that satisfy the conditions.

Of course, the analyzed problems represent the simplest cases that can arise when solving geometric problems, since the “tip of the iceberg” is given. Sometimes, when receiving several answers, it becomes necessary to conduct a more rigorous study, during which a permanent solution is sometimes discarded. We just wanted to show how a number of geometric problems can be reduced to problems about the study of certain functions. In conclusion, we suggest that you solve the following problems on your own.

Battles

2. Through the point $P$ of the diameter of a circle of radius $R$, a chord $AB$ is drawn, forming an angle of $60^\circ$ with the diameter. Find $BP$ if $AP = a$ (consider all possible cases).

3. The ratio of the radius of a ball circumscribed about a regular quadrangular straight line to the side of the base is $3/4$. Find the angle between the side face and the area of ​​the base.

4. The ratio of the radius of a ball circumscribed about a regular triangular straight line to the side of the base is $k$. For what values ​​of $k$ does the problem have a solution? How many will be solved depending on $k$?

I. Gabovich
