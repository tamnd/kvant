---
id: 1983-7-fomin-razlozhenie-na-mnozhiteli-cbac6c85
issue: kvant_1983_7
year: 1983
number: "7"
title: Factorization
authors:
  - Фомин С. В.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 25
page_last: 26
page_labels: 23-24
tag: K3XU
lang: en
source: kvant_digital
extraction: vision
content_sha256: b55226fe2321d7a729b7a7e481e3245b0a00eadabb0e5dd311af63c2124fc494
prompt_sha256: draft-1
translated_from: content/ru/1983/07/articles/02_fomin-razlozhenie-na-mnozhiteli-cbac6c85.md
source_content_sha256: 8b8e96aecdec3c75df84e8e42747cb29c66f9d2b8b7323c68d66ff72ec828850
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 23⟧

Factorization

Candidate of Physical and Mathematical Sciences S. V. FOMIN

At school you often have to deal with algebraic equations. Linear equations can already be solved by sixth-graders. In the village class, schoolchildren learned formulas for solving quadratic equations. Quite cumbersome formulas for solving cubic equations and equations of the fourth degree, found in the 16th century, turn out to be of little use in practice (see the book by S. G. Gindikin “Stories about physicists and mathematicians” (M., “Nauka”, 1981)). Equations of the fifth degree and higher in the general case are not solvable in radiacalx.

And yet, in many cases, an equation of degree $n>2$ is easy to solve. Most often, factoring helps. From the statement “the number $a$ is a root of the polynomial $P(x)$ if and only if $P(x)$ is divisible by $x-a$” and the Fundamental Theorem of Algebra («Kvant», 1982, No. 4) it follows that every polynomial with real coefficients of degree $n>2$ is disordered in the product of factors of the first degree and indecomposable square trieles.

Let's solve some equations.

$$2x^3 - x^2 - 7x + 2 = 0.$$

(1)

The polynomial on the left side of equation (1) has integer coefficients. It is easy to prove that if such an equation has an integer root, then this root is a divisor of the free term (prove it!). The number 2 is the root of equation (1). This means that the polynomial $2x^3 - x^2 - 7x + 2$ is divisible by $x-2$. Obviously, the partial equation is quadratic

a multiple trinomial with leading coefficient 2, so

$$2x^3 - x^2 - 7x + 2 = (x-2)(2x^2 + Bx + C),$$

where $B$ and $C$ are unknown display coefficients. This equality is true for all $x$. By clicking $x=0$, we get $-2C=2$, $C=-1$. By fielding, for example, $x=1$ we get $-(B+1) = -4$, $B=3$.

Thus, equation (1) is rewritten as

$$(x-2)(2x^2 + 3x - 1) = 0.$$

Answer. $\left\{2, \frac{-3+\sqrt{17}}{4}, \frac{3\sqrt{17}}{4}\right\}$

$$\frac{x^4 - 3x^3 + x^2 - 2}{x^3 + 1} = \frac{2}{3x-1}$$

If we immediately get rid of the denominator, we get an equation of the 5th degree. Therefore, “let’s try to count” - let’s try to find out whether it is possible to reduce the fraction on the left side. Its denominator is factorized:

$$x^3 + 1 = (x+1)(x^2 - x + 1).$$

The numerator is not divisible by the first factor (after all, the number - 1 is not the root of the polynomial $x^4 - 3x^3 + x^2 - 2$). Let's try to divide it by $x^2 - x + 1$. You can, of course, again apply the “method of indefinite coefficients”:

$$x^4 - 3x^3 + x^2 - 2 = (x^2 - x + 1)(x^2 + Ax + B) + C.$$

It’s easier, please, to divide with a “corner” - the way we divide a multi-digit number by a multi-digit number:

$$\frac{x^4 - 3x^3 + x^2 - 2}{x^4 - x^3 + x^2 - 2} = \frac{x^2 - x + 1}{x^2 - 2x - 2}$$

$$- \frac{2x^3 + 2x^2 - 2x}{2x^2 + 2x - 2}$$

$$- \frac{2x^2 + 2x - 2}{0}$$

(We divide the leading term of the dividend by the leading term of the divisor: $\frac{x^4}{x^2} = x^2$ - this will be the leading term of the quotient. Then we multiply the resulting term of the quotient by the divisor and subtract the product from the divisor. Next, we divide the leading term of the difference again

⟦folio 24⟧

divisor by the leading term: $\frac{-2x^3}{x^2} = -2x$ - we get the next term of the quotient, etc.)

We were “lucky” - we were divided without a trace. Thus, equation (2) is rewritten as
$$\frac{(x^2-x+1)(x^2-2x-2)}{(x+1)(x^2-x+1)} = \frac{2}{3x-1},
$$
$$\frac{x^2-2x-2}{x+1} = \frac{2}{3x-1}$$

and easily matching to the equation
$$x(x-3)(3x+2) = 0.$$
Answer. $\{0, 3, -\frac{2}{3}\}$.
$$\frac{2}{x+1} + \frac{4}{x-2} - \frac{2}{x} + x+4 = 0.$$ (3)

You can immediately get rid of the denominator and factor the left side of the resulting fourth-degree equation. It is easier, however, to factor directly the left side of equation (3). Note that the number 1 is its root. At $x=1$, the five terms on the left side take on the values ​​1, -4, -2, 1 and 4. Let us transform this equation by subtracting its value at $x=1$ from each term:
$$\left(\frac{2}{x+1}-1\right) + \left(\frac{4}{x-2}+4\right) +
\left(-\frac{2}{x}+2\right) + (x-1) + (4-4) = 0$$
(the sum of the added terms is zero). Let's perform the actions in each of the brackets:
$$-\frac{x-1}{x+1} + \frac{4(x-1)}{x-2} + \frac{2(x-1)}{x} + (x-1) = 0.$$
The factor $x-1$ appeared in each term. This is not surprising - after all, the value of each term at $x=1$ must be zero! Now the problem has been reduced to solving the equation
$$-\frac{1}{x+1} + \frac{4}{x-2} + \frac{2}{x} + 1 = 0.$$
It's not hard to guess one of its roots: $x=-2$ and apply the same example again:
$$\left(-\frac{1}{x+1}-1\right) + \left(\frac{4}{x-2}+1\right) +$$

$$+\left(\frac{2}{x}+1\right) + (1-1) = 0,$$
or
$$-\frac{x+2}{x+1} + \frac{x+2}{x-2} + \frac{x+2}{x} = 0,$$
whence $x=-2$ or
$$-\frac{1}{x+1} + \frac{1}{x-2} + \frac{1}{x} = 0,$$
$$\frac{x^2+2x-2}{x(x+1)(x-2)} = 0.$$
Solving the quadratic equation, we find the remaining roots.

Answer. $\{1, -2, -1-\sqrt{3}, -1+\sqrt{3}\}$.
$$(x^2+3x-2)^2 + 3(x^2+3x-2) - 2 = x.$$ (4)

Note that if x is a solution to the equation
$$x^2+3x-2=x,$$
then it satisfies equation (4). Consequently, we know two roots of equation (4): $x_1 = -1-\sqrt{3}$ and $x_2 = -1+\sqrt{3}$. Opening the parentheses and moving $x$ to the left side, we obtain the equation
$$x^4+6x^3+8x^2-4x-4=0.$$
Its left side is divisible by $x-x_1$ and $x-x_2$, and therefore also by $(x-x_1)(x-x_2) = x^2+2x-2$. Divide in one way or another, we get $(x^2+2x-2)(x^2+4x+2) = 0.$
Answer. $\{-1+\sqrt{3}, -1-\sqrt{3}, -2+\sqrt{2}, -2-\sqrt{2}\}$.

In conclusion, we solve the system of equations
$$\left\{ \begin{array}{l} (x+1)(13x-2y-15) - 2(y-1)(3y+2) = 0, \\ (x+1)(x+4y-15) - 28(y-1) = 0. \end{array} \right.$$ (5)

It is easy to see that the pair $(-1; 1)$ satisfies it. It's not hard to find another pair of $(1; 0)$.

And now - a non-standard move. Let's draw a straight line through the points $(-1; 1)$ and $(1; 0)$ (its equation is $y=-\frac{x}{2}+\frac{1}{2}$) and take another point on it, for example (3; -1). At $x=3; y=-1$ the left side of the first equation of system (5) is equal to 100, and the second is equal to -8. Next
