---
id: 1971-9-atamukas-kvadratnyiy-trehchlen-c7b06136
issue: kvant_1971_9
year: 1971
number: "9"
title: Square trinomial
authors:
  - Атамукас М. С.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 43
page_last: 48
page_labels: 41-46
tag: JMQM
lang: en
source: kvant_digital
extraction: vision
content_sha256: 49af10450c1b59a159dea071ab467f626d361a2f15a89a1b71c91ce8d84dc644
prompt_sha256: draft-1
translated_from: content/ru/1971/09/articles/08_atamukas-kvadratnyiy-trehchlen-c7b06136.md
source_content_sha256: 590b3ec0adb9053eb3eb4ffa9c54a377c5a76b9f500d14a488f10a10c5083a8f
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 41⟧

M. S. Atamukas

A square triline is a polynomial of the second degree of general form

$$ax^2 + bx + c, \quad a \neq 0.$$

In entrance exams in mathematics, problems directly or indirectly related to the square trilen are offered quite often. Yes, this is not surprising - in the school curriculum, a lot of space and time is removed from studying the quadratic equation

$$ax^2 + bx + c = 0,$$

finding out the properties of a quadratic function

$$y = ax^2 + bx + c.$$

This function is also found in physics; for example, when describing the movement of materials of a point thrown obliquely to the horizon.

Schoolchildren, of course, are well aware of all the formulas related to the square triangle; they can also draw the graph of a quadratic function - parabolic. However, when it comes to solving a specific problem, most tools try to act purely analytically, using only formulas. Meanwhile, very often the use of geometric considerations allows us to obtain an answer easier and faster.

We will show with several examples how important it is to think simultaneously in both algebraic and geometric languages ​​when solving a problem.

In order to check how well you are familiar with the properties of a square trilen, let’s first consider this problem (it was offered in oral exams at Moscow State University).

1. figure 1 shows several graphs of square trilens. Figure approximate, scale not indicated. For each of these parabolas, determine the signs of the corresponding coefficients $a, b$ and $c$.

Take, for example, paraboly 4; it is the graph of some quadratic function

$$f(x) = ax^2 + bx + c.$$

Since the branches of this parabola are directed upward, the coefficient is $a > 0$. (Prove it! Many applicants explained it this way: “The textbook shows

⟦folio 42⟧

It turns out that if $a > 0$, then the parabola is directed upward.” Is such an obligation convincing?). Further, the coefficient $c$ is equal to the value of the function $y$ at the point $x = 0$, that is, $c = f(0)$. From figure it is clear that parabola 4 intersects the positive semi-axis ordinat, and then $c > 0$. The abscissa of the vertex of the parabola is $-\frac{b}{2a}$; from figure it is clear that it is positive. We already know that $a > 0$, and therefore $b < 0$.

Answer: $a > 0$, $b < 0$, $c > 0$.

Readers can figure out the remaining cases presented in figure 1 on their own.

In many problems, it is necessary to find out the behavior of the quadratic function $f(x) = ax^2 + bx + c$ on a given interval $(\alpha, \beta)$, to describe the location of the roots of this triangle relative to a fixed point $x = \gamma$ of the abscissa axis, etc. In these problems, the geometric language makes interpretations simple and straightforward (and, moreover, quite strict!).

2. Based on the abscissa, the interval $\alpha < x < \beta$ is indicated. For what $a$, $b$ and $c$ the equation

$$ax^2 + bx + c = 0, \ a \neq 0, \ b^2 - 4ac > 0$$

has only one root on this interval?

In other words, we need to find out for which $a$, $b$ and $c$ the graph of the function $f(x) = ax^2 + bx + c$ intersects the x-axis on the interval $\alpha < x < \beta$ exactly once.

If one tries to solve this question analytically, using formulas for the roots $x_1$ and $x_2$ of a square triangle, then the conditions under which only one root lies between the numbers $\alpha$ and $\beta$ are written very grammatically. The geometric approach makes it possible to obtain this condition immediately and in a simple form.

Let's imagine how the graph of a triangle that satisfies the conditions set in the task can behave; Obviously, one of the four positions represented on figure 2 is possible. Note, further, that in each of these cases the values ​​of the function $f(x)$ at points $\alpha$ and $\beta$ have opposite signs, that is

$$f(\alpha)f(\beta) < 0,$$

or, in more detail,

$$(a\alpha^2 + b\alpha + c)(a\beta^2 + b\beta + c) < 0.$$

This condition is necessary and sufficient for the equation $ax^2 + bx + c = 0$ (for $a \neq 0, b^2 - 4ac > 0$) to have exactly one root on the interval $(\alpha, \beta)$.

⟦folio 43⟧

So the graphs helped us find this condition. They also suggest how to prove that this condition is necessary and sufficient.

Necessity. Let the equation have two roots $x_1$ and $x_2$ ($x_1 < x_2$), with one root lying inside the interval $(\alpha, \beta)$ and the other outside it. Then one of the numbers $\alpha, \beta$ lies inside the interval $(x_1, x_2)$, and the other one lies outside it. But the school textbook proves that the values ​​of the function $f(x) = ax^2 + bx + c$ outside the interval $(x_1, x_2)$ between the roots and the values ​​of the function inside this interval have opposite signs. Therefore, $f(\alpha) f(\beta) < 0$.

There is enough to eat. Let the numbers $f(\alpha)$ and $f(\beta)$ have different symbols. Then $b^2 - 4ac > 0$, equation $ax^2 + bx + c = 0$ has two roots $x_1$ and $x_2$, and the values ​​of the function inside and outside the interval $(x_1, x_2)$ have opposite signs. Therefore, only one of the numbers $\alpha, \beta$ lies inside the interval $(x_1, x_2)$. But this means, in turn, that only one of the numbers $x_1, x_2$ lies inside the interval $(\alpha, \beta)$.

It is clear that the square function

$$y = ax^2 + bx + c, \quad a \neq 0, \quad b^2 - 4ac = 0,$$

has only one root $x_0 = -\frac{b}{2a}$, and it lies on the interval $(\alpha, \beta)$ if $\alpha < -\frac{b}{2a} < \beta$.

Let us apply the messages just presented to solve the following problem, taken from the practice of oral exams.

3. Prove that the quadratic trinomial

$$f(x) = (x - a)(x - b) + \lambda (x - c)(x - d)$$

has real roots for any real $\lambda$ if it is known that exactly one of the numbers $c, d$ lies on the interval $(a, b)$ and the other outside it.

Looking at the graphs of various quadratic trinomials, it is easy to notice one important property: the maximum and minimum values ​​of the quadratic trinomial on the segment $[\alpha, \beta]$ can only be achieved at the following three points: at the point $x = -\frac{b}{2a}$, if, of course, it belongs to the segment $[\alpha, \beta]$; at point $\alpha$; at point $\beta$ (at the ends of the segment). Let's prove it; we will assume that $a > 0$ (the case $a < 0$ is analyzed in a similar way).

Let us extract a complete square from a quadratic trinomial:

$$f(x) = ax^2 + bx + c = a \left( x + \frac{b}{2a} \right)^2 + c - \frac{b^2}{4a}.$$

Using this notation, it is easy to show that for $a > 0$ the function $f(x)$ at the point $x = -\frac{b}{2a}$ has an absolute minimum equal to $c - \frac{b^2}{4a}$; on the interval $(-\infty, -\frac{b}{2a})$ it kills monotically, and on the interval $(-\frac{b}{2a}, \infty)$ it monotically increases.

*) Check for yourself that $f(\alpha) f(\beta) < 0$ implies $b^2 - 4ac > 0$.

⟦folio 44⟧

Because if
$$\alpha \leq -\frac{b}{2a} \leq \beta,$$
then the function $f(x)$ on the segment $[\alpha, \beta]$ takes the smallest value $c - \frac{b^2}{4a}$ at point $-\frac{b}{2a}$ (see graph 1 on figure 3).

The lowest value, due to monotonicity, is achieved at one of the ends of the interval.

Let now the point $-\frac{b}{2a}$ be located outside the segment $[\alpha, \beta]$ (see graphs 2, 3 on figure 3).

Then the segment $[\alpha, \beta]$ takes one of the monotonicity intervals, and, therefore, the minimum value is taken at one of its ends, and the maximum at the other.

Now try to formulate a necessary and sufficient condition under which the quadratic equation $ax^2 + bx + c = 0$ has two roots on the given interval $\alpha < x < \beta$.

The noticed property of the quadratic trinomial will make it easier for us to solve the following problems.

4. (MSU, mechanism, 1970). For what values ​​of the parameter $\alpha$ does the inequality
$$\sin^6 x + \cos^6 x + \alpha \sin x \cos x \geq 0$$
holds for all $x$?

Let's transform the left side of the inequality:
$$(\sin^2 x)^3 + (\cos^2 x)^3 + \alpha \sin x \cos x =$$
$$= (\sin^2 x + \cos^2 x) (\sin^4 x - \sin^2 x \cos^2 x + \cos^4 x) + \alpha \sin x \cos x =$$
$$= [(\sin^2 x + \cos^2 x)^2 - 3 \sin^2 x \cos^2 x] + \alpha \sin x \cos x =$$
$$= 1 - \frac{3}{4} \sin^2 2x + \frac{\alpha}{2} \sin 2x.$$

Let us denote $\sin 2x$ by $y$; Obviously, $-1 \leq y \leq 1$, the coefficient of $y^2$ is negative, therefore, on the interval $[-1; 1]$, the minimum of the square trinomial $-\frac{3}{4} y^2 + \frac{\alpha}{2} y + 1$ is achieved at the ends of the interval.

Therefore the inequality
$$-\frac{3}{4} y^2 + \frac{\alpha}{2} y + 1 \geq 0$$
holds on the entire interval $[-1; 1]$ if and only if the trinomial is nonnegative at the ends of the interval:

$$\begin{cases} -\frac{3}{4} (-1)^2 + \frac{\alpha}{2} (-1) + 1 \geq 0, \\ -\frac{3}{4} \cdot 1^2 + \frac{\alpha}{2} 1 + 1 \geq 0 \end{cases}$$

that is, $\alpha \leq \frac{1}{2}$ and $\alpha \geq -\frac{1}{2}$.

Answer: this inequality holds for all $x$ for $-\frac{1}{2} \leq \alpha \leq \frac{1}{2}$.

⟦folio 45⟧

Fig. 4. Minimum at $t = t_0$.

Fig. 5. Minimum at $t = t_0$.

5. (LSU, Mathematics, 1966). The rocket must travel a distance equal to $H$. It starts moving at a constant speed $v$ and at any moment can turn on an additional movement that gives constant acceleration $a$ ($a > 0$) and works until the end of the journey. Fuel consumption on a section of track at a constant speed is proportional to the time of movement, and when additional movement is turned on, it is proportional to the square of time with proportionality coefficients $k_1$ and $k_2$ correspondence ($k_1, k_2 > 0$). How long should the rocket move with the additional movement turned on in order for the promised fuel consumption to be the least?

Let $\tau$ be the time of movement of the rocket at a constant speed, $t$ be the time of movement with additional movement enabled, $A$ be the fuel consumption. From the equation:

$$H = v\tau + vt + \frac{at^2}{2}, \quad A = k_1\tau + k_2t^2$$

we find

$$\tau = \frac{1}{v} \left( H - vt - \frac{at^2}{2} \right), \quad A = \left( k_2 - \frac{ak_1}{2v} \right) t^2 - k_1t + \frac{k_1H}{v}.$$

Note that $0 \leq t \leq t_0$, where $t_0$ is the positive root of the equation

$$H = vt + \frac{at^2}{2}, \quad t_0 = \frac{-v + \sqrt{v^2 + 2aH}}{a}.$$

(This is the flight time if movement is enabled from the very beginning.) We need to find the minimum of the function $A = A(t)$ (*) defined on the segment $[0, t_0]$.

1) $k_2 - \frac{ak_1}{2v} < 0$. The vertex of parabolas $A = A(t)$ has an abscissa

$$t^* = \frac{k_1}{2 \left( k_2 - \frac{ak_1}{2v} \right)} < 0.$$

The parabola is located as indicated at figure 4. Minimum at $t = t_0$.

2) $k_2 - \frac{ak_1}{2v} = 0$; $A = -k_1t + \frac{k_1H}{v}$. Minimum at $t = t_0$ (Fig. 5).

3) $k_2 - \frac{ak_1}{2v} > 0$. Abscissa of the vertex of parabolas

$$t^* = \frac{vk_1}{2vk_2 - ak_1} > 0.$$

⟦folio 46⟧

Fig. 6. Minimum at $t = t^*$.

If $t^* \leq t_0$, then the minimum is at $t = t^*$ (Fig. 6).
If $t^* \geq t_0$, then the minimum is at $t = t_0$ (Fig. 7).
Answer: If $2vk_2 - ak_1 > 0$ and

$$\frac{vk_1}{2vk_2 - ak_1} \leq \frac{-v + \sqrt{v^2 + 2aH}}{a},$$

That

$$t = \frac{vk_1}{2vk_2 - ak_1}.$$

If $2vk_2 - ak_1 \leq 0$ or $2vk_2 - ak_1 > 0$ and

$$\frac{vk_1}{2vk_2 - ak_1} > \frac{-v + \sqrt{v^2 + 2aH}}{a},$$

That

$$t = \frac{-v + \sqrt{v^2 + 2aH}}{a}.$$

Exercises

1. Indicate the conditions under which both roots of the trinomial $f(x) = ax^2 + bx + c$ are less than the given number $\alpha$.
2. Indicate the conditions under which the given number $\alpha$ lies between the roots of the trinomial $f(x) = ax^2 + bx + c$.
3. (MSU, department of structural linearity, 1968). Find all values ​​of the parameter $b$ for which both roots of the quadratic equation $x^2 - 2bx - 1 = 0$ are real and do not exceed modulus 2.
4. (MSU, physicist, 1965). Find all values ​​of $a$ for which the equations $x^2 + x + a = 0$ are valid and greater than $a$.
5. (MSU, Department of Biology, 1969). Find all values ​​of $a$ for which the system

$$\begin{cases} x^2 + y^2 = a, \\ x - y = a \end{cases}$$

has a unique solution.
6. The radius of the base of a right circular cone is $R$ and its height is $H$. Determine the height of the cylinder inscribed in this cone and having the largest lateral surface.
7. (MSU, department of structural linearity, 1969). List all roots of the equation $x^2 + 1 = \cos x$.
8. (MSU, physicist, 1964). Find all values ​​of $m$ for which the expression $x^2 + mx + m^2 + 6m$ is negative for all values ​​of $x$ satisfying the inequalities $1 < x < 2$.
9. (MSU, physicist, 1963). The projectile leaves the ordium at an angle $\alpha$ to the horizon with a speed $v_0$. At the highest point of the trinomial there are two parts of equal mass outside, and the velocities of the parts immediately after the explosion are horizontal and lie in the plane of the trinomial. One half is outside at a distance of $S$ from the shot point. Determine the place where the second half fell, if it is known that it fell further than the first. Assume that the flight of a projectile occurs in airless space.
