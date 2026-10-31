---
id: 1975-2-vahovskiy-ryivkin-kogda-pomogayut-grafiki-494459e0
issue: kvant_1975_2
year: 1975
number: "2"
title: When graphs help
authors:
  - Ваховский Е. Б.
  - Рывкин А. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 45
page_last: 50
page_labels: 43-48
tag: WIUH
lang: en
source: kvant_digital
extraction: vision
content_sha256: d3a1609c46460dd98cf4c967fee29b32e051ea013e71f4fe16791e2615518a10
prompt_sha256: draft-1
translated_from: content/ru/1975/02/articles/13_vahovskiy-ryivkin-kogda-pomogayut-grafiki-494459e0.md
source_content_sha256: 3c11b55e3507d58175ef924989f111167fb43fd509697504818e9541abde4769
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 43⟧

Indeed, there is no material more familiar to applicants than the questions related to the study of the quadratic trinomial. Not a single examiner doubts that every student entering the university will easily solve a quadratic equation, remember Vieta’s theorem and cope with quadratic inequality. And, nevertheless, the practice of applied exams turns to this topic again and again, and the examinee does not always achieve success. They are overwhelmed by the desire to use information lying on the surface and, with its help, translate the problem into a formal language as quickly as possible. However, this solution is not always optimal.

A graphical representation of the problem conditions is often more helpful. It makes it possible to look at all the conditions together and find the simplest solution.

Let's show this with examples.

Problem 1. For what real values ​​$x_1$ and $x_2$ the equations

$$x^2 - 2x - a^2 + 1 = 0$$

lies between the roots $x_1'$ and $x_2'$ of the equation

$$x^2 - 2(a+1)x + a(a-1) = 0?$$

We need to find all $a$ such that their corresponding values ​​$x_1$, $x_2$, $x_1'$ and $x_2'$ satisfy the integer inequalities

$$x_1' < x_1 \leqslant x_2' < x_2'.$$

It is natural to start by trying to solve these equations and rewrite the equivalent integer inequalities problem for the unknown parameter $a$.

The roots of the first equation are $x_1,2 = 1 \pm a$, the roots of the second are $x_1',2 = a + 1 \pm \sqrt{3a+1}$.

Since it is unclear which of the numbers $1-a$ or $1+a$ is greater, we consider two cases. If $1-a \leqslant 1+a$, then the problem is reduced to the system: $x_1' < 1-a$, $x_2' > 1+a$. If $1+a < 1-a$, then we get another system: $x_1' < 1+a$, $x_2' > 1-a$.

Ptak will be able to solve a set of two systems of inrational inequalities. Do this yourself and compare with others the solution to the problem that we will now present.

Let $f(x)$ and $g(x)$ correspond to the left sides of the first and second equations. The graphs of functions $y = f(x)$ and $y = g(x)$ are parabolas formed by upward branches. Let us denote by $x_1$ and $x_2$ the roots of the equation $f(x) = 0$, and by $x_1'$ and $x_2'$ the roots of the equation $g(x) = 0$. For everyone, $x \in (x_1', x_2')$ will be $g(x) < 0$. If $x_1' < x_1 < x_2' < x_2'$, then $g(x_1) < 0$ and $g(x_2) < 0$. The reverse is also true: if $g(x_1) < 0$ and $g(x_2) < 0$, then $x_1' < x_1 < x_2' < x_2'$. Thus, the problem reduces to solving the system of inequalities

$$\begin{cases} g(x_1) < 0, \\ g(x_2) < 0. \end{cases}$$

Substituting $x_1,2 = 1 \pm a$ into $g(x)$, we obtain the system

$$\begin{cases} (1-a)^2 - 2(a+1)(1-a) + a(a-1) < 0, \\ (1+a)^2 - 2(a+1)(1-a) + a(a-1) < 0. \end{cases}$$

⟦folio 44⟧

Solving it, we find $-\frac{1}{4} < a < 1$.

It should be noted that such a transformation of the problem is appropriate if the expressions for $x_1$ and $x_2$ are sufficiently simple.

However, accessing graphs does not always go as smoothly and easily as in the example just discussed.

Here's another example.

Problem 2 (MAI, 1970). For what real values ​​of the parameter m will the roots of the equation $(1+m)x^2-3mx+4m=0$ obey the conditions $2 < x < 5$?

Let us retell here the solution to the problem proposed by one applicant. The graph of a quadratic trinomial can have its branches up or down, depending on the sign of the coefficient at $x^2$. In both cases, the values ​​of the quadratic trinomial $f(2)$ and $f(5)$ will be of the same sign, that is, $f(2) \cdot f(5) > 0$. However, the roots $x_1$ and $x_2$ can be located either both to the left of 2, or both to the right of 5. In both cases, $f(2) \cdot f(5)$ will be greater than zero, but the abscissa of the vertex of the parabolas $x_0$ is outside the segment [2,5]. Therefore, we require that it be inside this segment. It remains to write down that this equation has real roots and reduce the solution to the problem to the solution of the system of inequalities

$$\begin{cases} f(2) \cdot f(5) > 0, \\ 2 < x_0 < 5, \\ D \geq 0. \end{cases}$$

The above reasoning is not without foundation, but, unfortunately, it indicates a lack of accuracy. Replacing the original task with system (1) cannot be considered justified. For an arbitrary quadratic trinomial $f(x)$ it is simply not true (see Fig. 1). But in addition to this, it may be that the coefficient of $x^2$ goes to zero, and then the graph of the function will be a straight line.

To obtain an accurate solution to a problem, you need to find a way to ensure that all possible situations are exhausted. For this purpose, it is convenient to find the coefficient of $x^2$. It can be either negative, zero, or positive.

When $1+m=0$, that is, $m=-1$, the equation becomes $3x-4=0$. Its root $x=4/3$ does not satisfy the conditions of the problem; it does not lie between 2 and 5.

Fig. 1.

If $1+m \neq 0$, then the left side of the equation is a quadratic trinomial, and its graph is a parabola. Since the trinomial must have real roots, then $D \geq 0$, that is, $9m^2-16m(m+1) \geq 0$. Hence $0 \geq m \geq -16/7$.

Now let's take advantage of the fact that the abscissa of the vertices of the parabolas must lie between its roots, that is, $2 < \frac{3m}{2(m+1)} < 5$.

We have already discovered that $m < 0$, and therefore the quantities $\frac{3m}{2(m+1)}$ will be positive only for $m+1 < 0$. Thus, the case when the branches of the parabolas are facing upward does not need to be considered. Let us solve the resulting inequality and find that

$$-4 < m < -\frac{10}{7}.$$

⟦folio 45⟧

Comparing it with the first constraint on $m$, we get $-16/7 \leq m < -10/7$. The graph of our parabola for such values ​​of $m$ is depicted at figure 2. Its branches are directed downward, and the roots will lie in the interval $(2, 5)$ if and only if $f(2) < 0$ and $f(5) < 0$, that is, $4+2m < 0$, $25+14m < 0$.

Hence $m < -2$. Finally $-16/7 \leq m < -2$.

Problem 3 (MAI, 1970). For what real values ​​of $k$ is one of the real solutions of the system
$$\begin{cases} x+y=2(k+1), \\ xy=k^2+3k-1 \end{cases}$$
satisfy the condition $|x| < 1$, $|y| > 1$?

Along with system (2), (3), it is natural to consider the corresponding quadratic equation
$$z^2-2(k+1)z+k^2+3k-1=0.$$ (4)
It is closely related to this system, the solutions of which are obtained using the roots $z_1$ and $z_2$ of equation (4):
$$(z_1, z_2), (z_2, z_1).$$
It is easy to reformulate the problem for equation (4): for what real $k$ one of the real roots of equation (4) is in the interval $(-1, 1)$, and the other root is located outside this interval.

Since the quadratic trinomial (4) must have two different real roots, then $D > 0$, and the graph of the left side of equation (4) is a parabola intersecting $z$ at two different points $z_1$ and $z_2$ ($z_1 < z_2$).

The conditions of the problem are satisfied only by the arrangement of the roots of the square trinomial when one of them lies inside the interval $(-1, 1)$, and the other outside this interval (Fig. 3). If we translate this into formulaic language, we get the following systems:

$$\begin{cases} z_1 < -1, \\ -1 < z_2 < 1; \end{cases}$$

The purely technical difficulties that arose in solving them are unjustifiably great. Studying the geometric picture can tell us a less cumbersome approach. It is easy to see that the parabola is located in one of those ways that are depicted in figure 3, if and only if the values ​​of the polynomial $f(z)$, standing on the left side of (4), at points $-1$ and $1$ have different signs, that is
$$f(-1)f(1) < 0.$$ (6)

Indeed, let the value $k$ satisfy the conditions of the problem. Then equation (4) has two real roots. If one of the roots coincides with $-1$ or $1$, then the left side of inequality (6) vanishes. Let us exclude these options from further consideration.

Let us now compile a table of values ​​$f(-1)f(1)$ for possible cases of equality of location $z_1$ and $z_2$ relative to the interval $(-1, 1)$ ($z_1 < z_2$)

Since all possible options have been exhausted, we simultaneously establish the necessity and sufficiency of condition (6). It remains to be decided

⟦folio 46⟧

inequality
$(k^2+5k+2)(k^2+k-2) < 0,$
or
$$\left( k + \frac{V_{17}+5}{2} \right) \left( k + \frac{V_{17}-5}{2} \right) \times (k+2)(k-1) < 0.$$
Answer:
$$-\frac{V_{17}+5}{2} < k < -2,$$
$$\frac{V_{17}-5}{2} < k < 1.$$
Problem 4 (MSU, Mechanics and Mathematics, 1971). Find all values ​​of $\alpha$ for which the system of inequalities
$$\begin{cases} x^2+2x+\alpha \leqslant 0, \\ x^2-4x-6\alpha \leqslant 0 \end{cases}$$
has a unique solution.
Inequalities (7) and (8) can have solutions only if the discriminants $D_1$ and $D_2$ of their left sides are non-negative.
Let's start with the case $D_1 = 0$, that is, $\alpha = 1$. Inequality (7) then takes the form $(x+1)^2 \leqslant 0$ and has a unique solution $x = -1$. For the found values ​​of $x$ and $\alpha$, inequality (8) is satisfied. Therefore, $\alpha_1 = 1$ is one of the exceptions to the values ​​$\alpha$.
Let now $D_2 = 0$, that is, $\alpha = -\frac{2}{3}$. The only solution to inequality (8) for $\alpha = -\frac{2}{3}$ is $x = 2$; inequality (7) for these $\alpha$ and $x$ is not satisfied.
Now we can assume that $D_1 > 0$ and $D_2 > 0$. For a given system to have a unique solution, it is necessary and sufficient that the integrals $[x_1, x_2]$ and $[x'_1, x'_2]$ have a single common point for the solution to inequalities (7) and (8). This can occur at either $x'_2 = x_1$ or $x_2 = x'_1$.
The graph of the left side of (7) is a parabola from the abscissa vertex $x_0 = -1$, and the graph of the left side (8) is a parabola from the abscissa vertex $x'_0 = 2$.

Fig. 4.
Therefore, if $\alpha$ satisfies the conditions of the problem, then the parabolas are located exactly as shown in figure 4. Therefore, the only possibility remaining is $x_2 = x'_1$, that is, $-1 + \sqrt{1-\alpha} = 2 - \sqrt{4+6\alpha}$. Solving this irrational equation, we find its only root $\alpha = 0$ (the value $\alpha = \frac{48}{49}$, which is also possible in the solution process - the constructed root). So, $\alpha = 0$.
Answer: 0; 1.
Problem 5 (NSU, Mechanics and Mathematics, 1968). For each real a medium of all lobes of the plane, the coordinates comorbix $x$, $y$ satisfy the system of inequalities
$$\begin{cases} y - 2x \geqslant 0, \\ -x^2 + 2ax - a^2 + a + 1 - y \geqslant 0, \end{cases}
$$
The smallest lobes with the highest ordinate are $y$.
Let us rewrite the system in the form
$$\begin{cases} y \geqslant f(x), \\ y \leqslant \varphi(x), \end{cases}$$
where $f(x) = 2x$ and $\varphi(x) = -x^2 + 2ax - a^2 + a + 1$. The graph of the curve $y = \varphi(x)$ is a parabola formed by branches downwards, and all points satisfying inequality (10) are located no higher than this parabola. Since for each $a$ we are interested in the solution of the system that has the most ordinate, inequality (10) can be replaced by the equation $y = \varphi(x)$.

⟦folio 47⟧

The graph $y = f(x)$ is a straight line passing through the origin of coordinates, and all points of the plane that satisfy inequality (9) lie not lower than this straight line. Thus, for each $a$ a point of the parabola $y = \varphi(x)$ must be found that lies not lower than the straight line $y = 2x$ and has the most ordinal. There are two possible cases of relative position of the parabola and the line: either the vertex of the parabola lies not lower than the line $y = 2x$, or it is located under this line (see Fig. 5). In the first case, the solution to the problem will be the point $(x_0, y_0)$, which is the vertex of the parabola, in the second - the point $(x_1, y_1)$, the coordinates of which satisfy simultaneously the equation of the line and the parabola. The equation of a parabola makes it easy to find the coordinates of its vertex: $x = a$, $y = a + 1$. We see that all vertices of the parabola $y = \varphi(x)$ at

Fig. 5.

Fig. 6.

different values ​​of the parameter $a$ lie on the line $y = x + 1$, and vice versa, each point $(x_0, y_0)$ of the line $y = x + 1$ corresponds to a parabola $y = \varphi(x)$, which has its vertex in it - it is enough to take $a = x_0$. Let's plot straight lines $y = x + 1$ and $y = 2x$ on one graph (Fig. 6). The intersection of these two lines is the point (1, 2). At $a \leqslant 1$ the line $y = x + 1$ will be located above the line $y = 2x$ and the solution to the problem will be the point $(a, a + 1)$. If $a > 1$, then the solution is the point $(x, y)$, satisfying the system
$$\begin{cases} y - 2x = 0, \\ -x^2 + 2ax - a^2 + a + 1 - y = 0; \end{cases}$$
hence $y = 2x$ and $x^2 - 2(a - 1)x + a^2 - a - 1 = 0$.

The equation has two real roots when $D = 2 - a \geqslant 0$, that is $a \leqslant 2$. Of these, the larger one satisfies the problem conditions:
$$x_2 = a - 1 + \sqrt{2 - a}.$$
Answer: at $a \leqslant 1$, $x = a$, $y = a + 1$, at
$$1 \leqslant a \leqslant 2, x = a - 1 + \sqrt{2 - a},$$
$$y = 2(a - 1) + 2\sqrt{a - 1},$$
for $a > 2$ there are no solutions.

However, the “format” solution is not always more labor-intensive. Otherwise it is more appropriate than graphic.

Problem 6 (MAI, 1971). For what real values ​​of $m$ the inequality
$$x^2 - 2mx + 2|x - m| + 2 < 0$$
has at least one solution?
Let us transform this inequality to the form
$$(x - m)^2 + 2|x - m| + 2 - m^2 < 0,$$
or
$$\begin{cases} y^2 + 2y + 2 - m^2 < 0, \\ y \geqslant 0, \end{cases}$$

⟦folio 48⟧

where $y = |x - m|$. System (11), (12) has at least one solution if and only if the discriminant of the left-hand side of (9) is non-negative and the larger root $y_2$ does not lie to the left of zero:

$$\begin{cases} m^2 - 1 \geq 0, \\ -1 + \sqrt{m^2 - 1} \geq 0, \\ m^2 \geq 1, \\ m^2 \geq 2. \end{cases}$$

that is, $\begin{cases} m^2 \geq 1, \\ m^2 \geq 2. \end{cases}$

Answer: $m \leq -\sqrt{2}, m \geq \sqrt{2}$.

So, we see that in a number of problems it is convenient to use a graphical representation of the quadratic trinomial. This approach may be useful for other addictions; it helps to discover a simpler and more meaningful solution path. However, all arguments regarding graphs can become part of the solution only if they are carried out in the most general form. In problems with parameters, you should be especially careful about the type of dependence, since for some values ​​of the parameters the appearance of the graph can change significantly (in example 2 we saw that at $m = -1$ the graph of a quadratic trinomial will not be a parabola, but a straight line). The use of graphs when solving a problem is not an end in itself, which is clearly confirmed by the last example. First of all, you need to carefully analyze all the features of a specific problem, think about the most rational use of its conditions - this can help you find the most convenient solution.

Exercises
1. (MAI, 1970). For what real values ​​of $a$ are the numbers 1 and $a$ contained between the numbers $x_1$ and $y_1$, where $(x_1, y_1)$ is the solution of the system

$$\begin{cases} x + y - 1 = 2a, \\ 2xy = a^2 - a. \end{cases}$$

2. (MAI, 1970). Find all real values ​​of $m$ for which the roots of the equation

$$x^2 - 2(m - 1)x + 2m + 1 = 0$$

there will be different signs and each modulo four.

3. (MAI, 1970). Find all real values ​​of $m$ for which the roots of the equation

$$(m - 1)\log_3^2(x - 2) - 2(m + 1)\log_3(x - 2) + m - 3 = 0$$

little three.

4. (MSU, Mechanics and Mathematics, 1971). Find all values ​​of $\alpha$ for which solutions of the system

$$\begin{cases} x^2 + 6x + 7 + \alpha \leq 0, \\ x^2 + 4x + 7 \leq 4\alpha. \end{cases}$$

form a closed interval (segment) of length equal to one.

5. (MSU, economics, cybernetics, 1971). Find the minimum term of a sequence

$$a_n = 2n^2 - 24n + 69 - \frac{9}{(3n - 22)^2 + 3}(n = 1, 2, 3, \dots)$$

6. (MSU, physicist, 1964). Find all real values ​​of $m$ for which the equality $mx^2 - 4x + 3m + 1 > 0$ is satisfied for all positive values ​​of $x$.

7. (MAI, 1971). Find all real values ​​of $a$ for which the equality $\frac{ax - a - \frac{1}{4}}{ax - 1} < 0$ is satisfied for all positive values ​​of $x > -2$.

8. (MSU, physicist, 1968). Find all values ​​of the parameter $a$ for which both roots of the square trinomial $x^2 - ax + 2$ are real and lie between 0 and 3 (excluding extreme values).

9. (MSU, physicist, 1965). Find all values ​​of $a$ for which the roots of the equation $x^2 + x + a = 0$ are greater than $a$.

10. (MSU, Mechanics and Mathematics, 1966). Find all values ​​of $a$ for which, for all $x$, the number modulo one does not exceed the equality $2x^2 - 4a^2x - a^2 + 1 > 0$.
