---
id: 1981-1-egorov-pokazatelnyie-uravneniya-7d633aaf
issue: kvant_1981_1
year: 1981
number: "1"
title: Exponential equations
authors:
  - Егоров А. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 42
page_last: 44
page_labels: 40-42
tag: O5SA
lang: en
source: kvant_digital
extraction: vision
content_sha256: 05efb23ee2a73c9a578ac134edde74092c4efcf3716b8137944578d619053f45
prompt_sha256: draft-1
translated_from: content/ru/1981/01/articles/13_egorov-pokazatelnyie-uravneniya-7d633aaf.md
source_content_sha256: fdaf09c12e47c00d3b3e3cbca7992b324b2eff3b168fa7e7d63aa73ecd77b825
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

Exponential equations

The topic of this article is an equation containing an unknown in an exponent. Such equations are often encountered in advanced exams, and therefore it is useful for the applicant to become familiar with some methods for solving them.

The simplest exponential equation is an equation of the form $a^x = b$, where $a > 0, a \neq 1$. For $b > 0$ this equation has a single root $x = \log_a b$, for $b \leq 0$ the equation has no roots.

When transforming exponential equations, the properties of the exponential function are often used (see the manual “Algebra and Basic Analysis 10”, paragraph 108): $a^{x_1} \cdot a^{x_2} = a^{x_1 + x_2}, (a^{x_1})^{x_2} = a^{x_1 x_2}, (ab)^x = a^x \cdot b^x$ (here $a > 0, b > 0$).

If the original equation is of the form

$$f(a^x) = b,$$

(1)

where $f$ is a certain function, then to solve it we can put $y = a^x$, solve the equation $f(y) = b$, choose its positive roots and then solve the resulting simplest equation.

Task 1 (MIIGAiK, 1978). Solve the equation

$$3^{2-x} = 3^x - 8.$$

Solution. Putting $y = 3^x$, we obtain the equation $\frac{9}{y} = y - 8$ or $y^2 - 8y - 9 = 0$. The resulting quadratic equation has roots

$$y_1 = -1, y_2 = 9.$$

The first one DOESN'T STRAIGHT us ($y > 0$). Therefore $3^x = 9$, hence $x = 2$.

Answer. {2}.

In some cases, an equation that does not have the form (1) can be converted to this form, using the property of an exponential function.

Problem 2 (MII, 1976). Solve the equation

$$3 \cdot 16^x + 2 \cdot 81^x = 5 \cdot 36^x.$$

Solution. After obvious transformations we get:

$$3 \cdot 4^{2x} + 2 \cdot 9^{2x} = 5 \cdot 4^x \cdot 9^x.$$

Since $9^x \neq 0$, the resulting equation is equivalent to the equation

$$3 \cdot \left(\frac{4}{9}\right)^{2x} + 2 = 5 \cdot \left(\frac{4}{9}\right)^x.$$

Polling $y = \left(\frac{4}{9}\right)^x$, we arrive at the quadratic equation $3y^2 - 5y + 2 = 0$. Its roots are $y_1 = 1, y_2 = \frac{2}{3}$.

Solving the simplest equation $\left(\frac{4}{9}\right)^x = 1$ and $\left(\frac{4}{9}\right)^x = \frac{2}{3}$, we obtain in the first case $x = 0$, and in the second $\left(\frac{2}{3}\right)^{2x} = \frac{2}{3}$; that is, $2x = 1$ or $x = \frac{1}{2}$.

Answer. {0, 1/2}.

Let us now consider several examples in which the exponent turns out to be non-octorian functions of $x$.

Task 3 (MIIGAiK, 1970). Solve the equation

$$3^{2x^2 + 6x - 9} + 4 \cdot 15^{x^2 + 3x - 5} = 3 \cdot 5^{2x^2 + 6x - 9}$$

Solution. Let us put $y = x^2 + 3x - 5$, after which the equation will be rearranged as follows:

$$3^{2y+1} + 4 \cdot 3^y \cdot 5^y = 3 \cdot 5^{2y+1}.$$

Separating the right and left sides by $5^{2y}$, we arrive at the equation

$$3 \cdot \left(\frac{3}{5}\right)^{2y} + 4 \cdot \left(\frac{3}{5}\right)^y - 15 = 0.$$

Solving this equation as the previous one, we obtain $\left(\frac{3}{5}\right)^y = \frac{5}{3}$, whence

⟦folio 41⟧

$$y = -1. \text{ Осталось решить квадратное уравнение } x^2 + 3x - 5 = -1.$$

Answer. {1, -4}.

Sometimes, after transformation, the original equation is reduced to the form
$$a^{f(x)} = b^{g(x)}
(a > 0, b > 0, a \neq 1).$$

To solve this equation, it is useful to note that it is equivalent to the equation
$$a^{f(x)} = a^{g(x)} \log_a b$$
(we used the basic logarithmic theoretical alogab = b). From the monotonicity of the exponential function it follows that equation (2) is equivalent to the equation
$$f(x) = g(x) \log_a b.$$

Problem 4. Solve the equation
$$3^{x-3} = 5^{x^2 - 7x + 12}.$$
Solution. Let's move on to the equivalent equation
$$x - 3 = (x^2 - 7x + 12) \log_3 5.$$
The resulting equation, of course, can be solved in the usual way (this is a quadratic equation). But solving it is rather inconvenient, since it has “disgusting” coefficients.

However, if we notice that $x^2 - 7x + 12 = (x - 3)(x - 4)$, the solution is greatly simplified.

We have $x - 3 = (x - 3)(x - 4) \log_3 5$, from which either $x = 3$, or $(x - 4) \times \log_3 5 = 1$ or $x = 4 + \frac{1}{\log_3 5} = 4 + \log_5 3.$

Answer. {3, 4 + \log_5 3}.

Let's look at one more example.

Problem 5 (MIET, 1978). Solve the equation
$$32^{\frac{x+5}{x-7}} = 0,25 \cdot 128^{\frac{x+17}{x-3}}.$$
$$32 = 2^5, 0,25 = 2^{-2}, 128 = 2^7$$, so the equation is rewritten as:
$$2^{5 \cdot \frac{x+5}{x-7}} = 2^7 \cdot \frac{x+17}{x-3} - 2$$
and therefore equivalent to the equation
$$\frac{5x+25}{x-7} = \frac{7x+119}{x-3} - 2,$$

which reduces to the equation
$$\frac{x+5}{x-7} = \frac{x+25}{x-3},$$
having the root $x = 10$.

Answer. {10}.

Sometimes you come across an equation that contains an unknown in both the base and the exponent. Before moving on to considering specific problems, let us make some remarks about the domain of definition of functions of the form $f(x)^{g(x)}$.

Obviously, when an exam presents a problem in which a function is of the form $f(x)^{g(x)}$, it is assumed that applicants will consider it for such values ​​of $x$ for which one of the conditions is met: either $f(x) > 0$, or $f(x) = 0$ and $g(x) > 0$.

Thus, $x = 3$ is the root of the equation $(x - 3)^x = 3 - x$. For $x > 3$ this equation obviously has no roots (its left side is positive and its right side is negative). For $x < 3$ the base of the degree is negative and therefore such $x'$ should not be considered, although it can be noted that direct substitution of $x = 2$ into the equation gives the correct equality $(2 - 3)^2 = 3 - 2$ and therefore the number 2 is also its root.

Applicants who do not replace this and do not consider the case $x < 3$ at all do not commit any error and the answer $x = 3$ in this problem should be considered correct.

The accepted agreement is due to the fact that the question of the meaning of the expression $a^b$ with $a < 0$ and the real $b$, which is not an integer, is very complex and cannot be resolved within the framework of a medium scale course.

Problem 6. Solve the equation
$$x^{x^2 - 5x + 8} = x^2.$$
Solution. We only consider $x \ge 0$. Since at $x = 0$ the function on the left side is defined and equal to zero and the right side is equal to zero, 0 is the root of this equation. It is easy to see that for $x > 0$ this equation is equivalent to the equation $(x^2 - 5x + 8) \lg x = 2 \lg x$, whence either $\lg x = 0$, that is, $x = 1$, or $x^2 - 5x + 6 = 0$, that is, $x = 2$ and $x = 3$.

⟦folio 42⟧

Answer. {0, 1, 2, 3}.

To conclude this section, we consider two problems that can be solved by the property of monotonicity of the exponent of a function.

Problem 7. Solve the equation

$$3 \cdot 4^x + (3x - 10) \cdot 2^x + 3 - x = 0.$$

Solution. This task does not belong to any of the previously discussed types. Still, let's try to make a replacement $y = 2^x$. We get

$$3 \cdot y^2 + (3x - 10)y + 3 - x = 0.$$

Let us now solve the resulting equation as a quadratic equation with respect to $y$. We have

$$y = \frac{-3x + 10 \pm \sqrt{(3x - 10)^2 - 12(3 - x)}}{6}$$

$$= \frac{-3x + 10 \pm \sqrt{9x^2 - 48x + 64}}{6}$$

$$= \frac{-3x + 10 \pm (3x - 8)}{6},$$

from where either $y = 3 - x$ or $y = \frac{1}{3}$.

The equation $2^x = \frac{1}{3}$ has root $x = -\log_2 3$.

Let us now solve the equation

$$2^x = 3 - x.$$

It's easy to guess the root $x = 1$. Let us prove that this equation has no other roots. Indeed, for $x = 1$ the left side is equal to the right. The left side is an increasing function, and the right side is a decreasing function. Therefore, with $x < 1$ the left side will be smaller than the right, and with $x > 1$, on the contrary, the right side will be larger than the left.

Answer. {1, $-\log_2 3$}.

Problem 8. Solve the equation

$$6^x - 2^x = 32.$$

Solution. Attempts to find the root of this equation using conventional methods yield nothing. At the same time, it is easy to see that the equation satisfies the value $x = 2$. Let us prove that there are no other roots. To do this, we rearrange the equation like this:

$$3^x - 1 = \frac{32}{2^x}.$$

The right side is decreasing
