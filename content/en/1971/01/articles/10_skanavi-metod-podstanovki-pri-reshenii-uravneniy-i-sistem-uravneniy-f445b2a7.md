---
id: 1971-1-skanavi-metod-podstanovki-pri-reshenii-uravneniy-i-sistem-uravneniy-f445b2a7
issue: kvant_1971_1
year: 1971
number: "1"
title: Substitution method for solving equations and systems of equations
authors:
  - Сканави М. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 44
page_last: 46
page_labels: 42-44
tag: BBD2
lang: en
source: kvant_digital
extraction: vision
content_sha256: 428cde206230bd928d713ca0652ad534af3f5c3cbbd5e890f96af9f7db57b961
prompt_sha256: draft-1
translated_from: content/ru/1971/01/articles/10_skanavi-metod-podstanovki-pri-reshenii-uravneniy-i-sistem-uravneniy-f445b2a7.md
source_content_sha256: bc378a861fe378ca40c4fb2349a2b5d907c97d275e915a1ca9d7bc3665e373d3
translation_model: draft
translation_run: en-draft-2026-11-03
translation_quality: draft
---

⟦folio 42⟧

---
running_head:
folio:
---

it is easy to report that the substitution turns out to be effective
$$x + \frac{1}{x} = u.$$
Indeed, we find that then
$$x^2 + \frac{1}{x^2} = u^2 - 2$$
and solving the equation transforms to the equation
$$4u^2 + 12u - 55 = 0,$$
squared relative to the new quantity $u$. Having solved it, we find that $u_1 = \frac{5}{2}$ and $u_2 = -\frac{11}{2}$. To find $x$ we obtain two equations
$$x + \frac{1}{x} = \frac{5}{2},$$
$$x + \frac{1}{x} = -\frac{11}{2}.$$
From them we find that
$$x_1 = 2, x_2 = \frac{1}{2}, x_3 = \frac{-11 + \sqrt{105}}{4},$$
$$x_4 = \frac{-11 - \sqrt{105}}{4}.$$
Expanding the boundaries of our conversation, we will inform the reader that if we have to solve a reciprocal equation of an odd degree, then whatever this degree is, one root of such an equation is written immediately - it is equal to (-1). You can check this using the example of a reciprocal equation of the fifth degree
$$ax^5 + bx^4 + cx^3 + cx^2 + bx + a = 0.$$
If $x = -1$, then
$$-a + b - c + c - b + a = 0.$$
After dividing by $(x+1)$, this is a property equation of a fourth-degree reciprocal equation, which can be solved in general using the method shown in solving Example 2.
Example 3. Solve equation $10x^3 - 3x^2 - 2x + 1 = 0.$
Solution. The reader should be aware that the entire roots of an algebraic equation should be sought among the divisors of the free term. But here it is equal to one, and 1 or -1, as is easy to check, is not the roots of this equation. So, this equation has no whole roots. We advise the reader to try substitution for all equations that do not have integer roots
$$x = \frac{1}{y}.$$
In our case, this substitution leads to the equation
$$\frac{10}{y^3} - \frac{3}{y^2} - \frac{2}{y} + 1 = 0,$$
$$y^3 - 2y^2 - 3y + 10 = 0.$$
Having tested the divisors of the free term of this equation, we are happy to discover that the divisor (-2) serves as its root. In this case, lowering the degrees of the equation using this root, we find the remaining two roots $y_2 = 2 + i$ and $y_3 = 2 - i$. Hence,
$$x_1 = -\frac{1}{2}, x_2 = \frac{1}{2 + i} = \frac{2}{5} - \frac{1}{5} i,$$
$$x_3 = \frac{1}{2 - i} = \frac{2}{5} + \frac{1}{5} i.$$
Example 4: Solve equation $\sqrt{x^2 + x + 4} + \sqrt{x^2 + x + 1} = \sqrt{2x^2 + 2x + 9}.$
Solution. If you try to free an equation from radicals by squaring it, then it’s scary to think about what degree the equation will turn out to be after all the radicals disappear! It is clear that this approach will not do us any good. But even here, after reflection, we can conclude that the substitution
$$x^2 + x + 1 = t$$
will lead us to a simpler equation for $t$, namely:
$$\sqrt{t + 3} + \sqrt{t} = \sqrt{2t + 7}.$$
This irrational equation allows us to solve it like this (the technique we are using now is also good for many other irrational equations -

⟦folio 43⟧

not containing radicals of the second degree!): let’s compose the difference of the subdecimal expressions of the radicals located on the left, and we get that $(t+3) - t=3$.

Now we factorize this difference (using the formula for the difference of squares) and find that $(\sqrt{t+3} + \sqrt{t})(\sqrt{t+3} - \sqrt{t}) = 3$.

From here, by dividing by the original equation (with respect to $t$), we obtain that

$$\sqrt{t+3} - \sqrt{t} = \frac{3}{\sqrt{2t+7}}.$$

Subtracting from the original equation what we now have, we find that

$$2\sqrt{t} = \sqrt{2t+7} - \frac{3}{\sqrt{2t+7}},$$

$$2\sqrt{t} = \frac{2t+4}{\sqrt{2t+7}}, \sqrt{t} = \frac{t+2}{\sqrt{2t+7}}.$$

The procedure we have just carried out allows us to get rid of radicals by simply squaring the parts of the equation. Let's do this:

$$t = \frac{t^2+4t+4}{2t+7}, t^2+3t-4=0.$$

Hence $t_1=1, t_2=-4$. Next, note that we are only interested in positive values ​​of $t$, since $t = x^2+x+1 > 0$

for all values ​​of $x$. Therefore, we discard the unsuitable root $t_2$ and obtain one quadratic equation for finding $x$

$$x^2+x+1=1, \quad x^2+x=0$$

with roots $x_1=-1$ and $x_2=0$. It is easy to check that both of them are roots of this irrational equation.

Example 5. Solve a system of equations

$$\begin{cases} \frac{x^3}{y} + xy = 40, \\ \frac{y^3}{x} + xy = 10. \end{cases}$$

(Limit yourself to finding real solutions).

Solving a system of equations students practice a significant solution. At the same time, in these cases it often turns out to be very effective. Before going to the solution of the proposed system, I will allow myself to express some general messages about the substitution method when solving a system of two equations with two exceptions. If these latter are designated by the letters $x$ and $y$, then it is often useful to move on to the new quantities $\rho$ and $\varphi$ in accordance with the following equalities:

$$x = \rho \cos \varphi,$$

$$y = \rho \sin \varphi.$$

The reader who is sufficiently familiar with the method of coordinates on the plane, almost that if $x$ and $y$ serve as the Cartesian coordinates of some point, then $\rho$ and $\varphi$ are the so-called polar coordinates of the same point. The geometric meaning of polar coordinates and their connection with Cartesian ones will become clear from figure, which we now recommend everyone to CAREFULLY consider:

⟦folio 44⟧

We note that the origin $O$ has $\rho=0$, and the angle $\varphi$ has no defined value for it. All other points of the plane will be subordinated to a single pair of polar coordinates ($\rho, \varphi$), if we require that there be

$$0 \leqslant \rho < +\infty,$$
$$0 \leqslant \varphi < 2\pi.$$

We use equalities (!) to solve this system of equations, for which instead of $x$ and $y$ in the domain of the system equation we substitute their expressions through $\rho$ and $\varphi$; we get that

$$\begin{cases} \frac{\rho^3 \cos^3 \varphi}{\rho \sin \varphi} + \rho \cos \varphi \rho \sin \varphi = 40, \\ \frac{\rho^3 \sin^3 \varphi}{\rho \cos \varphi} + \rho \cos \varphi \rho \sin \varphi = 10. \end{cases}$$

or after processing that

$$\begin{cases} \rho^2 \text{ctg} \varphi = 40, \\ \rho^2 \text{tg} \varphi = 10. \end{cases}$$

By dividing the first equation by the second we find that

$$\text{ctg}^2 \varphi = 4.$$

Hence $\text{ctg} \varphi = 2$ or $\text{ctg} \varphi = -2$. The second (negative) value $\text{ctg} \varphi$ is immediately discarded, since we have $\text{ctg} \varphi$ and $\rho^2$ having the same sign, and $\rho^2$ cannot be negative. Now, using the known cotangent, we need to find the sine and cosine of the angle $\varphi$. I follow this without words:

$$\cos^2 \varphi = 1 + \text{ctg}^2 \varphi = 5,$$
$$\cos \varphi = \sqrt{5},$$
$$\cos \varphi = -\sqrt{5},$$

$$\sin \varphi = \frac{1}{\sqrt{5}}, \quad \sin \varphi = -\frac{1}{\sqrt{5}},$$
$$\cos \varphi = \frac{2}{\sqrt{5}}, \quad \cos \varphi = -\frac{2}{\sqrt{5}}.$$

Next we find $\rho$ from the fact that

$$\rho^2 \text{ctg} \varphi = \rho^2 \cdot 2 = 40, \quad \rho^2 = 20.$$

We get that $\rho = 2\sqrt{5}$. Using equalities (!) using the known $\rho$ and $\varphi$, we find the following two pairs of numbers as a solution to this system of equations:

$$x_1 = 2\sqrt{5} \cdot \frac{2}{\sqrt{5}} = 4,$$
$$y_1 = 2\sqrt{5} \cdot \frac{1}{\sqrt{5}} = 2;$$
$$x_2 = 2\sqrt{5} \left(-\frac{2}{\sqrt{5}}\right) = -4,$$
$$y_2 = 2\sqrt{5} \left(-\frac{1}{\sqrt{5}}\right) = -2.$$

It is incorrect to assume that this system can be solved only by passing to polar coordinates (it can be solved, for example, also this way: transfer $xy$ from the left sides of the equation to the right, then recombine the results and obtain a quadratic equation for $xy$; the rest is obvious). Meanwhile, this technique should be adopted. It allows us, in a certain sense, to regulate our transformations and makes it possible to use the entire apparatus of trigonometry. In what cases is it beneficial to use this technique, and in what cases is it not? Your experience helps answer this question, which you can enrich with your own work!

While there is time before the entrance exams, act!
