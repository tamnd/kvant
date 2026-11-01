---
id: 1986-2-v-reshenie-stereometricheskoy-zadachi-a4db58fc
issue: kvant_1986_2
year: 1986
number: "2"
title: '[Solving a stereometric problem]'
authors:
  - Дубровский В. Н.
rubric: raznoe
rubric_sub: Разное
page_first: 29
page_last: 29
page_labels: "27"
tag: N6CH
lang: en
source: kvant_digital
extraction: vision
content_sha256: 23d9c671a1e458a967b24d40dfa158dbaeb932b1863aaa3457c9553c8d1ab77a
prompt_sha256: draft-1
translated_from: content/ru/1986/02/articles/09_v-reshenie-stereometricheskoy-zadachi-a4db58fc.md
source_content_sha256: 1c79a90cbc77f473099a4e0a07167b64cc1495de669dd19124484d752c1cf7be
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 27⟧

Here's an example:
$$] - \infty; 0 [ \cup \{ 4 \}.$$
The first problem given at the beginning of the note is solved using the same scheme.

We write out the equivalent system again:
$$\begin{cases} 8x - 6p - 3 > 0, \\ \frac{x^2 + 2px}{8x - 6p - 3} = 1 \end{cases}$$
(it is clear that if these conditions are met, the inequality $x^2 + 2px > 0$ is also satisfied), that is
$$\begin{cases} 8x - 6p - 3 > 0, \\ x^2 + 2x(p - 4) + 6p + 3 = 0. \end{cases}$$
Again two cases are possible:
First case. A quadratic equation has a single root, that is, the discriminant of the equation is zero. Let's write this condition:
$$p^2 - 14p + 13 = 0,$$
whence $p = 1$ and $p = 13$.
For $p = 1$ we get $x = 3$; with $p = 13$ we get $x = -9$. Substituting the found values ​​$x$ and $p$ into the inequality $8x - 6p - 3 > 0$, we are convinced that the values ​​$p = 13$, $x = -9$ are not suitable. Conversely, the values ​​$p = 1$, $x = 3$ satisfy this inequality. Thus, the original equation at $p = 1$ has a single root $x = 3$*).

Second case. A quadratic equation has two roots, the larger of which falls into the ODZ, and the smaller of which does not.

The inequality $8x - 6p - 3 > 0$ implies that $x > \frac{6p - 3}{8}$, so if $x_1$ and $x_2$ ($x_1 < x_2$) are the roots of the quadratic equation $x^2 + 2x(p - 4) + 6p + 3 = 0$, then it must be $x_2 > \frac{6p + 3}{8}$ and $x_1 \leqslant \frac{6p + 3}{8}$. Again, as in example $\frac{\lg px}{\lg(x + 1)} = 2$ (see Fig. 2) we obtain that all conditions will be satisfied if and only if for the function $f(x) = x^2 + 2x(p - 4) + 6p + 3$ there is $f\left(\frac{6p + 3}{8}\right) \leqslant 0$. Having written this condition $\left(\frac{6p + 3}{8}\right)^2 + 2 \cdot \frac{6p + 3}{8}(p - 4) + 6p + 3 \leqslant 0$, we obtain after transformation $(6p + 3)(22p + 3) \leqslant 0$, whence $-\frac{1}{2} \leqslant p \leqslant -\frac{3}{22}$.

So, the answer to this problem is:
$$\left[ -\frac{1}{2}; -\frac{3}{22} \right] \cup \{1\}.$$
I. G. Gabovich
P. I. Gorshtein

*) This answer is given in the above collection of problems.

Our cover

Obviously the stereometric problem begins with the fact that we reproduce in general terms the configuration considered in it. In the problem from the cover of the previous issue, it is easiest to present the configuration directly as you solve it. The big one on the next one (shown on the cover) actually won’t come across to us.

The solution is based on the following useful statement: two circles of radii $R_1$ and $R_2$ touch each other externally if and only if the segment of their common external tangent between the points of contact is equal to $2\sqrt{R_1R_2}$ (Fig. 1). The proof of this statement is very convenient from figure 1. Considering the circles in this statement as sections of two balls to a plane passing through their centers, or as sections of a ball and a slit to a plane passing through the center of the ball perpendluklar to the axis of the slind, we obtain the conditions for external tangency of the balls or cylinder; for example, in the latter case it is necessary that the distance from the point of contact of the ball with the plane to the straight line along which the cylinder

$AB^2 = O_2C^2 = (R_1 + R_2)^2 - (R_1 - R_2)^2$

Fig. 1.
