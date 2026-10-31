---
id: 1975-9-ryizhkov-ionin-odnorodnyie-uravneniya-8f32e54e
issue: kvant_1975_9
year: 1975
number: "9"
title: Homogeneous equations
authors:
  - Рыжков Л. В.
  - Ионин Ю. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 51
page_last: 56
page_labels: 49-54
tag: TNVS
lang: en
source: kvant_digital
extraction: vision
content_sha256: b87cc60038e09f50f8e4e50d17757a1444858bbe7735abc72e078e9e6fc8a328
prompt_sha256: draft-1
translated_from: content/ru/1975/09/articles/14_ryizhkov-ionin-odnorodnyie-uravneniya-8f32e54e.md
source_content_sha256: 32b145a08622ecfa4ff2fd46ca5ad9ed08aed1f192ff89c5b059697f4b2c8959
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 49⟧

Homogeneous equations

In a school mathematics course, the concept of “homogeneous equation” (“homogeneous system of equations”) appears at least three times. Thus, when solving systems of linear equations, the system $^*$) was called homogeneous

$$\begin{cases} ax + by = 0, \\ cx + dy = 0. \end{cases}$$

When systems of second degree equations were considered, it was said that the system of equations

$$\begin{cases} 14x^2 - 5xy + 3y^2 = 16, \\ 6x^2 - xy + y^2 = 8 \end{cases}$$

is an equivalent system of equations, one of which is homogeneous, and the second is one of the equations of the original system $^*$). When solving trigonometric equations $^*$) the equations were called homogeneous

$$\sin x - \cos x = 0,$$

$$\sin^2 x - 5 \sin x \cos x + 6 \cos^2 x = 0.$$

What unites the above examples and the term “homogeneous equation” as a concept?

A polynomial $f(u, v)$ in two variables is called a homogeneous polynomial of degree $n$ if all of it is one-

$^*$) E. S. Kochetkov, E. S. Kochetkova. Algebra and the beginnings of analysis. M., “Enlightenment”, 1974, part 1, p. 54.

$^*$) Ibid., p. 142.

$^*$) Ibid., p. 281.

numerically we have degree $n$. For example,

$$f(u, v) = 2u^2 - 7uv + 9v^2$$

is a homogeneous polynomial of the second degree, and

$$f(u, v) = u^3 - 15u^2v + 5v^3$$

is a homogeneous polynomial of the third degree.

An equation $f(u, v) = 0$ is called a homogeneous equation of degree $k$ if $f(u, v)$ is a homogeneous polynomial of degree $k$.

Note that the concept of homogeneity also extends to equations with a large number of unknowns. For example, we will say that the equation $x^3 + 3x^2y + 3xyz + z^3 = 0$ is a homogeneous third-degree equation with respect to the unknowns $x, y$ and $z$.

Consider a homogeneous equation of $n$th degree with two unknowns $x$ and $y$:

$$f(x, y) \equiv a_0x^n + a_1x^{n-1}y + a_2x^{n-2}y^2 + \dots + a_ny^n = 0.$$ (1)

We will assume that $a_0 \neq 0$.

The case when $a_0 = 0$ is suitable for our consideration in the following way: if we take $y$ out of brackets in the smallest degree, then in brackets there will be a homogeneous polynomial with a non-zero leading coefficient. For example, the equation $x^4y^2 + 3xy^5 - 7y^6 = 0$ takes the form $y^2(x^4 - 3xy^3 - 7y^4) = 0$, after which the set of equations $y^2 = 0, x^4 + 3xy^3 - 7y^4 = 0$ remains considered an equation to the original equation.

Note that the pair $x = 0, y = 0$ is a solution to equation (1), but the pair $x = x_0, y = 0$ with $a_0 \neq 0, x_0 \neq 0$ is not a solution to equation (1)

⟦folio 50⟧

Is. Dividing both sides of equation (1) by $y^n$, we obtain an equation of $n$ degree with one unknown $t = x/y$:

$$a_0 t^n + a_1 t^{n-1} + \dots + a_{n-1} t + a_n = 0. \tag{2}$$

We will use this property of homogeneous equations when solving the problems below.

Let us find out what is the set of points on the plane whose coordinates $x, y$ satisfy equation (1). First of all, this set includes the origin $O(0, 0)$. Then, if $a_0 = 0$, then the solution $y = 0$ appears, defining the x-axis. And the roots $t_1, t_2, \dots, t_k$ of equation (2) determine the lines $x = t_1 y, x = t_2 y, \dots, x = t_h y$ passing through the origin of coordinates (for example, at figure 1 $t_1 = 1, t_2 = -1, t_3 = 2$).

Problem 1 (MSU, Faculty of Biology, 1967). A car leaves from point A to point B. However, a cyclist came straight towards her from point B. Three minutes after the meeting, the car makes a slight turn, follows the cyclist $u$, reaches him, turns again and arrives at point B. If the car made a slight turn 1 minute after the meeting, and the cyclist after the meeting reported a speed of 15/7 times, then the car would freeze for the entire road at the same time. Find the optimal speed of a bicycle and a car.

Let $x (km/min)$ be the speed of the car and $y (km/min)$ be the speed of the bicycle. Note that the movement from point A to the first meeting with the cyclist in the first and second cases takes the same time, and that the movement of the car from the place of the first meeting with the cyclist to point B also takes the same time in both cases. Therefore, the movement of the car takes the same time from the moment of the first meeting with the cyclist to the second passage of the place of their first meeting. Let's calculate this time in each case.

I. After meeting the cyclist, the car drove 3 minutes in the direction of point B. It will take another 3 minutes to get back to the meeting point. During this time, the cyclist will move 6 km away from the meeting point. The car will appreciate it at a speed of $(x-y) \cdot km/min$, which will cost it $\frac{6y}{x-y} \cdot min$. It will also take her $\frac{6y}{x-y} \cdot min$ to get back to the meeting place, but only $3+3+2 \cdot \frac{6y}{x-y} = \left(6 + \frac{12y}{x-y}\right) \cdot min$.

II. Wires similar alienation, we get

$$1 + 1 + \frac{2 \cdot \frac{15}{7} y}{x - \frac{15}{7} y} + \frac{2 \cdot \frac{15}{7} y}{x - \frac{15}{7} y} = \left(2 + \frac{60y}{7x - 15y}\right) \cdot min$$

Equating the found expressions, we obtain the equation

$$6 + \frac{12y}{x - y} = 2 + \frac{60y}{7x - 15y},$$

where

$$7x^2 - 16xy - 15y^2 = 0.$$

This is a homogeneous second degree equation with respect to $x$ and $y$. Polyag $t = x/y$ (the ratio of the speed of the car and the cyclist) and solving the equation $7t^2 - 16t - 15 = 0$, we find $t = 3$ (the negative root does not satisfy the conditions).

⟦folio 51⟧

In this problem we had one equation with two independent variables. This case is quite rare; usually in problems, variables are connected by some additional correspondences.

Task 2 (MISI). Solve the equation

$$20 \left( \frac{x-2}{x+1} \right)^2 - 5 \left( \frac{x+2}{x-1} \right)^2 + 48 \frac{x^2-4}{x^2-1} = 0.$$

Let us introduce new unknowns $u = \frac{x-2}{x+1}$, $v = \frac{x+2}{x-1}$. We obtain the equation $20u^2 - 5v^2 + 48uv = 0$, homogeneous of the second degree with respect to $u$ and $v$. Delim both of its parts by $v^2$ (it is easy to see that in the case of $u = v = 0$ there are no solutions) and set $\frac{u}{v} = t$. We obtain the equation $20t^2 + 48t - 5 = 0$ with roots $t_1 = -\frac{5}{2}$, $t_2 = \frac{1}{10}$.

In the first case $\frac{u}{v} = -\frac{5}{2}$; $\frac{x-2}{x+1} : \frac{x+2}{x-1} = -\frac{5}{2}$; $\frac{x^2-3x+2}{x^2+3x+2} = -\frac{5}{2}$; $7x^2 + 9x + 14 = 0$, this equation has no real roots.

In the second case $\frac{u}{v} = \frac{1}{10}$; $\frac{x^2-3x+2}{x^2+3x+2} = \frac{1}{10}$; $3x^2 - 11x + 6 = 0$; $x_1 = 3$; $x_2 = \frac{2}{3}$.

Task 3 (MISI). Solve the equation

$$2(x^2+x+1)^2 - 7(x-1)^2 = 13(x^3-1).$$

Let's put $u = x-1$, $v = x^2+x+1$. Then the equation will take the form $2v^2 - 7u^2 = 13uv$. In case $v = u = 0$ there are no solutions. Dividing both sides of the equation by $v^2$ and introducing a new unknown $t = \frac{u}{v}$, we obtain the equation $7t^2 + 13t - 2 = 0$ with roots $t_1 = 1/7$, $t_2 = -2$.

In the first case, $\frac{x-1}{x^2+x+1} = \frac{1}{7}$, $x^2 - 6x + 8 = 0$, $x_1 = 2$, $x_2 = 4$; in the second $\frac{x-1}{x^2+x+1} = -2$, $2x^2 + 3x + 1 = 0$, $x_3 = -1$, $x_4 = -\frac{1}{2}$.

Answer: $x_1 = 2$, $x_2 = 4$, $x_3 = -1$, $x_4 = -\frac{1}{2}$.

Task 4 (MISI). Solve the equation

$$x^2 + 2x + 15 = 2x\sqrt{2x+15}.$$

Let's introduce one more unknown $u = \sqrt{2x+15}$. We obtain a homogeneous equation $x^2 + u^2 = 2xu$. It can be solved as usual, or it can be represented in the form $(x-u)^2 = 0$, hence $x = u$. From equation $x = \sqrt{2x+15}$ it follows $x^2 - 2x - 15 = 0$, $x_1 = -3$, $x_2 = 5$. The value $x = -3$ does not satisfy equation (3), but $x = 5$ does.

Problem 5. Solve the equation

$$2\sqrt[3]{x+1} - \sqrt[3]{x-1} = \sqrt[6]{x^2-1}.$$

If we put $u = x+1$, $v = x-1$, we get an equation that could be called “homogeneous of degree 1/3” if there was a corresponding definition. In order not to deal with fractional steppes, we put

a) $u = \sqrt[6]{x+1}$, $u = \sqrt[6]{x-1}$, if $x \ge 1$;

b) $u = \sqrt[6]{-x-1}$, $v = \sqrt[6]{-x+1}$, if $x \leq -1$.

In the first case, we arrive at the equation $2u^2 - uv - v^2 = 0$, from which, by dividing by $v^2$, we find $\sqrt[6]{x+1} = 1$, $x+1 = x-1$, so that the original equation has no roots on the interval $x \ge 1$.

In the second case (at $x \leq -1$) we obtain the equation $-2u^2 - uv + v^2 =$

⟦folio 52⟧

= 0, whence $\sqrt[6]{\frac{x+1}{x-1}} = \frac{1}{2}$, $x = -\frac{65}{63}$.
Since $-\frac{65}{63} \leq -1$, this is the root of the original equation.

Problem 6. Solve the system of equations

$$\begin{cases}
3x^2 - 2xy - y^2 = 0, \\
x^2 + 5y = 6.
\end{cases}$$

The first equation of the system is homogeneous of degree 2. Dividing both its sides by $y^2$ (the case $y = x = 0$ is not a solution to the system) and setting $t = \frac{x}{y}$, we arrive at the quadratic equation $3t^2 - 2t - 1 = 0$, whence $t_1 = 1$, $t_2 = -\frac{1}{3}$. Thus, either $y = x$ or $y = -3x$. Substituting $y = x$ and then $y = -3x$ into the second equation of the system, we find its four solutions: $x_1 = y_1 = 1; x_2 = y_2 = -6$;

$$x_{3,4} = \frac{15 \mp \sqrt{249}}{2},$$
$$y_{3,4} = \frac{-45 \pm \sqrt{249}}{2}.$$

Problem 7. Solve the system of equations

$$\begin{cases}
3x^2 - \frac{25}{12}xy + 3y^2 = 50, \\
x^2 + y^2 = 25.
\end{cases}$$

This system is characterized by the fact that all terms containing unknowns have a second degree. To get rid of the free term, we multiply the second equation of the system by 2 and subtract it from the first. Consider a system of equations that consists of the resulting equation (it is homogeneous) and the second equation of the original system:

$$\begin{cases}
x^2 - \frac{25}{12}xy + y^2 = 0, \\
x^2 + y^2 = 25.
\end{cases}$$

System (5) is equivalent to system (4).

From the first equation of system (5), putting $t = \frac{x}{y}$, we find: $t_1 = \frac{3}{4}, t_2 = \frac{4}{3}$. Substituting $x = \frac{3}{4}y$ and $x = \frac{4}{3}y$ into the second equation of the system, we find four solutions: $x_{1,2} = \pm 3, y_{1,2} = \pm 4; x_{3,4} = \pm 4, y_{3,4} = \pm 3$.

The first equation of system (5) defines a pair of lines with equations $x = \frac{3}{4}y$ and $x = \frac{4}{3}y$, and the second is the equation of a circle with radius 5 and center at the origin. The solutions of the system will be the coordinates of the points of intersection of the lines with the circle (Fig. 2).

Problem 8 (MISI). Solve system of equations

$$\begin{cases}
2x^2 - 3xy + y^2 = 3, \\
x^2 + 2xy - 2y^2 = 6.
\end{cases}$$

Multiplying the first equation of the system by 2 and subtracting the second equation from it, we arrive at the system

$$\begin{cases}
3x^2 - 8xy + 4y^2 = 0, \\
x^2 + 2xy - 2y^2 = 6,
\end{cases}$$

in which the first equation is homogeneous, its solutions are $x = 2y$ and $x = \frac{2}{3}y$. Substituting them into the second equation of the system, we find two solutions: $x_{1,2} = \pm 2, y_{1,2} = \pm 1$.

Let us consider examples of trigonometric equations, the solutions of which can be reduced to the solution of homogeneous equations.

⟦folio 53⟧

Task 9. *Solve the equation*
$$2\sin x + 3\cos x = 0.$$

This equation is homogeneous of the first degree with respect to sin x and cos x. Divide both sides of the equation by cos x (it is easy to see that there is no loss of roots). We have:
$$2\mathrm{tg}x + 3 = 0, \quad \mathrm{tg}x = -\frac{3}{2}, \quad x = -\mathrm{arctg}\frac{3}{2} + \pi k \quad (k - \text{целое}).$$

The equation $a\sin^2x + b\sin x\cos x + c\cos^2x = 0$ is reduced to the form $a\mathrm{tg}^2x + b\mathrm{tg}x + c = 0$.

Task 10. *Solve the equation*
$$\sin^2x - 3\sin x\cos x + 2\cos^2x = 0.$$

When dividing the parts of the equation by $\cos^2x$ there will be no loss of roots, so we get the equation $\mathrm{tg}^2x - 3\mathrm{tg}x + 2 = 0$, from which $\mathrm{tg}x_1 = 1$, $x_1 = \frac{\pi}{4} + \pi k$; $\mathrm{tg}x_2 = 2$, $x_2 = \mathrm{arctg}2 + \pi m \quad (k, m - \text{целые}).$

The equation $a\sin x + b\cos x = c$ can be solved in many ways. It can be reduced to a homogeneous equation for sin $\frac{x}{2}$ and cos $\frac{x}{2}$ by substituting sin $x = 2\sin \frac{x}{2} \times \cos \frac{x}{2}$, cos $x = \cos^2\frac{x}{2} - \sin^2\frac{x}{2}$, $c = c\left(\cos^2\frac{x}{2} + \sin^2\frac{x}{2}\right)$.

Task 11. *Solve the equation*
$$3\sin x + 5\cos x = -3.$$

We have: $3\sin x + 5\cos x - 3, \quad \sin^2\frac{x}{2} - 3\sin \frac{x}{2}\cos \frac{x}{2} - 4\cos^2\frac{x}{2} = 0, \quad \mathrm{tg}^2\frac{x}{2} - 3\mathrm{tg}\frac{x}{2} - 4 = 0, \quad \mathrm{tg}\frac{x_1}{2} = -4, \quad x_1 = 2\mathrm{arctg}4 + 2\pi k; \quad \mathrm{tg}\frac{x_2}{2} = -1, \quad x_2 = -\frac{\pi}{2} + 2\pi m \quad (k, m - \text{целые}).$

Note that solving the equation $a\sin x + b\cos x = c$ by introducing an auxiliary argument is not always convenient. Solving, for example, equation (6) using this method, we obtain
$$3\sin x + 5\cos x$$

$$\sqrt{34}\left(\frac{3}{\sqrt{34}}\sin x + \frac{5}{\sqrt{34}}\cos x\right) =$$

$$= \sqrt{34}\sin \left[x + \arcsin \frac{5}{\sqrt{34}}\right],$$

$$\sin \left(x + \arcsin \frac{5}{\sqrt{34}}\right) = -\frac{3}{\sqrt{34}},$$

$$x = (-1)^{m+1}\arcsin \frac{3}{\sqrt{34}} -$$

$$- \arcsin \frac{5}{\sqrt{34}} + \pi m \quad (m - \text{целое}).$$

The idea of ​​using homogeneity when solving trigonometric equations is enriched by the ability to increase by 2 degrees of one-year relative to $u = \sin x$, $v = \cos x$ by multiplying them by $\sin^2x + \cos^2x$.

Task 12. *Solve the equation*
$$4\sin^3x = \sin x + \cos x.$$

Multiplying the right side of the equation by $\sin^2x + \cos^2x$ and then dividing both sides by $\cos^3x$, we arrive at the equation
$$3\mathrm{tg}^3x - \mathrm{tg}^2x - \mathrm{tg}x - 1 = 0.$$

Having guessed that when decomposing the left side into factors, one of them must equal $\mathrm{tg}x - 1$ (since $\mathrm{tg}x = 1$ satisfies the equation), we easily find this decomposition
$(\mathrm{tg}x - 1)(3\mathrm{tg}^2x + 2\mathrm{tg}x + 1) = 0$

and the answer: $x = \frac{\pi}{4} + \pi k \quad (k - \text{целое}).$

A successful substitution can also reduce some exponential equations to homogeneous equations.

Task 13 (MSU, Faculty of Chemistry, 1964). *Solve equation*
$$4^x = 2.14^x + 3.49^x.$$

Polyag $2^x = u, 7^x = v$, we arrive at a homogeneous second degree equation $u^2 - 2uv$ with respect to $u$ and $v$

⟦folio 54⟧

- 3v² = 0. Solving this equation, we find:

a) $\frac{u}{v} = -1, \left(\frac{2}{7}\right)^x = -1$ – decisive no;

6) $\frac{u}{v} = 3, \left(\frac{2}{7}\right)^x = 3, x = \log_{\frac{2}{7}} 3$.

Exercises

1 (MSU, mechanism, 1964). Solve equation $6\sqrt[3]{x-3} + \sqrt[3]{x-2} = 5\sqrt[6]{(x-2)(x-3)}$.

2 (NSU, 1970). Solve equation $5^{\log_2(x^2)} - 3^2\log_4(x^2/2) = \sqrt[3]{\log_2(\sqrt{2}/2)(2x^2)} - 5^{\log_2(x^2)} - 1$.

3 (UDN, 1971). Solve equation $(3 - 2\sqrt{2})^{x^2} - 6x + 9 + (3 + 2\sqrt{2})^{x^2} - 6x + 9 = 6$.

4 (MSU, Department of Geography, 1960). Solve equation $\sin 2x - \mathrm{tg} \frac{\pi}{6} \cos 2x = 1$.

5 (MSU, Faculty of Biology, 1966). Solve equation $2\sin 4x - 3\sin^2 2x = 1$.

6 (MSU, Faculty of Chemistry, 1964). Solve equation $3\cos^2 x - \sin^2 x - \sin 2x = 0$.

7. Solve system of equations

$$\begin{cases} x^2 + y\sqrt{xy} = 420, \\ y^2 + x\sqrt{xy} = 280. \end{cases}$$

8 (LPI, 1963). Solve system of equations

$$\begin{cases} \frac{x^2 + y^2}{xy} = \frac{5}{2}, \\ x^2 - y^2 = 3. \end{cases}$$

9 (POI, 1964). Solve equation $7.3^{x+1} - 5^{x+2} = 3^{x+4} - 5^{x+3}$.

10 (MSU, Department of Geography, 1967). Clean water begins to flow into the empty tank through two pipes at the same time and the constant water begins to flow. After filling
