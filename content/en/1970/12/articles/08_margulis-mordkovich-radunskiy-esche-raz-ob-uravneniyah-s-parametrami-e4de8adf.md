---
id: 1970-12-margulis-mordkovich-radunskiy-esche-raz-ob-uravneniyah-s-parametrami-e4de8adf
issue: kvant_1970_12
year: 1970
number: "12"
title: Once again about equations with parameters
authors:
  - Маргулис А. Я.
  - Мордкович А. Г.
  - Радунский Б. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 51
page_labels: 46-49
tag: R1KM
lang: en
source: kvant_digital
extraction: vision
content_sha256: f8ba224ab76ddd42cf12823931c78a9ef275ddf98b3bd2a74eac9f8db927540b
prompt_sha256: draft-1
translated_from: content/ru/1970/12/articles/08_margulis-mordkovich-radunskiy-esche-raz-ob-uravneniyah-s-parametrami-e4de8adf.md
source_content_sha256: 264645cf41f61b7b2894372529c338d17d0ece6c264a83a11f57bd9ec9c1c051
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

ONCE AGAIN ABOUT EQUATIONS
WITH PARAMETERS

You have already come across equations and inequalities that contain one parameter more than once. What if there are more than one parameters? It is natural to expect that the number of possible cases to be considered will increase. None of the possible options should be missed. How to do this? There is no single method suitable for any equations and inequalities with parameters. In this article we will show with examples how equations with two parameters are solved.

The general form of the equation for $x$ with two parameters $a, b$ is:

$$F(x; a; b) = 0.$$

(1)

Equation (1) for a given function $F$ is, in fact, an infinite set of equations, each of which is determined by an ordered pair of numbers $(a; b)$.

As is known, such an ordered pair can be interpreted as a point on the coordinate plane. This makes it possible to establish a one-to-one correspondence between equations of the form (1) for a given function $F$ and points of the plane.

To do this, we introduce the coordinate system $aOb$ and agree on how to assign an equation of the form (1) to a point in the plane $aOb$ with coordinates $(a; b)$, and vice versa. Let's turn this plane into a plane of parameters. Such a correspondence is somewhat unusual (the equation corresponds to a point), but it will help us in each specific case to find a set of permissible parameter values ​​and not to miss a single case: to which point of the plane of parameters an equation of the form (1) corresponds and a certain answer must correspond.

Example 1: Solve the equation

$$\frac{2a + b}{a + x} - \frac{2a - b}{a - x} = \frac{2a}{b}$$

(2)

Solution. Let us immediately note that for $b = 0$ equation (2) does not make sense, that is, for any pair of numbers of the form $(a; 0)$, where $a$ is any real number, there are no solutions (red line on figure 1).

Let $b \neq 0$. Let's find the ODZ: $x \neq \pm a$, get rid of the denominator and bring similar terms. We get

$$a(x^2 - 2bx + b^2 - a^2) = 0.$$

(3)

If $a = 0$, then equation (3) has its solutions for any values ​​of $x$. Of these, for equation (2), the values ​​$x = \pm a$, that is, $x = 0$, are prohibited.

Thus, for any pair of numbers of the form $(0; b)$, where $b \neq 0$, equation (2) has its solutions to any numbers except 0 (green line). Let now $a \neq 0$. Solving the equation $x^2 - 2bx + b^2 - a^2 = 0$, we obtain $x_1 = b + a$, $x_2 = b - a$.

*) In the form (1) this equation is: $$\frac{2a + b}{a + x} - \frac{2a - b}{a - x} - \frac{2a}{b} = 0.$$

⟦folio 47⟧

Can we assume that for any $a, b$ different from zero, the found values ​​$x_1$ and $x_2$ are the roots of equation (2)? No, or it may turn out that for some values ​​of the parameters $x_1$ or $x_2$ will coincide with the forbidden values ​​$\pm a$.

So, it remains to find out when $x_1 = \pm a$ or $x_2 = \pm a$. If $x_1 = a$ or $x_2 = -a$ then $b = 0$, but we are considering the case $b \neq 0$. So, $x_1 \neq a$, $x_2 \neq -a$.

Let $x_1 = -a$, that is, $b + a = -a$, whence $b = -2a$. But then $x_2 = -3a$. Thus, if the parameters $a$ and $b$ are such that $b = -2a$, then equation (2) has a single root $x = -3a$ (blue line at figure 1). Let $x_2 = a$, that is $b - a = a$. This is possible with $b = 2a$.

But then $x_1 = 3a$. Thus, if the parameters $a$ and $b$ are such that $b = 2a$, then equation (2) has a single root $x = 3a$ (yellow line).

To summarize, we get the following answer:

if $b = 0$, $a$ are any real number, then there are no solutions;
if $b \neq 0$, $a = 0$, then $x$ is any real number other than zero;
if $b = -2a$, $b \neq 0$, then $x = -3a$;
if $b = 2a$, $b \neq 0$, then $x = 3a$;
if $a, b \neq 0$, $b \neq \pm 2a$, then $x_1 = b + a$, $x_2 = b - a$.

Example 2*). Solve the equation

$$\sqrt{a^2 - x} + \sqrt{b^2 - x} = a + b.$$

(4)

Solution. ODZ is determined by a system of inequalities

$$x \leq a^2, \quad x \leq b^2, \quad \text{или } x \leq \min\{a^2; b^2\}.$$

The left side of equation (4) is non-negative, and therefore for $a + b < 0$ this equation cannot have solutions. On figure 2 this is marked by the fact that the result under the straight line $b = -a$ is colored pink.

Let us now consider the case $a + b \geq 0$. After estimated transformations we obtain

$$x(a + b)^2 = 0$$

(5)

Let's consider two cases:

I case: $a + b > 0$. Then $x = 0$. In this case, conditions $x \leq a^2$ and $x \leq b^2$ are satisfied automatically, which cannot be said about condition $x \geq -ab$. If $ab > 0$, then this condition is very much satisfied. If $ab < 0$, then $-ab > 0$ and $x = 0 < -ab$. Therefore, at figure 2 in zones II and III (where $a + b > 0$, but $ab < 0$) there are no solutions. So $x = 0$ is the root

*) This example is taken from the book by N.P. Antonov et al. “Collection of problems in elementary mathematics” (Moscow, “Nauka”, 1969), where it was solved incorrectly.

⟦folio 48⟧

Fig. 2.

Equation (4), only if $a + b > 0$ and $ab \geq 0$, that is, for the points of the first four plane of parameters, including the points of its boundary (zone $I$ to figure 2).

P case: $a + b = 0$. In this case, equation (5) becomes the identity $x \cdot 0 = 0$, but this does not mean at all that any real number is the root of the original equation (4) (explain yourself why this is so).

For $a + b = 0$ we successively find $b = -a$, $b^2 = a^2$, and equation (4) takes the form $2\sqrt{a^2 - x} = 0$, whence $x = a^2 = b^2$, and all conditions are obviously satisfied. At figure 2 this answer is indicated near the blue line $b = -a$.

Combining all the results obtained, we get the answer:
if $a + b > 0$ and $ab \geq 0$, then $x = 0$;
if $a + b = 0$, then $x = a^2$;
if $a + b < 0$ or $a + b > 0$ and $ab < 0$, then there are no solutions.

Example 3. Solve a system of equations

$$tg x + tg y = a, \quad x + y = b.$$

Solution. Let's note the ODZ: $x, y \neq \frac{\pi}{2} + n\pi$ (hereinafter $k, l, m, n = 0; \pm 1; \ldots$). Let us transform the first equation of the system to the form $\frac{\sin(x + y)}{\cos x \cos y} = a$ and then, taking into account the fact that $x + y = b$, we obtain

$$a \cos x \cos y = \sin b.$$

I case: $a = 0$. It naturally breaks down into two options: I, a) $a = 0$, $\sin b = 0$; I, 6) $a = 0$, $\sin b \neq 0$.

If $sin b = 0$, that is, $b = m\pi$, then equation (7) satisfies any pairs $(x; y)$, and system (6) satisfies any pairs $(x; y)$ satisfying the following conditions:

$$x \neq \frac{\pi}{2} + n\pi; \quad y \neq \frac{\pi}{2} + n\pi; \quad x + y = b.$$

If $sin b \neq 0$, that is, $b \neq m\pi$, then equation (7), and with it system (6), has no solution.

II case: $a \neq 0$. Then equation (7) is transformed to the form

$$\cos x \cos y = \frac{\sin b}{a} \text{ и, далее,}$$

$$\cos (x + y) + \cos (x - y) = \frac{2 \sin b}{a}.$$

If we again take into account that $x + y = b$, then equation (8) can be rewritten as follows:

$$\cos (x - y) = \frac{2 \sin b}{a} - \cos b.$$

⟦folio 49⟧

Further alienation depends on the assessment of the right side of equation (9):
if $\left| \frac{2 \sin b}{a} - \cos b \right| > 1$, then equation (9), and with it system (6), has no solution; if $\left| \frac{2 \sin b}{a} - \cos b \right| \leq 1$, then
$$x - y = \pm \arccos \left( \frac{2 \sin b}{a} - \cos b \right) + 2k\pi.$$
Solving the last equation in the system with equation $x + y = b$, we obtain
$$\begin{cases} x = \frac{b}{2} \pm \frac{1}{2} \arccos \left( \frac{2 \sin b}{a} - \cos b \right) + k\pi, \\ y = \frac{b}{2} \pm \frac{1}{2} \arccos \left( \frac{2 \sin b}{a} - \cos b \right) - k\pi. \end{cases}$$
We just have to find out whether it could happen that for some parameter values ​​the found values ​​$x, y$ will coincide with the forbidden values ​​$\frac{\pi}{2} + n\pi$. It is easy to see that this will happen in the case when $b \pm \arccos \left( \frac{2 \sin b}{a} - \cos b \right) = \pi + 2l\pi$. Let's rewrite the last equality as follows: $\pm \arccos \left( \frac{2 \sin b}{a} - \cos b \right) = \pi - b + 2l\pi$, and take the cosine from both sides. We get
$$\frac{2 \sin b}{a} - \cos b = -\cos b, \quad \sin b = 0, \quad b = m\pi.$$
So, if $b = m\pi$ and $a \neq 0$, then system (6) will not have a solution. Combining all the results obtained, we write down the answer:
if $a = 0, b = m\pi$, then the solution to system (6) is any pair $(x, y)$ as well as $x \neq \frac{\pi}{2} + n\pi, \quad y \neq \frac{\pi}{2} + n\pi, \quad x + y = b$;
if $a = 0, b \neq m\pi$, or $a \neq 0, b = m\pi$, then there are no solutions;
if $a \neq 0, b \neq m\pi$ but $\left| \frac{2 \sin b}{a} - \cos b \right| \leq 1$, then there are no solutions.

We limited ourselves to considering examples with only two parameters. Further notification of the number of parameters, without giving anything fundamentally new, only leads to the notification of technical difficulties.

Exercises
1. Solve the following equations:
2. Solve the system of equations:

a) $a^2 - \frac{a^2 - b^2}{2x - x^2} = \frac{b^2 (x + 2)}{x - 2}$;
b) $\frac{\sqrt{a - x} - \sqrt{x - b}}{\sqrt{a - x} + \sqrt{x - b}} = \frac{a - b}{a + b - 2x}$;
b) $\frac{\mathrm{tg} ax}{\sin bx} = 0$.
