---
id: 1987-11-bolibruh-uroev-shabunin-reshenie-sistem-trigonometricheskih-uravneniy-1fae2db9
issue: kvant_1987_11
year: 1987
number: "11"
title: Solving systems of trigonometric equations
authors:
  - Болибрух А. А.
  - Уроев В. М.
  - Шабунин М. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 51
page_labels: 46-49
tag: XXRY
lang: en
source: kvant_digital
extraction: vision
content_sha256: ebd141d557c70471913169cc977b572fcc8ce9d05bfac22c8f11fb11795785ba
prompt_sha256: draft-1
translated_from: content/ru/1987/11/articles/19_bolibruh-uroev-shabunin-reshenie-sistem-trigonometricheskih-uravneniy-1fae2db9.md
source_content_sha256: e91de4415ab15b8e3c218a33b9c2ab8949e4c282e7d086e5d075058bddb6fa34
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

Solving systems of trigonometric equations

Candidate of Physical and Mathematical Sciences
A. A. BOLIBRUKH,
Candidate of Physical and Mathematical Sciences
V. M. UROEV,
Professor M. I. SHABUNIN

In this note, using examples of problems proposed in different years of entrance exams at MIPT (written and oral), some methods for solving systems of trigonometric equations are given.

Let us recall the definitions that apply to any, not necessarily trigonometric, systems. If every solution of one system is a solution to another system, then the second system is called a “consequence” of the first. If the first system is a consequence of the second, and the second is a consequence of the first, then such systems are called equivalent.

Let us indicate some transformations of the system, as a result of which we obtain systems equivalent to the original one.

1. Any equation of the system can be replaced by an equivalent equation.

2. Any equation of the system can be replaced by an equation that is obtained by adding the given equation to another equation of the system.

3. The value of the unknown, found from some equation of the system, can be substituted into any other equation of the same system.

4. You can add an equation to the system that is a consequence of this system.

5. If a system contains the equation $f \cdot g = 0$, where the function $f$ and $g$ are defined on the same set, then it is equivalent to the collection of two systems, in one of which the equation $f \cdot g = 0$ is replaced by the equation $f = 0$, and in the other by the equation $g = 0$.

When starting to solve a system of trigonometric equations, it is advisable to first check whether it is possible to vaguely express one of the unknowns in terms of the others from any equation of the system.

Problem 1 (MIPT, 1983). Solve the system of equations
$$\begin{cases} tg x + tg y = 1 - tg x \cdot tg y, \\ \sin 2y - \sqrt{2} \sin x = 1. \end{cases}$$

Solution e. The underside system makes sense only in the case when the functions $tg x$ and $tg y$ are defined, i.e.

⟦folio 47⟧

there are conditions
$$\cos x \neq 0, \cos y \neq 0.$$ (3)

Let's look at the first equation. It would be natural to divide both parts by 1 - tg x · tg y and use the formula for the tangent of the sum. Then equation (1) could be rewritten as
$$\text{tg}(x + y) = 1;$$ (4)
but at the same time we can lose those solutions of system (1), (2), for which
$$1 - \text{tg} x \cdot \text{tg} y = 0.$$ (5)
However, it is easy to verify that system (1), (2), (5) has no solution. In fact, if there were solutions to this system, then from equation (1) it would follow that tan x + tan y = 0. But then equation (5) would take the form 1 + tan² y = 0, and therefore, it would have no solutions.

Thus, the original system under condition (3) is equivalent to system (2), (4).

From equation (4) we find x + y = π/4 + πn, i.e.
$$y = \pi/4 + \pi n - x, \ n \in \mathbb{Z}.$$ (6)
Now let’s substitute the expression found for y into equation (2) of the original system:
$$\sin(\pi/2 - 2x + 2\pi n) - \sqrt{2} \sin x = 1.$$
The resulting equation is reduced to the form sin x (2 sin x + √2) = 0, whence
a) sin x = 0, x = πm, m ∈ Z,
6) sin x = -√2/2,
x = (-1)^{k+1}π/4 + πk, k ∈ Z.
Using formula (6) we determine the corresponding values ​​of y. For series a)
$$y = \pi/4 + \pi(n - m), \ n, m \in \mathbb{Z};$$ (7)
for series 6)
$$y = \pi/4 - (-1)^{k+1}π/4 + π(n - k), \ n, k \in \mathbb{Z}.$$ (8)
The values ​​(x, y) from formula (7) satisfy conditions (3). Series (8) requires additional research. If sin x = -√2/2, then cos x ≠ 0, so the first inequality of equation (3) depends completely. The second inequality cos y ≠ 0 is not always satisfied.

If k is an even number, i.e. k = 2p, where p ∈ Z, then formula (8) gives y = π/2 + π(n - 2p). For these values ​​of y, condition (3) is not satisfied. If k is an odd number, i.e. k = 2p - 1, where p ∈ Z, then y = π(n - 2p + 1) and condition (3)
log. The corresponding values ​​of x are found using formula 6): x = -3π/4 + 2πp.
Answer: (πm; π/4 + π(n - m)), (-3π/4 + 2πp; π(n - 2p + 1)), m, n, p ∈ Z.

Integer parameters included in the record of system solutions cannot be denoted by one letter. This means that they are designated to take on the same values, while in reality they take on all the same values ​​- the same or different.

In what follows, k, l, m, n, p, r, s, t, unless otherwise stated, take all integer values.

Problem 2. Solve the system of equations
$$\begin{cases} \sin x \cdot \cos y = -1/2, \\ \cos x \cdot \sin y = 1/2. \end{cases}$$ (9)

Solution. Adding the equations of system (9), and then subtracting the first from the second equation, we obtain a system equivalent to system (9):
$$\begin{cases} \sin(x + y) = 0, \\ \sin(y - x) = 1, \end{cases}$$

where is sequentially located
x + y = πn, y - x = π/2 + 2πk,
x = π(n/2 - k - 1/4),
y = π(n/2 + k + 1/4).

Answer: (π(n/2 - k - 1/4); π(n/2 + k + 1/4)).

Just like system (9), you can solve any system of the form
$$\begin{cases} \sin x \cdot \sin y = a, \\ \cos x \cdot \cos y = b. \end{cases}$$

Such systems include, for example, systems
$$\begin{cases} \sin x \cdot \sin y = a, \\ \text{tg} x \cdot \text{tg} y = b, \\ \sin x \cdot \cos y = a, \\ \text{tg} x \cdot \text{ctg} y = b. \end{cases}$$

If a system contains only two combinations of trionometric functions or can be reduced to one, then by designating these combinations of functions as new unknowns, we can reduce the original system to an algebraic one.

Problem 3. Solve the system of equations
$$\begin{cases} \cos x - \sin x = 1 + \cos y - \sin y, \\ 3 \sin 2x - 2 \sin 2y = 3/4. \end{cases}$$ (10)

Solution. Let us use the identity
$$(\sin x - \cos x)^2 = 1 - \sin 2x$$ and denote

⟦folio 48⟧

cos x - sin x = u, cos y - sin y = v;
(11)

Then
sin 2x = 1 - u², sin 2y = 1 - v²,
and system (10) will be reduced to the algebraic system
$$\begin{cases} u = 1 + v, \\ 3u^2 - 2v^2 = 1/4. \end{cases}$$

System (12) has two solutions:
$$u_1 = -9/2, v_1 = -11/2 \text{ и } u_2 = 1/2, v_2 = -1/2.$$
Let us first consider the values ​​of $u_1, v_1$. Returning to the original variables, using formulas (11) we obtain:
$$\begin{cases} \cos x - \sin x = -9/2, \\ \cos y - \sin y = -11/2. \end{cases}$$

But the first equation of system (13) has no solutions, since cos x - sin x = $\sqrt{2}$ cos $(x + \pi/4)$ $\geqslant -\sqrt{2} > -9/2$.

Consequently, system (13) has no solutions.

Let us now consider the values ​​of $u_2$ and $v_2$. Again, using formulas (11), we obtain
$$\begin{cases} \cos x - \sin x = 1/2, \\ \cos y - \sin y = -1/2. \end{cases}$$

For the first equation we find
$$\cos x \cdot 1/\sqrt{2} - \sin x \cdot 1/\sqrt{2} = 1/2\sqrt{2}, \cos(x + \pi/4) = 1/2\sqrt{2}, x + \pi/4 = \pm \arccos(1/2\sqrt{2}) + 2\pi n, x = -\pi/4 \pm \arccos(1/2\sqrt{2}) + 2\pi n.$$
In exactly the same way we get
$$y = -\pi/4 \pm \arccos(-1/2\sqrt{2}) + 2\pi n.$$
Thus, we find the following solution to the original system:
$$(-\pi/4 \pm \arccos(1/2\sqrt{2}) + 2\pi n; -\pi/4 \pm \arccos(-1/2\sqrt{2}) + 2\pi n)$$
(signs are selected independently of each other).

In some cases, the system can be brought to the form
$$\begin{cases} \sin x = f(y), \\ \cos x = g(y), \end{cases}$$

whence, due to the main trionometric point $\sin^2 x + \cos^2 x = 1$, we obtain the equation $f^2(y) + g^2(y) = 1$, containing only one unknown.

If the system is reduced to the form
$$\begin{cases} \text{tg} x = f(y), \\ \text{ctg} x = g(y), \end{cases}$$

then the unknown $x$ is excluded by the variables of the equation: tg $x \cdot \text{ctg} x = 1$, whence $f(y) \cdot g(y) = 1$.

With such methods of solution, it is necessary to carefully monitor so as not to lose solutions and not to acquire extraneous solutions.

Problem 4 (MIPT, 1978). Solve the system of equations
$$\begin{cases} 4 \sin x - 2 \sin y = 3, \\ 2 \cos x - \cos y = 0. \end{cases}$$

Solution. System (15) can be reduced to form (14). Consequently, we obtain an equivalent system
$$\begin{cases} \sin x = 3/4 + 1/2 \cdot \sin y, \\ \cos x = 1/2 \cdot \cos y. \end{cases}$$

By squaring the equation of system (16) term by term and adding, we obtain an equation that is a consequence of system (16):
$$1 = \frac{9}{16} + \frac{3}{4} \sin y + \frac{1}{4} \cos^2 y,$$
or
$$\sin y = 1/4,$$

where
$$y = (-1)^n \arcsin 1/4 + \pi n.$$
From the first equation of system (16) taking into account (17) we find $x = 7/8$, $x = (-1)^m \arcsin 7/8 + \pi m.$

Since when solving system (15) the construction of a solution may appear (the squaring operation was used), it is necessary to make a selection by substituting the found values ​​(18), (19) into the second equation of this system.

It is easy to see that for even $m$ and $n$ in formulas (18), (19) the corresponding values ​​of cos $x$ and cos $y$ are positive, and for odd $m$ and $n$ these values ​​are negative. Thus, |cos $x| = \sqrt{1 - \sin^2 x} = \sqrt{15}/8, |\cos y| = \sqrt{15}/4$, so that to satisfy the second equation of system (16) it is only required that the values ​​of cos $x$ and cos $y$ coincide. From here we get
$$\begin{cases} x = \arcsin \frac{7}{8} + 2\pi k, \\ y = \arcsin \frac{1}{4} + 2\pi l, \end{cases}$$

$$x = -\arcsin \frac{7}{8} + (2k + 1)\pi,$$
$$y = -\arcsin \frac{1}{4} + (2l + 1)\pi.$$

Both obtained series (20) can be combined and the answer can be written in the following form.

⟦folio 49⟧

Answer:

$$((-1)^p \arcsin \frac{7}{8} + \pi p),$$
$$((-1)^p \arcsin \frac{1}{4} + \pi (p + 2r)).$$

When solving trigonometric systems, it is often difficult to take the first step, to find the “keys” to solving the problem. No general recommendations can be given here. We can only advise trying to apply such transformations of the system equation that lead to the appearance of trigonometric functions of one argument or at least do not increase the number of functions with different arguments.

Problem 5 (MIPT, 1982). Solve the equation system

$$\begin{cases}
3 \cos 3x = \sin (x + 2y), & (21) \\
3 \sin (2x + y) = -\cos 3y.
\end{cases}$$

Solution. If we express the terms of the equation in terms of the sines and cosines of the arguments $x$ and $y$, we get a rather complex system. Therefore, another solution should be chosen.

Note that the sum of the cosine arguments in the system equations, equal to $3x + 3y$, coincides with the sum of the sine arguments. Taking this into account, let’s re-arrange the equations of system (21) “crosswise”, i.e., multiply the left side of one equation by the right side of the other. We obtain equation $-\cos 3x \cos 3y = \sin (x + 2y) \sin (2x + y)$, (22) which is a consequence of system (21).

Let us note in equation (22) the product of trigonometric functions with the corresponding sums (differences); we obtain after applying similar cos $(x - y)$ + cos $(3x - 3y) = 0$, hence 2 cos $(x - y) \cdot \cos (2x - 2y) = 0$. This equation breaks down into two equations:

$$\cos (x - y) = 0, \quad (23)$$
$$\cos (2x - 2y) = 0. \quad (24)$$

Consequently, system (21) is equal to the totality of system (21), (23) and (21), (24).

a) From equation (23) it follows that $x = y + \pi/2 + \pi n$. (25)

Substituting $x$ from (25) into system (21), we obtain:

$$3 \cos (3y + 3\pi/2 + 3\pi n) = \sin (3y + \pi/2 + \pi n), \quad 3 \sin (3y + \pi + 2\pi n) = -\cos 3y.$$

Both equations of this system are reduced to the form 3 sin $3y = \cos 3y$, whence $y = \frac{1}{3} \arctg \frac{1}{3} + \frac{\pi m}{3}$. From (25) the corresponding values ​​of $x$ are found.

6) Let us now consider system (21), (24). From equation (24) we find $x = y + \pi/4 + \pi k/2$. Substituting this value in system (21), we obtain:

$$3 \cos (3y + 3\pi/4 + 3\pi k/2) = \sin (3y + \pi/4 + \pi k/2), \quad 3 \sin (3y + \pi/2 + \pi k) = -\cos 3y.$$

Next, we will use reduction formulas. From the second equation of system (26) it follows that $\cos 3y = 0$, i.e. $y = \pi/6 + \pi p/3$. Substituting this value into the first equation, we get

$$3 \cos (\pi p + \pi/2 + 3\pi/4 + 3\pi k/2) = \sin (\pi p + 3\pi/4 + \pi k/2), \quad \text{откуда } (3(-1)^k + 1) \sin (3\pi/4 + \pi k/2) = 0.$$

The last equality is not satisfied for any purpose $k$, therefore system (26) is inconsistent, and in case 6) there are no solutions.

Answer:

$$\left( \frac{1}{3} \arctg \frac{1}{3} + \frac{\pi}{2} + \frac{\pi m}{3} + \pi n; \frac{1}{3} \arctg \frac{1}{3} + \frac{\pi m}{3} \right).$$

Battles

Solve systems of equation:

1 (MIPT, 1982).

$$\begin{cases}
tg y - tg x = 1 + tg x \cdot tg y, \\
\cos 2 y + \sqrt{3} \cos 2x = -1.
\end{cases}$$

2 (MIPT, 1978).

$$\begin{cases}
6 \cos x + 4 \cos y = 5, \\
3 \sin x + 2 \sin y = 0.
\end{cases}$$

3 (MIPT, 1982).

$$\begin{cases}
2 \cos (3x + y) = \sin (x - y), \\
2 \sin (x + y) = \cos (3x - y).
\end{cases}$$

4 (MIPT, 1982).

$$\begin{cases}
\sin (2x + y) + \sin (2x - y) = \sqrt{2} \cos y, \\
tg (x + \pi/8) + \cos y = tg^2 y.
\end{cases}$$

5 (MIPT, 1981).

$$\begin{cases}
\cos 2y + 1/2 = (\cos y - 1/2) (1 + 2 \sin 2x), \\
\sin y (tg^3 x + ctg^3 x) = 3 ctg y.
\end{cases}$$

6 (MIPT, 1976).

$$\begin{cases}
\sin^2 x + \cos y \cdot \sin x = \cos 2y, \\
\cos 2x + \sin 2y = \sin^2 y + 3 \cos y \cdot \sin x.
\end{cases}$$

7 (MIPT, 1978).

$$\begin{cases}
\sqrt{1 + \sin x \cdot \sin y} = \cos x, \\
2 \sin x \cdot ctg y + 1 = 0.
\end{cases}$$

8 (MIPT, 1986).

$$\begin{cases}
tg x \cdot \sin y + 2 ctg x \cos y = \sqrt{5/2}, \\
2 ctg x \cdot \sin y - tg x \cdot \cos y = \sqrt{5/2}.
\end{cases}$$

9 (MIPT, 1982), Find all solutions to the system of equations

$$\begin{cases}
tg x \cdot \sin y + 2 ctg x \cdot \cos y = \sqrt{5/2}, \\
2 ctg x \cdot \sin y - tg x \cdot \cos y = \sqrt{5/2}.
\end{cases}$$
