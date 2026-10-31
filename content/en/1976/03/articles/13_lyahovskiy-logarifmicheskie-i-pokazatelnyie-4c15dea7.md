---
id: 1976-3-lyahovskiy-logarifmicheskie-i-pokazatelnyie-4c15dea7
issue: kvant_1976_3
year: 1976
number: "3"
title: Logarithmic and exponential...
authors:
  - Ляховский В. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 53
page_last: 59
page_labels: 51-57
tag: 9PON
lang: en
source: kvant_digital
extraction: vision
content_sha256: 876304b1399dcdd10d566ebc2282777eec8d08037e8849027e442f98e4ecfb44
prompt_sha256: draft-1
translated_from: content/ru/1976/03/articles/13_lyahovskiy-logarifmicheskie-i-pokazatelnyie-4c15dea7.md
source_content_sha256: 2e81988cde222178e973e38a7c313fb0694ff720c57c08b9ad878c31eb2567e7
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 51⟧

Logarithmic and exponential...

Most of the mathematics tasks offered at competitive university exams involve solving equations and inequalities.

For the simplest of them, for example, for quadratic equations and systems of linear equations, there are general methods for solving them. In most cases, there are no rules that allow solving an equation by sequentially performing arithmetic operations and elementary operations on the coefficients of the equation. Therefore, when studying, for example, exponential and logarithmic equations and inequalities, only partial solutions are considered.

Equations

When solving an equation, transformations of both sides of this equation are widely used.

About the limit 1. If all the roots of one equation are roots of another equation, then the second equation is called a consequence of the first.

About the limit 2. Two equations are called equivalent (equivalent) from some set of values ​​of the unknown if they have the same roots, with

belonging to this set, that is, if each of them is a consequence of the other.

It is natural to apply only such transformations in which each subsequent equation is equivalent to the previous one for the distance between them (below, unless otherwise stated, we mean the set of all real numbers). Then the solution to the last equation will also be the roots of the original equation.

However, this solution is not always possible. Otherwise, replace the equation with a non-equivalent consequence, and then check the roots to see if there are any constructed ones among them.

Let us first recall a few basic theorems.

Theorem 1. For $a > 0, a \neq 1$, equation $a^{f(x)} = a^{\varphi(x)}$ is equivalent to equation $f(x) = \varphi(x)$.

Theorem 2. For $a > 0, a \neq 1$ the equation $\log_a f(x) = \log_a \varphi(x)$ is equivalent to any of the systems

$$\begin{cases} f(x) = \varphi(x), \\ f(x) > 0, \\ \varphi(x) > 0. \end{cases}$$

Note that if the construction of roots appears only as a result of expanding the range of permissible values ​​(APV) of the unknown, then you can separate them from the roots of the original equation either by checking whether they are included in the APV, or by directly substituting them into the original equation or into an equation equivalent to the original one. If extra roots may appear not due to the expansion of the ODZ, then it is necessary to check by substituting into the original equation or into the intermediate equation in the solution of which these roots may appear.

Task 1 (Novosibirsk Institute of Railway Transport Engineers, 1974). Solve the equation

$$9\sqrt{x^2-2x}-x-1=2.$$

⟦folio 52⟧

Noticing that
$$9\sqrt{x^2-2x}-x=3^2(\sqrt{x^2-2x}-x),
3\sqrt{x^2-2x}-x-1=\frac{1}{3}\cdot 3\sqrt{x^2-2x}-x,
$$
putting $3\sqrt{x^2-2x}-x=t$, we obtain the equation $3t^2-7t-6=0$, which has roots $t_1=3$ and $t_2=-\frac{2}{3}$. The second root does not provide solutions to the original equation, since the range of the exponential function is the set of all positive numbers. Consequently, the original equation in the range of admissible values ​​of the unknown equivalent equation $3\sqrt{x^2-2x}-x=3^1$, and the latter, based on Theorem 1, to the irrational equation

Fig. 1.
Fig. 2.
Fig. 3.

$$\sqrt{x^2-2x}=x+1.$$

By squaring both sides, we find $x=-0,25$. Since when both sides of the equation are raised to an even power, extraneous roots may appear, verification is necessary, and only at this stage. Substituting the found value of $x$ into the irrational equation shows that it satisfies it and, therefore, the original equation.

In most random cases, the main difficulty in solving a logarithmic or exponential equation is to transform the original equation until it becomes possible to apply Theorems 1 or 2. But in doing so, one must carefully monitor the change in the ODZ. Missing this point often leads to errors in decision making.

So, using, for example, logarithm formulas
$$\log_a xy=\log_a x+\log_a y,$$
$$\log_a \frac{x}{y}=\log_a x-\log_a y,$$
$$\log_a x^p=p\log_a x,$$
applicants often forget that the ODZ of their left and right sides do not coincide.

Indeed, the matching parts rules (1) and (2) are defined for the values ​​$x>0$ and $y>0$. This inequality is satisfied by the coordinates of the point filling the first coordinate angle (Fig. 1). At the same time, the left-hand sides of the correspondence (1) and (2) make sense when the signs $x$ and $y$ coincide.

Consequently, when moving, for example, from the expression $\log_a xy$ to the expression $\log_a x+\log_a y$, the ODZ exists (at the third coordinate angle), and this can lead to a loss of solutions.

The right-hand side of equality (3) is defined only for $x>0$, and the ODZ of the left-hand side depends on the exponent $p$. If $p$ is an integer, then the left side of equality (3) also makes sense for negative $x$. Therefore, moving from the expression $\log_a x^p$ to the expression $p\log_a x$ can also lead to a loss of solutions.

⟦folio 53⟧

The best examples of logarithm formulas are in this form:

$$\log_a xy = \log_a |x| + \log_a |y|,$$
(1a)
$$\log_a \frac{x}{y} = \log_a |x| - \log_a |y|,$$
(2a)

$$\log_a x^p = p \log_a |x| (p - \text{четное}).$$
(3a)

Now the right-hand sides of formulas (1a) and (2a) are defined at $x \neq 0$ and $y \neq 0$. These conditions are satisfied by all points of the coordinate plane, with the exception of points lying on the axes (Fig. 3), and when moving from the expression $\log_a xy$ to the expression $\log_a |x| + \log_a |y|$ the ODZ of unknowns does not exist, but expands (compare Fig. 2 and Fig. 3). The possibility of losing the solution is excluded, but the construction of roots may appear. And in equality (3a) the ODZ of the right and left sides coincide: $x \neq 0$.

The second way to avoid changing the ODZ is to move from one equation to an equivalent system or set of equations (inequalities). Thus, the equation $\log_a \frac{x}{y} = c$ is equivalent to the set of equations $\log_a x - \log_a y = c$, $\log_a (-x) - \log_a (-y) = c$.

Problem 2. Solve the equation

$$\lg (x + 10) + \frac{1}{2} \lg x^2 = 2 - \lg 4.$$

Unknown's ODZ: $x > -10, x \neq 0$. Since $\frac{1}{2} \lg x^2 = \lg |x|$, we reduce the equation to the form $\lg (x + 10) + \lg |x| + \lg 4 = 2$, whence $\lg [4 |x| (x + 10)] = \lg 100$. By Theorem 2, the last equation is equivalent to:

$$4 |x| (x + 10) = 100$$

(since $100 > 0$, the inequality holds). Considering two cases and solving the corresponding equations:

a) $x > 0, x^2 + 10x - 25 = 0$,
b) $-10 < x < 0, x^2 + 10x + 25 = 0$, we find two roots: $x_1 = -5 + 5\sqrt{2}, x_2 = -5$.

Often the solution to an equation or system of equations can be simplified by introducing new variables.

Task 3 (Plant-technical college at ZIL, 1974). Solve the equation

$$\left( \sqrt{7 + \sqrt{48}} \right)^x + \left( \sqrt{7 - \sqrt{48}} \right)^x = 14.$$

Let's denote $\left( \sqrt{7 + \sqrt{48}} \right)^x = u$, $\left( \sqrt{7 - \sqrt{48}} \right)^x = v$. Then the system

$$\left\{ \begin{array}{l} u + v = 14, \\ uv = 1 \end{array} \right.$$

at $u > 0, v > 0$ will be equivalent to the original equation. Her solution:

$$u_1 = 7 + \sqrt{48}, v_1 = 7 - \sqrt{48};$$
$$u_2 = 7 - \sqrt{48}, v_2 = 7 + \sqrt{48}.$$

Let's write $u_2$ and $v_2$ in this form: $u_2 = (7 + \sqrt{48})^{-1}, v_2 = (7 - \sqrt{48})^{-1}$. Returning to the original variable, we find $x_1 = 2, x_2 = -2$.

An equation of the form $[f(x)]^{\phi(x)} = [g(x)]^{h(x)}$ is usually solved using Theorem 2 of taking the logarithm of the equation to some base.

Problem 4 (Moscow Geological Institute, 1975). Solve the equation

$$x^{\lg^2 x^2 - 3\lg x - 4,5} = 10^{-2\lg x}.$$

Unknown's ODZ: $x > 0$. With this in mind, the original equation is equivalent to the equation

$$\lg \left( x^{\lg^2 x^2 - 3\lg x - 4,5} \right) = \lg \left( 10^{-2\lg x} \right),$$

which by substitution $\lg x = t$ coincides with the cubic: $t (8t^2 - 6t - 5) = 0$ with roots $t_1 = 0, t_2 = 1, 25$ and $t_3 = -0, 5$. Returning to the original variable, we find: $x_1 = 1, x_2 = 10\sqrt[4]{10}$ and $x_3 = \sqrt[10]{10}$.

Problem 5 (Novosibirsk State University, 1974). Solve system of equations

$$\left\{ \begin{array}{l} (x + y)^{\frac{1}{x-y}} = 2\sqrt{3}, \\ (x + y) \cdot 2^{y-x} = 3. \end{array} \right.$$

⟦folio 54⟧

From the second equation it follows that $x + y > 0$. Therefore, continuing to rhyme in base 2 and putting $\log_2(x + y) = u$, $x - y = v$, we get the system
$$\begin{cases} \frac{u}{v} = 1 + 0, 5 \log_2 3, \\ u - v = \log_2 3, \end{cases}$$

equivalent on the set $x + y > 0$ to the original one. Substituting the value of $u$ from the first equation into the second, we find $v = 2$ and then $u = \log_2 12$. Returning to the original variables and potentiating, we get
$$\begin{cases} x - y = 2, \\ x + y = 12, \end{cases}$$

whence $x = 7$, $y = 5$.

Note that the use of the main logarithmic identity $a^{\log_a f(x)} = f(x)$ during the solution can lead to the appearance of constructed solutions due to the expansion of the ODZ.

Problem 6 (MIPT, 1975). Solve the equation
$$9^{\log_3(1 - 2x)} = 5x^2 - 5$$.

Let's transform the left side of the equation, taking into account the basic logarithmic identities and properties of the degree: $9^{\log_3(1 - 2x)} = (3^2)^{\log_3(1 - 2x)} = [3^{\log_3(1 - 2x)}]^2 = (1 - 2x)^2$. Equation $(1 - 2x)^2 = 5x^2 - 5$ is a consequence that is not equivalent to the original equation. Indeed, its first root $x_1 = -2 - \sqrt{10}$ satisfies the original equation, since it is included in the ODZ, and the constructed second root $x_2 = -2 + \sqrt{10}$ appears as a consequence of expanding the ODZ when replacing the expression $9^{\log_3(1 - 2x)}$, which makes sense at $x < 0,5$, with the expression $(1 - 2x)^2$, defined for any value of the argument.

Problem 7 (MIPT, 1974; MAI, 1975). Solve the equation
$$\log_3(\log_2 x - 9) = 2 + \log_3(1 - 4 \log_2 x)$$.

Since $2 + \log_3(1 - 4 \log_2 x) = \log_3[9(1 - 4 \log_2 x)]$, then by theory
Rem 2 the original inequality is equivalent to the system
$$\begin{cases} \log_2 x - 9 = 9(1 - 4 \log_2 x), \\ \log_2 x - 9 > 0. \end{cases}$$

Since $\log_2 x = t$, we obtain the system
$$\begin{cases} t^2 - 18t + 72 = 0, \\ t > 9, \end{cases}$$

whose solution is $t = 12$, hence $x = 4096$. Note that if we restrict the equation from a mixed system without inequality, then the constructed root $x = 64$ will appear.

Problem 8 (MSU, Department of Geography, 1972; plant-technical college at ZIL, 1974). Solve system equation
$$\begin{cases} 2\log_4 x^2 + \log_0.2 y^3 = -1, \\ 2\log_4 x^4 - \log_0.2 y = 5. \end{cases}$$

In the region of admissible values ​​of the unknowns, determined by the condition $x \neq 0$ and $y > 0$, this system is equivalent to the system
$$\begin{cases} 4\log_4 |x| + 3\log_0.2 y = -1, \\ 8\log_4 |x| - \log_0.2 y = 5, \end{cases}$$

linear relative $\log_4 |x|$ and $\log_0.2 y$. This system has a unique solution $\log_4 |x| = 0,5$, $\log_0.2 y = -1$, hence $x = \pm 2$, $y = 5$. If we omit the signs of the model, then the solution (-2; 5) will be lost when taking logarithms.

Sometimes it is useful to use the formula $b^{\log_a c} = c^{\log_a b}$, which is valid for positive $a$, $b$ and $c$ and for $a \neq 1$. Really,
$b^{\log_a c} = (a^{\log_a b})^{\log_a c} = (a^{\log_a c})^{\log_a b} = c^{\log_a b}$

Problem 9 (Moscow Mining Institute, 1975). Solve the equation
$$5^{\lg x} = 50 - x^{\lg 5}$$.

Let's find the ODZ: $x > 0$. Based on the considered formula $x^{\lg 5} = 5^{\lg x}$, therefore the original equation is equal to the solo equation $2 \cdot 5^{\lg x} = 50$, whence $5^{\lg x} = 5^2$, $\lg x = 2$, $x = 100$.

⟦folio 55⟧

Exponential and logarithmic equations can also appear when solving “test” problems.

Problem 10 (Moscow Institute of Electronic Technology, 1975). Find $x$ and $y$ if it is known that $xy$, $x^x$ and $\frac{1}{y}$ are successive terms of a geometric process, $a$ log$_x(y+1)$, $-0.5$ and $\log_x(2-y)$ are an arithmetic process.

The problem condition can be written in the form
$$\begin{cases} x^{2x} = xy \cdot \frac{1}{y}, \\ \log_x(y+1) + \log_x(2-y) = -1. \end{cases}$$

Find your own solution to this system. Answer: $x = 0,5$; $y = 1$.

Task 11 (LSU, Faculty of Psychology, 1970). Solve the equation
$$\log_{\sqrt{2-x^2}}(2x^2+a) = 4.$$

This is an equation with a parameter. To solve it means to indicate at what values ​​of the parameter a solution exists and what they are. When solving such equations, checking the equivalence of the equation plays a particularly important role, since verification is usually difficult.

Putting $x^2 = t$, we reduce the equation to the form
$$\log_{\sqrt{2-t}}(2t+a) = 4.$$

The last equation is equivalent to the original one (subject to the change $x^2 = t$) for $t \geq 0$. In the ODZ, we define the correspondences $2-t > 0$, $2-t \neq 1$, $2t+a > 0$, it is equivalent to the equation $2t+a=(2-t)^2$, which has roots $t_1=3+\sqrt{5+a}$, $t_2=3-\sqrt{5+a}$. These roots exist at $a \geq -5$. The root $t_1$ is not included in the ODZ at any $a$, and the root $t_2$ is included at $-4 < a < -1$ and $a > -1$. Inequality $t_2 \geq 0$ holds for $a \leq 4$ (check!). Returning to the original variable, we get:
$$x = \pm \sqrt{3-\sqrt{5+a}}$$

at $-4 < a < -1$, $-1 < a \leq 4$; for the remaining $a$ there are no solutions.

Inequalities

The basic definitions needed to solve inequalities are almost the same as the corresponding definitions for an equation. Everything said above about transformations that change ODZ is also true for inequalities. However, solving inequalities has its own characteristics and requires good knowledge of the properties of the functions included in them. In particular, it must be remembered that the properties of the exponential and logarithmic functions are different for bases greater or less than one: for $a > 1$ the functions $y = a^x$ and $y = \log_a x$ increase monotonically, and for $0 < a < 1$ the functions $y = a^x$ and $y = \log_a x$ decrease monotonically.

Important theorems follow from these properties.

Theorem 3. The inequality $a^{f(x)} < a^{\varphi(x)}$ for $0 < a < 1$ is equivalent to the inequality $f(x) > \varphi(x)$, and for $a > 1$ to the inequality $f(x) < \varphi(x)$.

Theorem 4. The inequality $\log_a f(x) < \log_a \varphi(x)$ for $0 < a < 1$ is equivalent to the system of inequalities
$$\begin{cases} f(x) > \varphi(x), \\ \varphi(x) > 0, \\ a \neq 1 \text{ и } a > 1 \end{cases}$$

Inequalities of the form $\log_a f(x) > c$ and $a^{f(x)} > d$ ($d > 0$); together > can stand $\leq$, <, <=) can be brought to the form considered in Theorems 3 and 4 using the formulas $c = \log_a a^c$ and $d = a^{\log_a d}$.

Problem 12 (Moscow Textile Institute, 1974). Solve inequality
$$3^{2x+5} \leq 3^{x+2} + 2.$$

Note that $3^{2x+5} = 3 \cdot 3^{2(x+2)}$. By putting $3^{x+2} = t(t > 0)$, reception to

⟦folio 56⟧

inequality $3t^2 - t - 2 \leqslant 0$. It satisfies for $-\frac{2}{3} \leqslant t \leqslant 1$. The inequality $3x^2 \geqslant -\frac{2}{3}$ is valid for any real $x$. Let us represent 1 as $3^0$, then from the inequality $3x^2 \leqslant 3^0$ by Theorem 3 we find $x \leqslant -2$.

When solving exponential and logarithmic inequalities, the method of integrals is often used.

Problem 13 (Moscow Mining Institute, 1975). Solve inequality
$$\log_2^4 x - \log_0.5^2 \frac{x^3}{8} + 9 \log_2 \frac{32}{x^2} <
< 4\log_0.5^2 x.$$
The ODZ of the inequality has the form $x > 0$. Note that in ODZ
$$\log_0.5 \frac{x^3}{8} = \log_2 \frac{8}{x^3} = 3(1 - \log_2 x),$$
$$\log_2 \frac{32}{x^2} = 5 - 2\log_2 x,$$
$$\log_0.5 x = -\log_2 x,$$
Posically the original inequality is equivalent to the following:
$$\log_2^4 x - 13 \log_2^2 x + 36 < 0.$$
Putting $\log_2 x = t$, after factoring we obtain the inequality $(t + 3)(t + 2)(t - 2)(t - 3) < 0$. His solution (see Fig.4): $-3 < t < -2$, $2 < t < 3$. Let's return to the original variable: $-3 < \log_2 x < -2$, $2 < \log_2 x < 3$, from where: $0,125 < x < 0,25$ and $4 < x < 8$.

Problem 14 (Moscow Institute of Electronic Engineering, 1974). Solve inequality
$$0,3^{\log_0.25 \log_2 \frac{3x+6}{x^2+2}} > 1.$$
By Theorem 3, this inequality
$$\log_0.25 \log_2 \frac{3x+6}{x^2+2} < 0,$$
and the last one to the inequality $\log_2 \frac{3x+6}{x^2+2} > 1$, whence $\frac{3x+6}{x^2+2} > 2$. Multiplying both sides by $x^2 + 2$ (this expression is positive for any real $x$), we get $2x^2 - 3x - 2 < 0$ or $2(x+0,5)(x-2) < 0$, hence $-0,5 < x < 2$.

When solving inequalities that contain parameters or unknowns in the base of the logarithm or power, it is necessary to separately consider the integrals $(0; 1)$ and $(1; +\infty)$ of the base values.

Problem 15 (Moscow Institute of Geodesy, Aerial Photography and Cartography Engineers, 1975). Solve inequality
$$(x^2 - x + 2)^{\log_0.6 \frac{2x-3}{x+1}} > 1.$$
Since the base of degree $x^2 - x + 2$ is positive for any real value $x$ (check!), this inequality is equivalent to the totality of the system
$$\left\{ \begin{array}{l l} x^2 - x + 2 < 1, \\ \log_0.6 \frac{2x-3}{x+1} < 0, \\ \log_0.6 \frac{2x-3}{x+1} > 0. \end{array} \right.$$
On the set of all real numbers, the inequality $x^2 - x + 2 < 1$ has no solutions, and the inequality $x^2 - x + 2 > 1$ satisfies for any $x$ (prove it!). Therefore, the system has no solution, and the second inequality
$$\log_0.6 \frac{2x-3}{x+1} > 0, \text{ т. е. } 0 < \frac{2x-3}{x+1} < 1.$$

Fig. 5.

⟦folio 57⟧

Transforming these inequalities into the system
$$\begin{cases} (x+1)(x-1,5)>0, \\ (x+1)(x-4)<0, \end{cases}$$

Let's solve it by the method of integrals (Fig. 5). Answer: $1.5<x<4$.

In conclusion, consider the solution to the inequality with a parameter.
Problem 16 (MNET, 1975). Find all values ​​of the parameter $a$ for which the inequality
$$\log_{a+x}[x(a-x)]<\log_{a+x}x$$
has at least one solution.

In the region of permissible values ​​of the unknown $x$ and the parameter $a$, we define the condition $x>0, a+x>0, a-x>0, a+x\neq1$, the inequality is equivalent to the following: $$\log_{a+x}(a-x)<0.$$

The following inequality, taking into account the ODZ, is equivalent to a set of two systems of inequalities:

$$\begin{cases} x>0, \\ x>-a, \\ x<a, \\ a+x>1, \\ a-x<1, \end{cases}$$

Let us draw the lines $x=0, x=-a, x=a, x=1-a$ and $x=a-1$ in the rectilinear coordinate system (Fig. 6). Each straight line divides the coordinate plane into two half-planes, in one of which the corresponding inequality is satisfied, and in the other half-plane and on the straight line itself it is not satisfied. Ouch-
