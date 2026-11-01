---
id: 1978-8-bashmakov-diofantovyi-uravneniya-i-ratsionalnyie-tochki-c8986776
issue: kvant_1978_8
year: 1978
number: "8"
title: Diophantine equations and rational points
authors:
  - Башмаков М. И.
rubric: osnovnye-stati
page_first: 4
page_last: 9
page_labels: 2, 4, 5, 6, 7
tag: 2VOJ
lang: en
source: kvant_digital
extraction: vision
content_sha256: e0a0bf01e955683f9e3ccea07cf4064a8bc792be8b3fa8566c771c4bbb95fb45
prompt_sha256: draft-1
translated_from: content/ru/1978/08/articles/03_bashmakov-diofantovyi-uravneniya-i-ratsionalnyie-tochki-c8986776.md
source_content_sha256: c9d8ded41b15fbe1911d1cd32c5e9f9d4553171779031e11095a4f623e3bac96
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

Diophantovs
equations
and rational
points

The field of number theory that studies integer solutions to an equation of the form $P(x, y, \dots) = 0$, where $P(x, y, \dots)$ is a polynomial in several variables with integer coefficients, is called Diophantine analysis, and these equations themselves are called Diophantine.

They are named after the famous Greek mathematician Diophantus, who lived in the 3rd century and wrote the first treatise on such equations.

Despite the fact that Diophantine equations constitute one of the oldest areas of mathematics,

General methods for solving them have only recently emerged. In classical works, linear and quadratic Diophantine equations were mainly considered. The solution of more complex equations has greatly advanced in the last 20-25 years due to the widespread involvement in number theory from other areas of mathematics, primarily from geometry and topology. In the words of N. Bourbaki, “...classical geometry...was turning into a universal language of all mathematics, possessing exceptional flexibility and convenience.” Geometry offers not only language, but also its constructions, its intuition.

Look how clear the geometric language is. Take, for example, Fermat's equation $x^n + y^n = z^n$, divide both sides by $z^n$ and denote $x/z$ by $u, y/z$ by $v$. We obtain the equation $u^n + v^n = 1$. Each solution of the $(x; y; z)$ equation of Fermat in number terms corresponds (at $z \neq 0$) to a solution of the $u^n + v^n = 1$ equation in rational numbers.

If we now consider the graph of this equation on the $(u, v)$ plane,

⟦folio 4⟧

Let us now consider a curve defined by a third-degree equation, which also turns out to be rational. This is the $y^2=x^3-x^2$ curve. It is depicted in figure 3 and consists of an isolated point $O$ and a branch symmetrical to the relative axis $x$.

Task 3. Justify figure 3.

Let us draw through the point $O$ all possible lines $y=tx$. The values ​​of the angular coefficient $t$ can be plotted on the axis $t$ drawn through the point $(1, 0)$ (Fig. 4). Substituting $y=tx$ into the equation of the curve and canceling by $x^2$ (we lose the singular point $O!$), we obtain the parameterization

$$\begin{cases} x=t^2+1, \\ y=t(t^2+1), \end{cases}$$

at which the rational value $t$ corresponds to the rational points of the curve $y^2=x^3-x^2$.

Task 4. Form and prove the converse statement.

So, it is possible to establish a one-to-one correspondence between the rational points of the curve $y^2=x^3-x^2$ (without the point $(0, 0$)) and the line $t$. Geometrically, they represent the central design depicted in figure4.

Similarly, one can find a rational parametrization of the curve $y^2=x^3+x^2$:

$$x=t^2-1, y=t(t^2-1).$$

Problem 5. Construct this curve and prove that if the correspondence $(t_1-1)(t_2-1)(t_3-1)=(t_1+1)(t_2+1)(t_3+1)$ is satisfied for the values ​​of the parameter $t_1, t_2$, then the three corresponding points lie on the same straight line.

So, for each of the rational curves we have considered, we can specify a mapping of a line on the curve in which the rational points of the curve correspond to the rational points of the line. In fact, this statement is also true for an arbitrary rational curve; we obtain the equation from Diophantus.

Questions arise: are there irrational curves? How to describe all rational curves? The answer to these questions is known. For example, all curves of the first and second degree are rational. There are rational

⟦folio 5⟧

Fig. 6.

curves of any degree, but all such curves of degree greater than two have a singularity—points of self-intersection, points of self-tangency, etc. (Fig. 5).

For $n > 2$ the Fermat curve $u^n + v^n = 1$ is not rational. Prove that this is equivalent to the statement that Fermat's equation $x^n + y^n = z^n$ has no solutions among polynomials $x(t), y(t), z(t)$ of degree at least one. (This fact was proven in the article by B. Martynov “Fermat’s Theorem for Polynomials” («Kvant», 1976, No. 8).)

We will again show the second one using the example of a circle. Let's take two rational points on the circle - for example, $P_1$ (3/5, 4/5) and $P_2$ (5/13, 12/13). Let $\alpha_1$ and $\alpha_2$ be the angles corresponding to points $P_1$ and $P_2$. The point corresponding to angle $\alpha_1 + \alpha_2$ will also be rational, since

$$\cos(\alpha_1 + \alpha_2) = \cos \alpha_1 \cos \alpha_2 - \sin \alpha_1 \sin \alpha_2, \sin(\alpha_1 + \alpha_2) = \sin \alpha_1 \cos \alpha_2 + \cos \alpha_1 \sin \alpha_2.$$

Thus, we can “add” rational points on a circle using the formula $(u_1; v_1) \oplus (u_2; v_2) = (u_1 u_2 - v_1 v_2; u_1 v_2 + u_2 v_1)$ and obtain new rational points. This property of a circle underlies many beautiful problems.

Task 6. a) Let $P_1$ be a rational point of the circle corresponding to some angle $\alpha$. Prove that the points $P_n$ corresponding to the angles $n \in \mathbb{Z}$ are also rational.

b) Prove that the pairwise distances between the points constructed in part a) are rational.

c) Construct $n$ points on the plane, the lower three of which do not lie on the same line and the pairwise distances between them are integers.

It turns out that there are also curves with the following property: points on them can be “added”, and the “sum” of rational points is a rational point. For such curves, it is sometimes possible to “stretch” a whole series of new rational points from two rational points.

Let's take the curve as an example

$$y^2 + y = x^3 - x.$$

Problem 7. Prove that this curve is not rational.

Let's take two points on this curve and draw a straight line through them. This straight line will intersect our curve at one more point (Fig. 6). Indeed, if we write the equation of the straight line we drew in the form $y = kx + b$ and substitute $y$ into the equation of the curve, we obtain an equation of the third degree of the relative $x$. When the root of this equation corresponds to the abscissa of the three points of intersection of the straight line and our cubic curve. Let $P_1(x_1; y_1), P_2(x_2; y_2), P_3(x_3; y_3)$ be the three intersection points of the line $y = kx + b$ and the curve $y^2 + y = x^3 - x$. There is a correspondence

$$x_1 + x_2 + x_3 = \left(\frac{y_1 - y_2}{x_1 - x_2}\right)^2.$$

To prove this, let’s substitute $y = kx + b$ into the equation of the curve. We obtain the equation $x^3 - k^2 x^2 - (2kb + k + 1)x - b^2 - b = 0$. It can be proven that $x^3 - k^2 x^2 - (2kb + k + 1)x - b^2 - b = (x - x_1)(x - x_2)(x - x_3)$. Therefore, $x_1 + x_2 + x_3 = k^2$. The slope $k$ of the line passing through the points $P_1(x_1, y_1)$ and $P_2(x_2, y_2)$ is $\frac{y_1 - y_2}{x_1 - x_2}$. Thus we get (*).

Given that $y_3 = kx_3 + b$, $b = \frac{y_2 x_1 - y_1 x_2}{x_1 - x_2}$, we see that the coordinates of the third intersection point are rational if the coordinates of the first two points are rational. This makes it possible to obtain new solutions to the equation $y^2 + y = x^3 - x$ in rational numbers.

⟦folio 6⟧

Fig. 7.

Comment. The distance above the cubic equation may have coincidence roots. This will mean that the straight line and our curve touch.

We will now construct an infinite series of rational solutions to the equation $y^2+y=x^3-x$ by drawing secants and tangents through known rational points. Let us first note that the points of our curve are located in pairs - together with the point $P(x_0; y_0)$ there is a point $P'(x_0; -1-y_0)$ on the curve, symmetrical to it relative to the straight line $y=-\frac{1}{2}$. This follows from point $y^2+y=(-1-y)^2+(-1-y)$. Let's start with the evaluated rational point $P_1(0; 0)$. The point symmetrical to it is $P'_1(0; -1)$. Let's draw a tangent through $P_1$ (see remark). The equation of this tangent is $y=-x$. Let's find the point of its intersection with our curve: $P_2(1; -1)$. Those who do not know how to find a tangent can use direct substitution to check that the rational point $P_2$ lies on our curve. From $P_2$ we obtain the point $P'_2(1; 0)$.

So, there are four rational points on our curve:

$$P_1(0; 0), \quad P'_1(0; -1),$$
$$P_2(1; -1), \quad P'_2(1; 0).$$

Now we launch the “conveyor”. Let's draw a straight line through $P_1$ and $P'_2$—this is the $x$ axis. It intersects our curve at another obvious point $P_3(-1; 0)$. Together with the symmetrical point $P'_3(-1; -1)$ we have six points of the original curve. Let's connect the points $P'_3$ and $P_1$. We get straight line $y=x$. The third intersection point is easy to find: substituting $y=x$, we get the cubic equation $x^3-x^2-2x=0$, two roots of which are changed. Using (*) we obtain a new point $P_4(2; 2)$ - a non-obvious solution to the original equation. Let's continue this process. To get point $P_5$, draw a straight line through points $P'_4(2; -3)$ and $P_1$. It is easy to check that the result will be point $P_5(1/4; -3/8)$. Using figure 7 it is easy to trace the process of constructing new points. Calculations using formula (*) are also simple. As a result, we obtain a series of points shown in the table.

It is unlikely that any of the readers will say that all the solutions we found are obvious.

At this point in the article, the author even captured two of them - how many meaningful questions can be raised by looking at the harmless figure 7. Here are a few of them:

1. By drawing secants and tangents, will we get an infinite sequence of different points or will our process “go in cycles”?
2. Are all rational solutions to the original equation found in our sequence?

⟦folio 7⟧

3. Will integer solutions still appear (as, for example, points (6; 14) and (6; -15) were expressed) or will all subsequent solutions be non-integer?

4. Is it by chance that the denominators of the solution contain squares and cubes of integers?

5. It is clear from the picture that, for example, the point $P_5$ can be obtained differently - by drawing a straight line through $P'_3$ and $P'_2$. Is this a coincidence?

6. It is almost obvious that all points with odd numbers are located on one branch of the curve, and all points with even numbers are located on the other. How can this be strictly proven?

The first three questions are very difficult. Let me tell you that our sequence of points is infinite and all points with rational coordinates will be found in it.

Instead of insults, I will give one more example. Let's look at a very similar curve $y^2 + y = x^3 - x^2$. A configuration similar to the one we constructed is declared at the third step - see figure 8. It is interesting that this curve has no other rational points, and the equation $y^2 + y = x^3 - x^2$ has no solution in rational numbers, except for four trivial ones.

We have touched upon one of the most difficult questions of modern number theory.

It is known that on any Cubian curve there is a finite number of points from which, starting the described process, one can obtain all its rational points. This was proven about fifty years ago, but there is still no general way to find these points.

The way to find out whether the process of drawing straight lines or ducting an infinite configuration will loop is known. More recently, it has been proven that the final configuration can have more than 11 points and all cases (except the case of 10 points) occur and are well studied.

On most known curves, the number of starting points for constructing all rational points is small - one or two. However, there is a hypothesis that for any $n$ there are curves that require $n$ points to construct all solutions. So far the examples have been built for $n \leqslant 7$.

And finally, the last remark: if in our example with the curve $y^2 + y = x^3 - x$ we slightly change the notation - we write $A_1$ together $P_1$, $A_{-1}$ (instead of $A'_1$, $A_k$ together $P'_k$ and $A_{-k}$ together $P_k$ (for $k \geqslant 2$), and the “addition” given is somewhat trickier (“the sum” of two points is not the third point of intersection of a straight line and a curve, but the point symmetrical to it relative to the straight line $y = -\frac{1}{2}$), we get the formula

$$A_m \oplus A_n = A_{m+n},$$

valid for all integers $m, n$.
