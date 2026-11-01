---
id: 1990-2-toom-uravneniya-kotoryie-udaetsya-reshit-8bb28127
issue: kvant_1990_2
year: 1990
number: "2"
title: Equations that can be solved
authors:
  - Тоом А. Л.
rubric: shkola-v-kvante
page_first: 57
page_last: 59
page_labels: 55-57
lang: en
source: kvant_digital
extraction: vision
content_sha256: b7fcaba7af2e62e600abc3761b0262def3a1d4f460974d28e266102be573224b
prompt_sha256: draft-1
translated_from: content/ru/1990/02/articles/16_toom-uravneniya-kotoryie-udaetsya-reshit-8bb28127.md
source_content_sha256: 38c40da034672abb0ea3b52fe20083e9d7ac493ed3147382df1aedd3947927dc
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 55⟧

---
running_head:
folio:
---

Mathematics 9-11

Equations,
which can be solved

In this note we will talk about algebraic equations of the form
$a_nx^n + a_{n-1}x^{n-1} + \dots + a_1x + a_0 = 0$. (1)

At school, equations are also solved only for values ​​$n \leqslant 2$. However, in some cases, equations of degree higher than second are obtained using special techniques. We will show some of them here.

I. Theorem. Let all coefficients $a_n, \dots, a_0$ in equation (1) be integers, and let the irreducible fraction $p/q$ be the root of this equation. Then its numerator $p$ is a divisor of the free term $a_0$, and its denominator $q$ is a divisor of the leading coefficient $a_n$.

Proof. Let us substitute $x = p/q$ into equation (1). We'll get
$a_np^n + a_{n-1}p^{n-1}q + \dots + a_1pq^{n-1} + a_0q^n = 0$.

The factor $p$ is included in all terms except the last one. But then the last term is also divisible by $p$, since it is equal to the sum of the remaining terms (with a minus sign). Since our fraction $p/q$ cannot be a divisor of the number $p$, it means that for the last term $a_0q^n$ to be divisible by $p$, it is necessary that the free term $a_0$ be divisible by $p$. The first statement of the theorem is proven. The second can be proven in a similar way.

Using this theorem, we can find all rational roots of any equation with integer coefficients (if any). To do this, just make a list of all divisors

⟦folio 56⟧

---
running_head:
folio:
---

free term, a list of all divisors of the leading coefficient and then try all the fractions of the form $p/q$, taking $p$ from the first list, and $q$ from the second.

II. Now let's assume that we already know one root of the equation. (It doesn't matter now how we recognized it.) How can we use this to find the rest of the roots? The procedure for dividing polynomials will help us by putting multi-digit numbers on the procedure. Let's show with an example how this is done. Let us be given the equation

$$x^3 - 2x + 1 = 0.$$

According to the previous theorem, if this equation has rational roots, then only 1 or -1. By checking we make sure that the number 1 is indeed a root.

Now we need to factor the polynomial on the left side of the equation. This can be done by clever grouping of terms, but there is also a reliable way that does not require a contract: dividing our polynomial by a corner by $x - 1$. How this is done is shown in figure 1.

$$\begin{array}{c}
x^3 - 2x + 1 \\
x^3 - x^2 \\
x^2 - 2x + 1 \\
x^2 - x \\
- x + 1 \\
- x + 1 \\
0
\end{array}$$

Puc. 1.

In this case, the remainder is zero, so we dare to write down the identity

$$x^3 - 2x + 1 = (x - 1)(x^2 + x - 1).$$

But, generally speaking, when dividing polynomials, a remainder is obtained. Another example of division is shown at figure 2. This gives a remainder of 2. We know this

$$\begin{array}{c}
x^3 - 2x + 1 \\
x^3 + x^2 \\
- x^2 - 2x + 1 \\
- x^2 - x \\
- x + 1 \\
- x + 1 \\
0
\end{array}$$

Puc. 2.

read that there is an identity

$$x^3 - 2x + 1 = (x + 1)(x^2 - x - 1) + 2.$$

A remainder is a polynomial whose degree is less than the degree of the divisor. In particular, if the divisor is a binomial of the form $x - x_0$, then the remainder is a number. It is this case that interests us here.

Let us now move on to general definitions.

Dividing the polynomial $P(x)$ by the binomial $x - x_0$ means finding a polynomial $Q(x)$ and a number $R$ such that the identity is obtained

$$P(x) = (x - x_0)Q(x) + R.$$

(2)

You can search for them in any way, for example by dividing with a corner. The following theorem tells us what the remainder will be when dividing by the binomial $x - x_0$.

Bezout's theorem. The remainder when dividing the polynomial $P(x)$ by the binomial $x - x_0$ is $P(x_0)$. In particular, this remainder is equal to zero if and only if the number $x_0$ is the root of the polynomial $P(x)$.

Proof. Let's substitute $x = x_0$ into identity (2) and get

$$P(x_0) = R,$$

which constitutes the first statement of the theorem. From this equality we see that $R$ is equal to zero if $P(x_0)$ is equal to zero, that is, if $x_0$ is the root of $P(x)$.

So, if we know that the number $x_0$ is the root of the polynomial $P(x)$, we divide it by $x - x_0$, knowing in advance (thanks to Bezout’s theorem) that the remainder will be zero. Thus, we will create a solution to this equation to solve another equation of lesser degree. Sometimes in this way it is possible to solve the equation completely, that is, find all its roots.

III. Another example that is useful when solving an equation is substitution of variables. The most interesting case is reciprocal equations. Equation (1) is called reciprocal if its coefficients, located at equal distances from the ends, are equal:

$$a_{n-k} = a_k$$ for all $k$ from 0 to $n$.

It turns out that any return

⟦folio 57⟧

---
running_head:
folio:
---

$$x + \frac{1}{x} = t.$$ (3)

Let's show how to apply this substitution using the example of a returned fourth-degree equation:

$$ax^4 + bx^3 + cx^2 + bx + a = 0,$$ where $a \neq 0$.

Let's divide it by $x^2$ and rewrite it like this:

$$a \left(x^2 + \frac{1}{x^2}\right) + b \left(x + \frac{1}{x}\right) + c = 0.$$

Let us square equality (3):

$$t^2 = \left(x + \frac{1}{x}\right)^2 = x^2 + \frac{1}{x^2} + 2,$$

i.e.

$$x^2 + \frac{1}{x^2} = t^2 - 2.$$

Introducing a new variable $t$, we obtain a quadratic equation

$$a(t^2 - 2) + bt + c = 0.$$

As for recurrent polynomials of odd degree, they are all divisible by $x + 1$ and after such division they give recurrent polynomials of even degree. Let's show this using the example of the returned equation of the fifth degree

$$ax^5 + bx^4 + cx^3 + bx + a = 0.$$

It is easy to see that $x = -1$ is the root of this equation, therefore, according to Bezout’s theorem, the polynomial on the left side of the equation is divisible by $x + 1$. However, the result of division can also be obtained by grouping the terms:

$$a(x^5 + 1) + bx(x^3 + 1) + cx^2(x + 1) = 0.$$

As is known, both $x^3 + 1$ and $x^5 + 1$ are divisible by $x + 1$:

$$x^3 + 1 = (x + 1)(x^2 - x + 1),$$

$$x^5 + 1 = (x + 1)(x^4 - x^3 + x^2 - x + 1).$$

And in general, $x^{2k+1} + 1$ is divisible by $x + 1$ for any $k$:

$$x^{2k+1} + 1 = (x + 1)(x^{2k} - x^{2k-1} + \dots - x + 1)$$

(“flat” and “cons” are crossed).

With this we have established the theory. To learn how to use it, solve the following problems.
