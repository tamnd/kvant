---
id: 1988-4-faddeev-nikulin-sokolovskiy-osnovnoy-printsip-differentsialnogo-ischisleniya-da08c5a2
issue: kvant_1988_4
year: 1988
number: "4"
title: Basic principle of differential calculus
authors:
  - Фаддеев Д. К.
  - Никулин М. С.
  - Соколовский И. Ф.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 50
page_last: 55
page_labels: 48-53
tag: 17SL
lang: en
source: kvant_digital
extraction: vision
content_sha256: dba2925f07ee28e02fe0c65354d09b1f6049dd9cb182e0243ba298c92690f021
prompt_sha256: draft-1
translated_from: content/ru/1988/04/articles/09_faddeev-nikulin-sokolovskiy-osnovnoy-printsip-differentsialnogo-ischisleniya-da08c5a2.md
source_content_sha256: a6098121b4de610ad39ec6e054cbec0291ea9ee38592fe9c1c853384ce0f508d
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

Basic principle of differential calculus

Part II:
Properties of arbitrary

Corresponding member of the USSR Academy of Sciences
D. K. FADDEYEV,
Candidate of Physical and Mathematical Sciences
M. S. NIKULIN,
I. F. SOKOLOVSKY

In our previous article (see «Kvant» No. 3) we talked about the basic principle of differential calculus. (In short, it is that the graph of a good function over a sufficiently small interval is almost no different from the graph of a linear function.) Then we studied in detail the properties of a linear function. In particular, we defined the instantaneous rate of change of a linear function as $k = \Delta y / \Delta x$, i.e., we took it to be equal to the average rate over any interval.

In the general case (i.e., for an arbitrary function), such a definition is unsuitable: the average speed for different intervals may not be the same. In general, we are faced with a contradiction in the fact that we are trying to talk about the “instantaneous value” of a quantity, which, in its physical meaning, can only be considered as a function of the interval. The correct definition of the concept of introducing the instantaneous rate of change of existence uses the formal mathematical apparatus of the passage to the limit.

Let us note, however, that the justification of the elements of analysis on the basis of the theory of limits was carried out by O. Cauchy only at the beginning of the 19th century, i.e., more than two thousand years after the appearance of some of the ideas underlying differential calculus, and 200 years after its creation by Newton and Leibniz. Mathematical analysis including

⟦folio 49⟧

Zinius, which included differential and integral calculus, was a leading and highly developed branch of mathematics at the time when its justification was given.

The application of the “basic principle” and the involvement of a linear function allows us to give a visual, intuitive clear definition of the concept of “instantaneous speed” in the general case, a minute of the theory of limits.

Here we come to the question of why the linear function occupies a special place in mathematics.

The point is, firstly, that everything related to the linear function, both in terms of the problems of studying the function, and in terms of the geometric and physical source of the results, is very simple and clear. It is this simplicity and clarity that has given the linear function a special role in mathematics in the study of the properties of those functions that are most often encountered in applications.

The second and most significant circumstance was noted in the first part of the article: to all elementary functions and to large functions, which we come to when studying the dependence between real quantities, we apply the “basic principle” of differential calculus.

In other words, when solving a certain range of problems, each of these functions of the fulfilled point can be replaced by a linear one, the graph of which is tangent to the graph of the function in question at the selected point. Since the most important properties of a linear function are determined by its slope, then by the slope of the tangent, i.e., by the value of an arbitrary function at a given point, one can judge the behavior of the function itself of the executed point.

We will not dwell here on the technical calculations of the arbitrary (assuming that the reader has some knowledge of it). We only note that (as shown in the article “On the tangent to the graph of a function”, see «Kvant», 1986, No. 3) for some functions the values ​​of an arbitrary function can be obtained based on essentially elementary messages.

Geometric and physical origin of an arbitrary $f'(x_0)$ from functions $f(x)$ at a given point $x_0$

In accordance with the “basic principle”, we consider the function $f(x)$ at point $x_0$ to be linear, and a small piece of the graph to coincide with the tangent segment at point $x_0$. Then $f'(x_0)$ shows how roundly the small piece of the graph of the function $f(x)$ containing the point $f(x_0)$ is tilted (and in which direction). In this state the geometric meaning is arbitrary.

For example, according to the table

| $x$ | 1 | 2 | 3 | 4 |
| :--- | :--- | :--- | :--- | :--- |
| $f(x)$ | 0,5 | 2 | 3 | 1,5 |
| $f'(x)$ | 1 | 2 | 0 | -2 |

we can plot not only the graph points themselves, but also small pieces of the graph containing table points (Fig. 1).

We know that in cases where a straight line is a graph of the relationship between two physical quantities, the slope of the straight line has a clear physical meaning. An arbitrary function (not linear) has the same physical meaning if this function describes the dependence between the same quantities. But only the numerical value $f'(x_0)$ of an arbitrary function $f(x)$ at the point $x_0$ can no longer be attributed to all functions as a whole, but only to a small neighborhood of the point $x_0$. For example, if function $T=f(t)$ describes the relationship between the temperature of a body and the time of its heating (Fig. 2), then $f'(t_0)$ is the rate of temperature change (heating rate) over a small time interval containing point $t_0$. Last statement

⟦folio 50⟧

Fig. 2.

the more accurate the integral containing the point $t_0$. Therefore, $f'(t_0)$ is called the heating rate at time $t_0$. Distracting from the specific physical content, we say that $f'(x_0)$ is the rate of change of function $f(x)$ at point $x_0$.

Approximate calculations

Theorem. The absolute error in calculating the value of a function is approximately equal to the absolute error in measuring the argument multiplied by the model value of the derivative at the corresponding point.

Proof. Indeed, $x_0$ is empty - an approximation of the value of the argument and $x$ - the unknown exact value of the argument; it is set to be close to $x_0$. We take the value $\Lambda x=x-x_0$ of the absolute error as a small argument. Considering (in accordance with the “basic principle”) the function $y(x)$ of the magnitude of the point $x_0$ to be linear with an angular coefficient $y'(x_0)$, we obtain, due to the characteristic property of a linear function (proven in the first part of the article), $\Lambda y=y'(x_0)\cdot \Delta x$, which is what we needed to prove.

It should be understood that the stated statement is valid under the assumption that the absolute error of the argument is indeed quite small for a given function.

If the value of the function $f(x)$ at the point $x_0$ is known and it is necessary to calculate the value $f(x)$ of the magnitude of the point $x_0$, then, based on the “basic principle”, one can replace the laborious calculations of the function with approximate calculations using the tangent equation at the point $x_0$. Exactly,

$$f(x) \approx f(x_0) + f'(x_0)(x-x_0).$$

Approximation is an increment of a function calculated “tangentially”, i.e.

$$f'(x_0)(x-x_0),$$

is called the differential of the function and is denoted by the symbol df. The increment of the argument $x-x_0$ is called the differential of the independent variable and is denoted by dx. Thus,

$$df=f'(x_0)dx.$$

In terms of differentials, the “basic principle” should be understood in such a way that the true increment of a “good” function on a small interval from the increment calculated “tangentially” is by a value inconvertibly small compared to df. Here it is necessary to note one important property of the differential: the difference $\Delta f$-df between the true increment of the function and its differential is not just much smaller than df - when dx decreases, this difference kills existence faster than dx. The exact meaning of the term “significantly faster” and the corresponding proof are possible only after a proper, more rigorous description of the initial concepts of the analysis.

We will limit ourselves to explaining the meaning of the terms “equally fast” and “substantially fast” using specific examples. The quantities related by the principle of proportional dependence change equally quickly, namely, a change in one by $n$ times leads to a change in the other also by $n$ times. Quantities associated, for example, with a quadratic relationship, change at different rates. Indeed, if $y=x^2$, then when $|x|$ decreases by 10 times, $y$ decreases by 100 times, when $|x|$ decreases by 100 times, $y$ decreases by 10,000 times, etc. In general, if $y=x^a$, where $a>1$, then when tending $|x|$ to zero $y$ kills existence faster than $|x|$. This is confirmed by the fact that the ratio $y/x=x^{a-1}$ approaches zero as $x$ tends to zero. The same can be said about the difference $\Lambda f-df$ - the ratio $(\Lambda f-df)/dx$ tends to zero as $dx$ tends to zero.

Two properties of differential - 1) differential function of proportional

⟦folio 51⟧

Fig. 3.

the difference between the true increment of a function and its differential decreases significantly faster than the differential argument - fully characterize the differential function and determine its most elementary, but most important applications in physics, technology, etc. The fact is that the differential (unlike an arbitrary one) is often visible “by eye” and can be found easier than an arbitrary one. After this, an arbitrary one can be calculated as a ratio of differentials: $df = f'(x_0)dx$,

$$f'(x_0) = \frac{df}{dx}.$$

Example 1. Compute $f'(0) = f'(x)|_{x=0}$ if $f(x) = x^3 - 3x^2 + 4x$.

Solution. Near $x=0$ the differential argument is equal to the argument $(dx=x)$ itself, and the increment of the function is equal to the value of the function. The part of the function increment proportional to $dx$ is the term $4x$, and the remaining terms containing $x$ decrease in magnitude much faster than $x$. So at point $x=0$ we have $df=4dx$, which means $f'(x)=4$.

Both differential properties are illustrated graphically Fig. 3). On this figure, the value $dx$ is chosen to be quite large, but “by eye” it is clear that as $dx$ decreases, the difference $\Delta f - df$ decreases significantly faster than $\Delta x$.

Differentiating a complex function

Based on the “basic principle” it is easy to obtain an expression for an arbitrary and differential complex function.

Let $F(x) = f(g(x))$. We consider the function $g(x)$ to be linear “in the small” magnitude of the point $x$, and the function $f(t)$ to be linear to the value of the point $t = g(x)$. Then, by virtue of the theorem on the composition of linear functions, proven in the first part of our article, $F(x)$ is a linear quantity $x$ and its angular coefficient is equal to the product of the angular coefficients of the function $g$ and $f$, i.e.

$$F'(x) = k_1 \cdot k_2, \quad \text{где } k_1 = f'(t)|_{t=g(x)} \quad \text{и } k_2 = g'(x).$$

For the differential of a complex function we obtain the expression

$$dF(x) = k_1 \cdot k_2 \cdot dx = \frac{f'(t)|_{t=g(x)}}{\cdot g'(x)}dx.$$

Since $g'(x)dx = dg(x)$, we get

$$dF(x) = f'(t)|_{t=g(x)} \cdot dg(x).$$

This important equality says that the form of writing the differential does not depend on what is under the sign of functions - an independent variable or a function of another variable. This property of a differential is called invariance. The differential invariance property makes it easier to technically differentiate complex functions.

Example 2. Find an arbitrary one from $F(x) = \sqrt{\sin(3x-1)}$, knowing that $(\sqrt{x})' = \frac{1}{2\sqrt{x}}$, $(\sin x)' = \cos x u (3x-1)' = 3$.

Solution:

$$dF(x) = (\sqrt{t})'|_{t=\sin(3x-1)} \cdot d\sin(3x-1) = \frac{1}{2\sqrt{\sin(3x-1)}}(\sin t)'|_{t=3x-1}d(3x-1) = \frac{1}{2\sqrt{\sin(3x-1)}} \cos(3x-1)3dx = \frac{3\cos(3x-1)}{2\sqrt{\sin(3x-1)}}dx.$$

Disclosure of Type 0/0 Uncertainty

It is often necessary to study the behavior of a point magnitude fraction in which the numerator and denominator become zero. Direct calculations using even high-precision computers can be a gross error in these cases due to the destruction of significant values.

⟦folio 52⟧

Fig. 4.

$$f(x)/g(x)$$ for values ​​of $x$ approaching $x_0$, if at this point the explorer and the substitute vanish. We consider $f(x)$ and $g(x)$ to be linear quantities of the point $x_0$, and replace small pieces of their graphs with tangents to the graphs of these functions at the point $x_0$. Thus, we believe that
$$f(x)=f'(x_0)(x-x_0), \quad g(x)=g'(x_0)(x-x_0).$$
Then, if $g'(x_0) \neq 0$, then
$$\frac{f(x)}{g(x)}=\frac{f'(x_0)(x-x_0)}{g'(x_0)(x-x_0)}=\frac{f'(x_0)}{g'(x_0)}.$$
We must remember that in fact this equality is an approximation, but the more accurate it is, the closer it is to $x_0$. We have obtained a rule known in mathematics as L'Hopital's rule for revealing uncertainty of the 0/0 type.

In the language of limits, this rule reads like this: the limit of the ratio $\frac{f(x)}{g(x)}$ at $x \rightarrow x_0$, if $f(x_0)=0$ and $g(x_0)=0$, is equal to the ratio of arbitrary $f'(x_0)$ and $g'(x_0)$:
$$\lim_{x \rightarrow x_0} \frac{f(x)}{g(x)}=\frac{f'(x_0)}{g'(x_0)} \quad (g'(x_0) \neq 0).$$

Example 3. Create a table of function values
$$f(x)=\frac{2x^2-x-\sin x/2}{\sqrt{x}-\cos(1-x)}$$
near point $x=1$.

Solution. The results of calculations on the V3-34 MK are shown in Table 1. Let us apply the Lopitania rule
$$\left(2x^2-x-\sin \frac{\pi}{2}x\right)' \bigg|_{x=1}=
= \left(4x-1-\frac{\pi}{2}\cos \frac{\pi}{2}x\right) \bigg|_{x=1}=4-1=3,
(\sqrt{x}-\cos(1-x))' \bigg|_{x=1}=$$

Numerical solution of differential equations

In many cases, it is possible to obtain a relationship between quantities containing their arbitrary values, i.e., in the form of a differential equation. It is not always possible to solve an equation, that is, to find a function that is a solution to a given differential

Table 1

| $0 x$ | 1,1 | 1,01 | 1,001 | 1,0001 | 1,00001 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| $f(x)$ | 6,1762693 | 6,0196529 | 6,0039984 | 6,012024 | 6,1224489 | 7,5 |

52

⟦folio 53⟧

Fig. 6.

central equation. However, based on the “basic principle”, it is possible to obtain an approximate (numerical) solution to the differential equation.

Example 4. Restore on the interval [0; 1] function according to the differential equation: $y'(t)=5t$ and the natural condition $y(0)=0$.

Solution. Let's create an arbitrary table of values:

Table 2

| $t$ | 0 | 0,1 | 0,2 | 0,3 | 0,4 | 0,5 | 0,6 | 0,7 | 0,8 | 0,9 | 1 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $y'(t)$ | 0 | 0,5 | 1 | 1,5 | 2 | 2,5 | 3 | 3,5 | 4 | 4,5 | 5 |

We assume that near the table points (according to the “basic principle”) the graph of the function is closely adjacent to the tangent segments. Dimension interval [0; 1] to part [0; 0.05]; [0.05; 0.15]; [0.15; 0.25], etc. up to [0.95; 1]. We will place the vertices of the broken line that replaces the function at the division points: 0; 0.05; 0.15; 0.25; ...; 0.95; 1.

Taking the angular coefficients of the broken line from the table, we obtain a graph (Fig. 5). Only part of the graph is built on this figure. Plot the entire graph yourself and make sure it matches well with the exact solution $y=2,5t^2$.

Determination of a portion of the curve, which is the graph of the function $y=f(x)$, on the interval [a; b]

figure 6 shows the graph of function $y=f(x)$. We need to find the length of part of the graph on the interval [a; b]. Let's consider the function $l(x)$, the value of which is equal to the length of the graph section from point $x=a$ to some $x$, $x\in[a; b]$.

Let us find the differential function $l(x)$ at the point $x$. Considering the function $f(x)$ “in the small” to be linear, we obtain

$$dl=\sqrt{(dx)^2+(dy)^2}=\sqrt{1+\left(\frac{dy}{dx}\right)^2}dx$$

$$=\sqrt{1+(f'(x))^2}dx,$$

where

$$l'(x)=\frac{dl}{dx}=\sqrt{1+(f'(x))^2}.$$

Obviously $l(a)=0$. We came to the well-known problem of restoring a function from its arbitrary (differential) and natural conditions. In terms of integral calculus, we need to calculate

$$\int_a^b \sqrt{1+(f'(x))^2}dx.$$

Note that it is precisely when solving the problem of calculating the length of a curve, even in seemingly simple cases, that we come to non-taking intervals, i.e., to integrals that are not expressed through elementary functions. For example, when calculating the length of a part of a sine wave, we obtain the equation $l'(x)=\sqrt{1+\cos^2x}$ or the integral

$$\int_a^b \sqrt{1+\cos^2x}dx.$$

Similarly, when calculating the length of the section of the hyperbola $y=1/x$, we obtain the equation $l'(x)=\sqrt{1+1/x^4}$ and the integral

$$\int_a^b \sqrt{1+1/x^4}dx.$$

Defeat. Construct a numerical solution to the last two differential equations using the method described in the article. Find the length of the sinusoid section on the interval [0; π/2] and the length of the hyperbola section on the interval [1; 2].

In conclusion, we note that the described ideas are developed in more detail in the book “Elements of Mathematics Computations for Schoolchildren” by the authors of this article (M.: “Nauka”, 1987). This book provides a fairly rigorous justification of the “main principle” and a more structured proof of theorems based on the concept of an infinitely small magnitude.
