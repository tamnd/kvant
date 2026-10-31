---
id: 1974-6-abramovich-chisla-bernulli-ec1bf57b
issue: kvant_1974_6
year: 1974
number: "6"
title: Bernoulli numbers
authors:
  - Абрамович В. С.
rubric: osnovnye-stati
page_first: 12
page_last: 15
page_labels: 10, 12, 13
tag: 8IVA
lang: en
source: kvant_digital
extraction: vision
content_sha256: 11792e7aa194ab51937a9d61b73785a6a0236eba508828c77e8345b6ba82c483
prompt_sha256: draft-1
translated_from: content/ru/1974/06/articles/04_abramovich-chisla-bernulli-ec1bf57b.md
source_content_sha256: 2ec9c8f6eec8c8cf1f81a0394a4856b5adb107954b963359701f72b197f1e4ba
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 10⟧

Since ancient times, mathematicians have tried to construct the secrets of the wonderful world of numbers. This world attracts with its diversity, strictness and perfection of laws. Here there are “greats” and there are “dwarfs”, general “hard workers” and such “celebrities” as l and e. But the world of number sequences is even more diverse. Here is a sequence of natural numbers
1, 2, 3, ...,
and a sequence of prime numbers full of deep secrets
2, 3, 5, 7, ...,
and a sequence of “binomial coefficients”
$C_1^1, C_2^1, C_2^2, C_3^1, C_3^2, C_3^3, ...,$

appearing when raised to the power of 2, 3, 4, ... “binomial” $a + b$:
$(a + b)^k = a^k + C_k^1 a^{k-1} b + C_k^2 a^{k-2} b^2 + \ldots + C_k^{k-1} a b^{k-1} + b^k.$

The numbers $C_k^m$ are a fundamental tool in a fascinating branch of mathematics: combinatorics $^*$. We will need them in this country too. For example, they can be calculated very simply - using the formula
$$C_k^m = \frac{k(k-1)(k-2)\ldots(k-m+1)}{1 \cdot 2 \ldots m},$$

$1 \leq m \leq k$, with which you can easily derive their most important property:
$$C_k^{m-1} + C_k^m = C_k^{m+1}$$

(Pascal's theorem). Formula (2) can also be rewritten in this more “compact” form:
$$C_k^m = \frac{k!}{m!(k-m)!},$$

where $n! = 1 \cdot 2 \cdot \ldots n$ at $n > 0$; value 0! turns out to be equal to one (the symbol ! is called a factor). Formula (2*) immediately implies one more property of binominal coefficients:
$$C_k^m = C_k^{k-m}.$$

$^*$ This science is described in the book by N. Ya. Vilenkin with an unambiguous title, M., “Science”, 1969.

⟦folio 12⟧

then setting $n = 0$, we obtain a recurrent formula for calculating the numbers $B_k$:

$$B_k = \frac{1}{k+1} \left[ C_{k+1}^2 B_{k-1} - C_{k+1}^3 B_{k-2} + \ldots + (-1)^k C_{k+1}^k B_1 - (-1)^k B_0 \right],$$

(7)

$B_0 = 1$.

Use this formula to check the values ​​of the first four Bernoulli numbers (see (6)).

Bernoulli was able to prove that other coefficients of the polynomial $S_k(n)$ can be calculated using the numbers $B_k$. The coefficient of $n^2$ turns out to be equal to $\frac{B_{k-1}}{k-1} C_k^2$, the coefficient of $n^3$ is equal to $\frac{B_{k-2}}{k-2} C_k^3$, and finally, the coefficient of the degree $n^k$ turns out to be independent of $k$ and always equal to $\frac{B_1}{1} C_k^k = \frac{1}{2}$.

The coefficient for the highest degree $k+1$ stands out, which can be found immediately from formula (5). It is equal to $\frac{1}{k+1}$.

Thus, Bernoulli's formula has the form

$$S_k(n) = B_k n + \frac{B_{k-1}}{k-1} C_k^2 n^2 + \frac{B_{k-2}}{k-2} C_k^3 n^3 + \ldots + \frac{B_1}{1} C_k^k n^k + \frac{n^{k+1}}{k+1}.$$

(8)

In the next paragraph we will show that formula (8) is actually half as long.

2. Bernoulli numbers with odd numbers

Theorem. All odd-numbered Bernoulli numbers except $B_1$ are equal to zero: $B_{2m+1} = 0$ at $m \geqslant 1$.

To prove this, we use equality (1); apply it to the difference $(1+a)^{2m} - (1-a)^{2m}$:

$$(1+a)^{2m} - (1-a)^{2m} = 2 \left( C_{2m}^1 a + C_{2m}^3 a^3 + C_{2m}^5 a^5 + \ldots + C_{2m}^{2m-1} a^{2m-1} \right).$$

Putting $a = 1, 2, \ldots, n$ here and adding up the results obtained, we get:

$$(S_{2m}(n) + (n+1)^{2m} - 1) - (S_{2m}(n) - n^{2m}) = (n+1)^{2m} + n^{2m} - 1.$$

On the right we get the expression

$$2 \left( C_{2m}^1 S_1(n) + C_{2m}^3 S_3(n) + \ldots + C_{2m}^{2m-1} S_{2m-1}(n) \right).$$

(9)

So we have

$$(n+1)^{2m} + n^{2m} - 1 = 2 \left( C_{2m}^1 S_1(n) + C_{2m}^3 S_3(n) + \ldots + C_{2m}^{2m-1} S_{2m-1}(n) \right).$$

Let us calculate the coefficient of $n^1$ in the expressions obtained in the right and left parts. In the expression on the left side, this coefficient will be equal to 2$m$ (obviously). It is a little more difficult to obtain the form of the coefficient of the first power $n$ in the expression on the right side: to do this, it is enough to replace the sums $S_j(n)$ ($j = 1, 3, \ldots, 2m-1$) of Bernoulli numbers with the same numbers in formula (9) (this statement follows from the very definition of Bernoulli numbers). So this is the approach:

$$C_{2m}^1 B_1 + C_{2m}^3 B_3 + C_{2m}^5 B_5 + \ldots + C_{2m}^{2m-1} B_{2m-1} = m.$$

⟦folio 13⟧

Not like $C_{2m}^1 = 2m$, but $B_1 = \frac{1}{2}$, then it should be:

$$C_{2m}^3 B_3 + C_{2m}^5 B_5 + \ldots + C_{2m}^{2m-1} B_{2m-i} = 0. \tag{10}$$

Putting $m = 2, 3, 4, \ldots$ here successively and taking into account that $C_n^k = 0$ for $k > n$, we obtain:

$$B_3 = B_5 = B_7 = \ldots = 0.$$

3. Connection with prime numbers

Christan Staudt (1798-1867), studying Bernoulli numbers, obtained a beautiful and profound result that reveals the arithmetic nature of these numbers. Let the number $B_h$ be given. Consider all prime numbers $p$ not exceeding $k + 1$, and also that $p - 1$ is called $k$ (that is, the number of a given Bernoulli number). For all such $p$ we compose a finite sum of the form $\sum \frac{1}{p}$ - let's call it the sum corresponding to the given Bernoulli number $B_h$ (let us consider just such sums that Staudt deals with). It turned out that the number $B_h$ and the corresponding sum $\sum \frac{1}{p}$ complement each other to an integer. So, $B_h + \sum \frac{1}{p}$ is always an integer!

Let us give an example to evaluate the importance of this result of Staudt. Let us know what $B_6$ is and what $0 < B_6 < 1$. We want to find its exact value; It turns out that this is now easy to do.

Indeed, the divisors of 6 are the numbers 1, 2, 3, 6. Increasing them by one, we get the numbers 2, 3, 4, 7. Of these, the prime numbers are 2, 3 and 7. We calculate the sum $\sum \frac{1}{p}$:

$$\frac{1}{2} + \frac{1}{3} + \frac{1}{7} = \frac{41}{42}.$$

Thus, by Staudt's theorem $\frac{41}{42} + B_6$ must be an integer, but since by condition $0 < B_6 < 1$, the only suitable integer is 1. Therefore

$$B_6 = 1 - \frac{41}{42} = \frac{1}{42}.$$

Exercise 1. Find $B_{14}$, which is between the numbers 1 and 2.

4. About Kummer's theorem

In 1850, the great German mathematician Ernst Kummer (1810–1893) obtained an important result concerning the probleme of the existence of a solution in integers to the Fermat equation $x^n + y^n = z^n$, $n \geq 3$ – to the probleme of Fermat. Although the result of this does not completely solve the problem, it nevertheless remains one of the most significant obtained in this direction. This result turns out to be closely related to Bernoulli numbers.

Before formulating Kummer's theorem, we introduce the following (Kummer's proposal). Let the given simple
