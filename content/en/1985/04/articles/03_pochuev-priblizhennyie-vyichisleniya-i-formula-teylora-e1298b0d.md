---
id: 1985-4-pochuev-priblizhennyie-vyichisleniya-i-formula-teylora-e1298b0d
issue: kvant_1985_4
year: 1985
number: "4"
title: Approximate calculations and Taylor's formula
authors:
  - Почуев В. Р.
rubric: osnovnye-stati
page_first: 5
page_last: 8
page_labels: 3-6
tag: WYMX
lang: en
source: kvant_digital
extraction: vision
content_sha256: bccf286c1ab7e5c4a79b1c11722b1d6cc97a3d2b48687d552fd3f54a4dade624
prompt_sha256: draft-1
translated_from: content/ru/1985/04/articles/03_pochuev-priblizhennyie-vyichisleniya-i-formula-teylora-e1298b0d.md
source_content_sha256: 6f90894a8bcaf2351829917c23315e71bf8bed67701d8b20e46004b7b4b7cd84
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 3⟧

Approximate calculations and Taylor's formula

V. R. POCHUEV

This article begins with simple substitutions about approximate arithmetic calculations, which naturally lead to Taylor's substitution formula. In particular, this formula is established by school methods, and then used to approximately calculate the values ​​of functions.

Two examples to warm up

Suppose we need to calculate the product

$$p = 1,03 \times 2,01$$

with an accuracy of 0.001. It’s natural to do this calculation like this

$$p = (1 + 0,03) \cdot (2 + 0,01) \approx 2 + 0,06 + 0,01 = 2,07.$$

Here we have spared four terms $0,01 \times 0,03 = 0,0003$, since it is less than the prescribed accuracy.

The sign used will become clearer if you denote the number 0.01 by $x$. Then our calculation is simply the calculation of functions (polynomial)

$$f(x) = (1 + 3x)(2 + x) = 2 + 7x + 3x^2$$

when the value is $x = 0,01$, or $p = f(0,01)$. When writing the approximate equality $f(x) \approx 2 + 7x$, we neglect the higher (second) degree term $3x^2$.

Let's consider a slightly more complex example: let's calculate the product with an accuracy of 0.01

$$q = 2,12 \times 1,97.$$

Now denoting the number 0.1 by $x$, we see that calculating $q$ means finding the value of the function

$$g(x) = (2 + x + 2x^2)(2 - 3x^2)$$

at $x = 0,1$. Opening the brackets, we get

$$g(x) = 4 + 2x - 2x^2 - 3x^3 - 6x^4.$$

The terms with $x^3$ and $x^4$ can be neglected, since at $x = 0,1$, $x^3 = 0,001$ and $x^4 = 0,0001$ is outside the required accuracy of 0.01. So,

$$q = g(0,1) \approx 4 + 2(0,1) - 2(0,1)^2 = 4,18.$$

Let's analyze our actions

The success of the calculations was based on the fact that the desired product $p$ (or $q$) was close to the exact number $A$, and then represented as the value of some function $f(x)$ for small $x$, with $f(0)$ equal to $A$.

So, in the first example, a rough estimate gives $p \approx 1 \cdot 2 = 2 = A_1$, and the deviations of the com factor from ones and twos are small. Similarly, in the second example a rough estimate gives $q \approx 2 \cdot 2 = 4 = A_2$, and again the deviations of the com factor from twos are small. In per-

⟦folio 4⟧

In the second case, this deviation of the factors was measured in “x-units”, where $x$ was 0.01, and in the second case - in `other “x’-units”, where $x'$ was 0.1.

Next, the selected function $f(x)$ (or $g(x)$) was divided into two parts - existing and secondary:

$$f(x) = f_1(x) + f_2(x), \quad f_1(x) = 2 + 7x, \quad f_2(x) = 3x^2, \quad g(x) = g_1(x) + g_2(x), \quad g_1(x) = 4 + 2x - 2x^2, \quad g_2(x) = -3x^3 - 6x^4,$$

where the essential parts $f_1(x)$ (and $g_1(x)$) were polynomials of the first and second degree, representing the results with the required accuracy, and $f_2$ and $g_2$ were negligible.

Let's introduce the symbol "about small"

In the cases considered in mathematical analysis, the following shorter and more expressive recording formula is often used:

$$f(x) = 2 + 7x + o(x), \quad g(x) = 4 + 2x - 2x^2 + o(x^2).$$

Here the symbol $o(x)$ (read “about small from $x$”) denotes some function of $x$ (we are not interested in its exact form), which tends to zero faster than $x$, that is, such that

$$\lim_{x \to 0} \frac{o(x)}{x} = 0.$$

Similarly, $o(x^2)$ is some function of $x$ tending to zero faster than $x^2$, that is

$$\lim_{x \to 0} \frac{o(x^2)}{x^2} = 0.$$

The general $o(x^n)$, for $n \ge 1$, is a notation for a function of $x$ that has the following property:

$$\lim_{x \to 0} \frac{o(x^n)}{x^n} = 0.$$

Using the arithmetic properties of limits (see Algebra and the beginning of analysis 9-10, paragraphs), it is easy to establish the following rules that allow you to transform complex expressions containing o small into simpler ones:

(a) $o(x^n) + o(x^n) = o(x^n)$,
(b) $x \cdot o(x^n) = o(x^{n+1})$,
(c) $x^{n+1} = o(x^n)$, etc.
(For example, to set (a),

$$\begin{align*}
\lim_{x \to 0} \frac{o(x^n)}{x^n} &= 0.
\end{align*}$$

it is necessary to show that the sum of two functions, each of which tends to zero, itself tends to zero; and this immediately follows from the rule about the sum of limits.)

Let us derive several approximate formulas

Let's use the symbols $o(x)$, $o(x^2)$, ... and their properties to derive some formulas useful for approximate calculations.

Example 1. Let's prove the formula:

$$(1+x)^3 = 1 + 3x + o(x).$$

(The term $o(x)$ tells us that this formula can be used if the square $x$ can be neglected in our calculations.)

Proof. Using the sum cube formula

$$(1+x)^3 = 1 + 3x + 3x^2 + x^3,$$

but $x^2 = o(x)$ (rule (d)); $3x^2 = o(x)$ (rule (b)); $x^3 = o(x)$ (rules (d), (c)). That's why

$$(1+x)^3 = 1 + 3x + o(x) + o(x) = 1 + 3x + o(x).$$

Thus, we can write with an accuracy of 0.01:

$$(1,012)^3 \approx 1 + 3 \cdot 0,012 = 1,036.$$

Example 2. Let's prove the formula:

$$\frac{1}{1-q} = 1 + q + q^2 + \dots + q^n + o(q^n).$$

The proof follows immediately from an easy verifiable approach

$$\frac{1}{1-q} = 1 + q + q^2 + \dots + q^n + \frac{q^{n+1}}{1-q}.$$

Let us use formula (2) to approximately calculate the fraction $r = 201/203$. Representing this fraction as

$$r = \frac{1 + \frac{1}{200}}{1 + \frac{3}{200}},$$

let's consider the function

$$h(x) = \frac{1+x}{1+3x}; \quad h\left(\frac{1}{200}\right) = h(0,005) = r.$$

Take in (2) $n=2$, $q=-3x$; Then

$$\frac{1}{1+3x} = 1 - 3x + 9x^2 + o(x^2),$$

⟦folio 5⟧

$$h(x) = \frac{1}{1+3x} = 1 - 2x + 6x^2 + o(x^2).$$

Thus, $r = h(0,005) \approx 1 - 0,01 + 0,000150 = 0,990150$.

Exercises

1. Write and establish a formula for $(1+x)^7$ with accuracy $o(x^2)$.
2. Write and establish a formula for $1/(1+q)$ with accuracy $o(q^n)$.

Approximate calculation of radicals

In the approximate calculation of radicals, we will distinguish between a “good” case and a “bad” case. In the “good” case, under the square root sign there is a number slightly different from the perfect square; the calculated number $\lambda$ has the form $\sqrt{a^2 + a^2}$, where $a$ is small compared to $a^2$. To illustrate this case, consider the following example.

Example 3. Let's find an approximation to the value of the root $\lambda = \sqrt{99}$.

Let's represent $\lambda$ as
$$\lambda = \sqrt{100-1} = 10\sqrt{1-0,01}$$
and consider the function $r(x) = \sqrt{1+x}$ so that $\lambda = 10r(-0,01)$. Let us assume that for small $x$ there is an approximate formula
$$r(x) = a + bx + cx^2 + o(x^2).$$

(3) Find $a, b$ and $c$. First of all, directing $x$ to zero, we obtain: $a = 1$. Now let’s square both sides of equality (3):
$$1 + x = a^2 + 2abx + (b^2 + 2ac)x^2 + o(x^2).$$

Equating the coefficients for the same powers $x$ in both sides of the last equality, we obtain $a^2 = 1; 2ab = 1; b^2 + 2ac = 0$. Considering that $a = 1$, we find: $b = 1/2; c = -1/8$. So,
$$\sqrt{1+x} = 1 + \frac{1}{2}x - \frac{1}{8}x^2 + o(x^2).$$

(4) Thus,
$$\lambda = 10r(-0,01) \approx 10(1-0,005 - 0,0000125) = 10(0,9949875) = 9,949875.$$

Let us now show how to act in a “bad” case. As an illustration, let's look at

Example 4. Let's find an approximation to the value of the root $\mu = \sqrt{2}$.

It is clear that the formula (4) we found, which gives $\sqrt{2}$ for $x = 1$, is completely unsuitable for calculating the root, since $x$ is not small, and we cannot calculate that the terms on the right side of (4) decrease quickly. To make a “good” case, we select two complete squares whose ratio is 2. Such squares are, for example, 25 and 49. Then
$$\mu = \sqrt{2} = \frac{7}{5} \sqrt{\frac{50}{49}} = \frac{7}{5} v.$$
The calculation of $v$ is already a “good” case, since under the radical sign there is a number close to 1 (a perfect square). Let's write $v$ as:
$$v = (1-0,02)^{-\frac{1}{2}}$$
and consider the function $S(x) = 1/\sqrt{1+x}$. Then $v = S(-0,02)$. Let us again assume that there is a formula of the form
$$S(x) = a + bx + cx^2 + o(x^2).$$
Directing $x$ to zero, we obtain $a = 1$. We square both sides and multiply by the denominator,
$$1 = (1+x)(a^2 + 2abx + (b^2 + 2ac)x^2 + o(x^2)),$$
$$1 = a^2 + (a^2 + 2ab)x + (b^2 + 2ab + 2ac) \times x^2 + o(x^2).$$
We equate the coefficients for the same powers $x$ in both sides of the last equality, we get $a^2 = 1, a^2 + 2ab = 0, b^2 + 2ab + 2ac = 0$. Considering that $a = 1$, we find: $b = -1/2; c = 3/8$. So,
$$\frac{1}{\sqrt{1+x}} = 1 - \frac{1}{2}x + \frac{3}{8}x^2 + o(x^2).$$

Thus,
$$\mu = \sqrt{2} = (7/5)S(-0,02) \approx 1,4(1+0,01+0,00015) = 1,41421.$$
Taylor's formula for polynomials Let a polynomial of degree $n$ be given:
$$p(x) = a_0 + a_1x + a_2x^2 + ... + a_nx^n$$
Then the following formula holds:
$$p(x) = p(0) + p'(0)x + \frac{1}{2!}p''(0)x^2 + ... + \frac{1}{n!}p^{(n)}(0)x^n,$$

⟦folio 6⟧

in which $p^{(n)}$ denotes the $n$th derivative function $p$, and the symbol $n!$ (read “en factoral”) is deciphered as follows: $n! = 1 \cdot 2 \cdot 3 \cdot \dots \cdot n$.

For example, at $n = 2$, $p(x) = a_0 + a_1x + a_2x^2$, therefore $p'(x) = 2a_2x + a_1$, $p''(x) = 2a_2$, therefore, $p'(0) = a_1$, $p''(0) = 2a_2$ and therefore, indeed,

$$p(x) = p(0) + p'(0)x + \frac{1}{2}p''(0)x^2 = a_0 + a_1x + a_2x^2.$$

In the general case, formula (6) is checked directly. I advise the reader not to be lazy and continue this check, starting “as a warm-up” with case $n = 3$.

Taylor formula for functions

Using rules (6) and (d), formula (6) can be rewritten as

$$p(x) = p(0) + p'(0)x + \frac{p''(0)x^2}{2} + \dots + \frac{p^{(n-1)}(0)}{(n-1)!}x^{n-1} + o(x^{n-1}).$$

This formula is useful for approximate calculations when $x^n$ is negligible. However, we are interested in it here for another reason: it turns out that this formula is true not only for polynomials $p(x)$, but also for arbitrary functions $f(x)$ (as long as they have arbitrary $f'(x)$, $f''(x)$, ..., $f^{(n+1)}(x)$ up to order $n+1$ inclusive). Correspondence

$$f(x) = f(0) + f'(0)x + \frac{f''(0)}{2}x^2 + \dots + \frac{f^{(n)}(0)}{n!}x^n + o(x^n)$$

is called the Taylor (or Maclaurin) formula after two English mathematical coefficients of the 17th-18th centuries, although in essence it was also known to Newton. We will not prove this formula in general form, but will also obtain expansions using simpler means, as we have already done earlier.

Taylor's formula
for fractional rational functions (method of indefinite coefficients)

Fractional rational is any function that represents

treatment in the form of a ratio of two polynomials. Let's look at a specific example of how to obtain the Taylor expansion for such functions.

Example 5. Using the Taylor formula, we expand the function up to $o(x^3)$

$$f(x) = \frac{1+x}{1+x+x^2}.$$

First way. Consider the function $g(x) = \frac{1}{1+x+x^2}$. Let's introduce a new variable $t = x+x^2$. Using formula (2), where $q = -t$, we can write

$$g(x) = \frac{1}{1+t} = 1-t+t^2-t^3+o(t^3) = 1-(x+x^2)+(x+x^2)^2-(x+x^2)^3 + o(x^3) = 1-x+x^3+o(x^3).$$

So,

$$f(x) = (1+x)(1-x+x^3+o(x^3)) = 1-x^2+x^3+o(x^3).$$

Second method (method of undetermined coefficients). Let

$$f(x) = \frac{1+x}{1+x+x^2} = a+bx+cx^2 + dx^3 + o(x^3)$$

Let's multiply both sides by the denominator:

$$1+x = (1+x+x^2)(a+bx+cx^2+dx^3 + o(x^3))$$

$$1+x = a+(a+b)x+(a+b+c)x^2 + (b+c+d)x^3+o(x^3).$$

We equate the coefficients for the same powers $x$ in both sides of the last equality, we get $a=1, a+b=1; a+b+c=0; b+c+d=0$. Thus, $a=1, b=0, c=-1, d=1$, and we arrive at the same result.

Taylor's formula
for trigonometric functions

Our goal is to prove the following formula, without using the general Taylor formula (7).

$$\sin x = x - \frac{x^3}{3!} + \frac{x^5}{5!} + o(x^5),$$

$$\cos x = 1 - \frac{x^2}{2!} + \frac{x^4}{4!} + o(x^4).$$
