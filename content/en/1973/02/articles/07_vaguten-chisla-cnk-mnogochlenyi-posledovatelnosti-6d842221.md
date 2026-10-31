---
id: 1973-2-vaguten-chisla-cnk-mnogochlenyi-posledovatelnosti-6d842221
issue: kvant_1973_2
year: 1973
number: "2"
title: Numbers C_n^k, polynomials, sequences
authors:
  - Вагутен В. Н.
rubric: osnovnye-stati
page_first: 29
page_last: 34
page_labels: 27-32
tag: WEA5
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2ad739e7f9e817e3075a6bdd988ae2c5c7db2d06becb4d450777a2a5b9a4b4a4
prompt_sha256: draft-1
translated_from: content/ru/1973/02/articles/07_vaguten-chisla-cnk-mnogochlenyi-posledovatelnosti-6d842221.md
source_content_sha256: 33c13a6eb39ad91f30cbc5e0c1681727c040b26fd1acea92251da62a900a4cc6
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

Numbers $C_n^k$, polynomials, sequences
(several approaches to one problem)
V. N. Vagumen

Let us recall one problem from “Problem «Kvant», the elementary solution of which was written in «Kvant» No. 12 for 1972.

M138. Prove that if $m$ and $n$ are terms of the number $1 < m < n$, then

$$\sum_{k=1}^{n} (-1)^k k^m C_k^k = 0,$$

its $C_k^k$ are biominal coefficients.

Various proofs of these points will serve as a good opportunity for us to introduce the reader to some important mathematical concepts and facts that are not included in the school curriculum (finite differences, interpolation formula for polynomials, arbitrary polynomials, power series of exponentials). Following the definitions and theorem in each paragraph, the reader will encounter the words “let us now return to our problem,” followed by a new solution problem M138.

The proofs of the theorems can be skipped, but it is better to parse them, although this is not easy to do, since they are written very briefly.

Introduction. Biominal coefficients and problem formulation

We list several properties of the numbers $C_n^k$. Each of the properties 0.1-0.3 can be taken to define these numbers.

0.1. $C_n^k$ — polynomial coefficients

$$(a + x)^n = C_n^0 a^n + C_n^1 a^{n-1} x + \dots + C_n^k a^{n-k} x^k + \dots + C_n^n x^n.$$

0.2. $C_n^0 = 1; C_n^n = 1$; for each $k = 1,2, \dots, n - 1$

$$C_n^k = C_{n-1}^{k-1} + C_{n-1}^k.$$

0.3. For all $n$ and $k$ ($0 \leqslant k \leqslant n$)

$$C_n^k = \frac{n(n-1)\dots(n-k+1)}{1 \cdot 2 \cdot \dots \cdot k},$$ or $C_n^k = \frac{n!}{k!(n-k)!},$

where $m! = 1 \cdot 2 \cdot 3 \dots m; \quad 0! = 1! = 1$.

Exercise 0. a) Find the numbers $C_n^k$ for all $n$ from 1 to 10, use each of the definitions 0.1, 0.2, 0.3. b) Print 0.2 from 0.1, use tokdev $(a + x)^n = (a + x)^{n-1}(a + x)$. b) Derive 0.3 from 0.2, use mathematical induction

⟦folio 28⟧

tsini (that is, check that if formula (3) is true for $n-1$, then it is also true for $n$).
d) Check that $C_n^k = C_n^{n-k}$.

The polynomial $a + x$ is sometimes called a “binomial” (bin is the same as double), formula (1) is the formula of “Newton’s binomial”, and the numbers $C_n^k$ are “binomial coefficients”.

Let us set $a$ equal to 1 in equality (1). We obtain

$$(1 + x)^n = C_n^0 + C_n^1 x + \dots + C_n^k x^k + \dots + C_n^n x^n.$$

Substituting $x = -1$ here, we get

$$C_n^0 - C_n^1 + C_n^2 - \dots + (-1)^k C_n^k + \dots + (-1)^n C_n^n = 0.$$

It turns out that in addition to correspondence (5), the following equalities are also true for the numbers $C_n^k$:

$$- C_n^1 + 2 C_n^2 - 3 C_n^3 + \dots + (-1)^n n C_n^n = 0,$$
$$- C_n^1 + 2^2 C_n^2 - 3^2 C_n^3 + \dots + (-1)^n n^2 C_n^n = 0,$$
$$- C_n^1 + 2^{n-1} C_n^2 - 3^{n-1} C_n^3 + \dots + (-1)^n n^{n-1} C_n^n = 0.$$

It was these equalities that needed to be proved in problem M138; they will be discussed at the end of each paragraph.

In the future, we will often use a short notation of amounts using the $\Sigma$ icon. For example, formula (1) can be briefly written as follows:

$$(a + x)^n = \sum_{k=0}^{k=n} C_n^k a^{n-k} x^k,$$
formula (4) $-(1 + x)^n = \sum_{k=0}^{k=n} C_n^k x^k,$
equality (5) $-\sum_{k=0}^{k=n} (-1)^k C_n^k = 0$ and, finally, equalities (6), which need to be proved in problem M138 -

$$\sum_{k=1}^{k=n} (-1)^k k^m C_n^k = 0$$

for every natural $m < n$.

§ 1. Sequences and finite differences

Let the set of non-negative integers 0, 1, 2, 3... be given a function $f$. This means that the sequence is given

$$f(0), f(1), f(2), f(3), \dots$$

If from each member of the sequence $f$, of course, except for the first, we subtract the preceding member of the sequence, then we obtain a new sequence - a sequence of differences

$$f(1) - f(0), f(2) - f(1), f(3) - f(2), \dots$$

Let us denote the corresponding function by $\Delta f$: $\Delta f(0) = f(1) - f(0);$
$\Delta f(1) = f(2) - f(1);$ $\Delta f(2) = f(3) - f(2) \dots$

If we perform the same operation - the transition from $f$ to $\Delta f$ - with the sequence $\Delta f$, then we get the sequence

$$f(2) - 2f(1) + f(0), f(3) - 2f(2) + f(1), \dots$$

Let's denote it by $\Delta^2 f$.

⟦folio 29⟧

This sequence is called the second difference sequence for $f$. Let's be clear again, we get a sequence of third differences - $\Delta^3 f$:

$$f(3) - 3f(2) + 3f(1) - f(0), f(4) - 3f(3) + 3f(2) - f(1), \dots$$

and so on.

Thus, by definition

$$\Delta^{n+1}f(x) = \Delta^n f(x + 1) - \Delta^n f(x).$$

(7)

(Recall that the argument $x$ of the functions $f$, $\Delta f$, $\Delta^2 f$, ... takes non-negative integer values: $x = 0, 1, 2, \dots$).

As a first example, consider the constant function $f$:

$$f(0) = f(1) = f(2) = \dots = a.$$

For it, the sequence of differences $\Delta f$ will obviously consist of only zeros. Let's briefly write it like this: $\Delta f \equiv 0$ (for all $x$).

Naturally, the sequences $\Delta^2 f$, ..., $\Delta^n f$ will also consist of only zeros, that is, $\Delta^n f \equiv 0$.

If $f$ is a linear function: $f(x) = ax + b$, that is, if the sequence is represented by the arithmetic progression $b, a + b, 2a + b, 3a + b, \dots$, then all terms of the sequence $\Delta f$ will be equal to the same number $a$. Hence $\Delta^2 f \equiv 0$.

If $f$ is a quadratic trinomial $f(x) = ax^2 + bx + c$, then $\Delta f$ is a linear function (from the number $x$):

$$\Delta f(x) = f(x + 1) - f(x) = a(x + 1)^2 + b(x + 1) + c - ax^2 - bx - c = 2ax + b.$$

Then $\Delta^2 f$ is a constant function: $\Delta^2 f = 2a$. Hence $\Delta^3 f = 0$ and of course $\Delta^n f = 0$ for all $n > 2$.

We do not have rights 1. a) Let $f(x) = x^3$. Find $\Delta f$, $\Delta^2 f$, $\Delta^3 f$, ... 6) Same question if $f(x) = 2^x$.

Our observations are summarized in the following two theorems.

1.1. The number $\Delta^n f(x)$ is expressed through the values ​​of the functions $f$ according to the formula

$$\Delta^n f(x) = C_n^0 f(x + n) - C_n^1 f(x + n - 1) + \dots + (-1)^n C_n^n f(x) =$$

$$= \sum_{k=0}^{k=n} (-1)^k C_n^k f(x + n - k).$$

1.2. If $f(x)$ is a polynomial of degree $m < n$, then $\Delta^n f = 0$.

Both statements 1.1 and 1.2 can be proved by induction on $n$. For $n = 1, 2, 3$ we have already checked them. It is assumed that they are true for $n$, we prove them for $n+1$.

1.1. Using (7), (8) and (2), we obtain

$$\Delta^{n+1}f(x) = \Delta^n f(x + 1) - \Delta^n f(x) =$$

$$= C_n^0 f(x + n + 1) - C_n^1 f(x + n) + \dots + (-1)^n C_n^n f(x) - C_n^0 f(x + n) + \dots + (-1)^n C_n^n f(x) =$$

$$= C_n^0 f(x + n + 1) - C_n^1 f(x + n) + \dots + (-1)^n C_n^n f(x + n) + (-1)^n \times C_n^n f(x).$$

1.2. Let $f(x) = a_0 + a_1 x + \dots + a_j x^j + \dots + a_m x^m$. Our $m$ equalities (they follow from (4))

$$(x + 1)^j - x^j = C_j^1 x^{j-1} + C_j^2 x^{j-2} + \dots + C_j^{j-1} x + 1$$

(here $j = 1, 2, \dots, m$). Let us multiply them accordingly by the coefficients $a_j$ and add them. We get: on the left side $\Delta f(x) = f(x + 1) - f(x)$, on the right - a certain polynomial in $g(x)$ of degree not higher than $m - 1$. If $m < n$, then $m - 1 < n - 1$ and by the induction hypothesis $\Delta^{n-1}g = 0$. Therefore, $\Delta^n f = \Delta^{n-1} (\Delta f) = \Delta^n g = 0$.

⟦folio 30⟧

Let us now return to our task.

Equality (6'), according to 1.1. I am exactly aware that $\Delta^n f(0) = 0$ is for the function $f(x) = x^m$, and this follows directly from Statement 1.2.

Problem 1. Let $f(x) = a + a_1x + \dots + a_nx^n$. Find $\Delta^n f$. Using this result, calculate the sum

$$\sum_{k=0}^{k=n} (-1)^k k^n C_n^k.$$

Problem 2. Prove that there is $\Delta^{n+1} f(x) = 0$ for all $x$, then $f(x)$ is a polynomial of degree at most $n$.

Problem 3. Find all sequences $f$ for which $\Delta f(x) = \lambda f(x)$, where $\lambda$ is some number.

§ 2. Polynomials and interpolation formula

We know that through two points we can draw a single straight line. In other words, if two pairs of numbers $(\alpha_0, \beta_0), (\alpha_1, \beta_1)$ are given, and $\alpha_0 \neq \alpha_1$, then there is a unique polynomial of degree not higher than the first $P(x) = ax + b$ such that $P(\alpha_0) = \beta_0$ and $P(\alpha_1) = \beta_1$.

This fact is summarized as follows.

Let $n + 1$ different numbers $\alpha_0, \alpha_1, \dots, \alpha_n$ and $n + 1$ numbers $\beta_0, \beta_1, \dots, \beta_n$ be given. Then the following statements are true.

2.1. There is a polynomial $P$ of degree no higher than $n$ such that

$$P(\alpha_i) = \beta_i \quad (\text{для всех } i = 0,1,\dots,n).$$

2.2. The polynomial $P$ is uniquely defined.

To prove 2.1, it suffices to imagine such a polynomial. To do this, consider first the polynomials

$$D_k(x) = \frac{(x - \alpha_0)(x - \alpha_1)\dots(x - \alpha_{k-1})(x - \alpha_{k+1})\dots(x - \alpha_n)}{(\alpha_k - \alpha_0)(\alpha_k - \alpha_1)\dots(\alpha_k - \alpha_{k-1})(\alpha_k - \alpha_{k+1})\dots(\alpha_k - \alpha_n)}$$

(into the numerator and denominator of $n$ polynomials). It's clear that

$$D_k(\alpha_i) = \begin{cases} 1, \text{ если } i = k; \\ 0, \text{ если } i \neq k. \end{cases}$$

Let us now multiply $D_k(x)$ by the number $\beta_k$ and add all these polynomials. To obtain a polynomial

$$P(x) = \sum_{k=0}^{k=n} \beta_k D_k(x)$$

all equalities (9) are satisfied.

To prove 2.2, we need two important theorems about the roots of polynomials.

2.3. If a polynomial

$$f(x) = a_0 + a_1x + \dots + a_nx^n$$

degrees not higher than $n + 1$ of different roots, then this polynomial is equal to 0, that is, $a_0 = a_1 = a_2 = \dots = a_n = 0$.

2.4. (“Bezout’s Theorem.”) If $\alpha$ is the root of the polynomial $f(x)$, then the polynomial $f(x)$ is divisible by $x - \alpha$, that is

$$f(x) = (x - \alpha)g(x),$$

food $g(x)$ is a certain polynomial.

⟦folio 31⟧

Proof 2.4. Let's write $n$ points $(x^j - \alpha^j) = (x - \alpha)(x^{j-1} + x^{j-2}\alpha + \ldots + \alpha^{j-2}x + \alpha^{j-1})$, $(j=1, 2, \ldots, n)$, multiply them respectively by the coefficients $a_j$ and add all these points. We obtain a formula that is valid for any polynomial (12) and any number $\alpha$:

$$f(x) - f(\alpha) = (x - \alpha)g(x),$$

where $g(x)$ is some polynomial. In particular, if $f(\alpha)=0$, we obtain (13).

Proof 2.3. Let us carry out induction on $n$. For $n=1$ Statement 2.3 is obvious. Let us prove that if it is true for $n-1$, then it is also true for $n$. Let $\alpha_0, \alpha_1, \ldots, \alpha_n$ be the roots of the polynomial (12). Then, according to 2.4:

$$f(x) = (x - \alpha_n)g(x),$$

moreover, the polynomial $g(x)$ has degree at most $n-1$ and has $n$ different roots $\alpha_0, \alpha_1, \ldots, \alpha_{n-1}$. By the induction hypothesis, $g(x)$ is equal to zero; from (14) it follows that $f(x)$ is also equal to zero.

Proof 2.2. Let $p_1$ and $p_2$ be two polynomials, for each of which equalities (9) are true. Then their difference satisfies the conditions of Theorem 2.3 (a polynomial $f(x) = p_1(x) - p_2(x)$) of degree no higher than $n+1$ roots $\alpha_0, \alpha_1, \ldots, \alpha_n$ and therefore equals zero, that is, $p_1(x) = p_2(x)$.

So, we have proven that through $n+1$ point $(\alpha_0, \beta_0), (\alpha_1, \beta_1), \ldots, (\alpha_n, \beta_n)$ we can prove a unique curve of the form

$$y = f(x) = a_0 + a_1x + \ldots + a_nx^n,$$

and even provided a formula that allows you to immediately write the required polynomial. This formula (11) is called the Laerang integration formula.

Exercise 2. a) Find a square triangle, which at points 2, 3, 5 belongs to the corresponding values ​​7, 11, 13. 6) Find a polynomial of degree not higher than 4, the graph of which passes through the points $(-2, -7), (-1, 0), (0, 1), (1, 2), (2, 9)$.

Let's return to our task. Let us construct a polynomial of degree at most $n$, which at points $\alpha_k = k(k=0, 1, 2, \ldots, n)$ belongs to the value of the corresponding $\beta_k = k^m$. From formula (11) it follows that this polynomial is equal to $\sum_{k=0}^{k=n} k^mD_k(x)$, where

$$D_k(x) = \frac{x(x-1)\ldots(x-k+1)(x-k-1)\ldots(x-n)}{k(k-1)\ldots1(-1)(-2)\ldots(k-n)}.$$

It is clear that the coefficient of $x^n$ for polynomial (15) is equal to

$$\frac{1}{k(k-1)\ldots1(-1)(-2)\ldots(k-n)} = (-1)^{k-n} \frac{1}{k!(n-k)!} = \frac{(-1)^n}{n!} (-1)^k C_n^k,$$

Posically the coefficient of $x^n$ for the polynomial $P(x)$ is equal to

$$(1/n!) (-1)^n \sum_{k=0}^{k=n} (-1)^k k^m C_n^k.$$

On the other hand, it is clear that the polynomial $P(x)$ is simply $x^m$, because $m < n$. Therefore, the coefficient of $x^n$ $P(x)$ is zero.

Task 4. Prove that the set of numbers $y_0, y_1, \ldots, y_n$ satisfies the following conditions: “for any polynomial $f(x)$ of degree not higher than $n-1$ the equality

$$\sum_{k=0}^{k=n} f(k)y_k = 0»,$$

if and only if $y_k = t(-1)^k C_n^k$, where $t$ is some number.

⟦folio 32⟧

Task 5 (generalization). Prove that if the numbers $\alpha_0, \alpha_1, \dots, \alpha_n$ are pairwise distinct, then the system of equation

$$y_0 + y_1 + \dots + y_n = 0,$$
$$\alpha_0 y_0 + \alpha_1 y_1 + \dots + \alpha_n y_n = 0,$$
$$\alpha_0^2 y_0 + \alpha_1^2 y_1 + \dots + \alpha_n^2 y_n = 0,$$
$$\alpha_0^{n-1} y_0 + \alpha_1^{n-1} y_1 + \dots + \alpha_n^{n-1} y_n = 0$$

has a solution to a set of numbers

$$y_k = \frac{t}{(\alpha_k - \alpha_1)(\alpha_h - \alpha_2) \dots (\alpha_k - \alpha_{k-1})(\alpha_h - \alpha_{k+1}) \dots (\alpha_h - \alpha_n)}$$

($k=0, 1, \dots, n+1$), where $t$ is an arbitrary number and has no other solutions.

§ 3. Derivative polynomial and multiple roots

Let $f(x)$ be a polynomial of degree $n$:

$$f(x) = a_0 + a_1 x + a_2 x^2 + \dots + a_{n-1} x^{n-1} + a_n x^n = \sum_{k=0}^{k=n} a_k x^k.$$

Then by definition a polynomial of degree $n-1$

$$f'(x) = a_1 + 2 a_2 x + \dots + (n-1) a_{n-1} x^{n-2} + n a_n x^{n-1} = \sum_{k=1}^{k=n} ka_k x^{k-1}$$

is called an arbitrary polynomial $f(x)$. The following statement turns out to be true.

3.1. If the polynomial $f(x)$ is divisible by $(x - \alpha)^{m+1}$, then the polynomial $f'(x)$ is divisible by $(x - \alpha)^m$. In other words, if the number $\alpha$ is the root of multiplicity $m+1$ of the polynomial $f(x)$, then $\alpha$ is the root of multiplicity at least $m$ of the polynomial $f'(x)$.

For proof 3.1. we use this lemma.

3.2. If $f(x) = (x - \alpha)g(x)$, then

$$f'(x) = g(x) + (x - \alpha)g'(x).$$

(16)

Proof 3.2. If $g(x) = b_{n-1} x^{n-1} + \dots + b_1 x + b_0$, then, as is not difficult to check, using the definition of an arbitrary polynomial, both the right and left sides of equality (16) are equal

$$(b_0 - b_1 \alpha) + 2 (b_1 - b_2 \alpha) x + \dots + (n-1) (b_{n-2} - b_{n-1} \alpha) x^{n-2} + n b_{n-1} x^{n-1}.$$

Proof 3.1 is verified by indykation using $m$. Let's check 3.1 for $m=1$. If $f(x)$ is divisible by $(x - \alpha)^2$, then $f(x) = (x - \alpha) g(x)$, where $g(x)$ is divisible by $(x - \alpha)$, and, as can be seen from (16), $f'(x)$ is also divisible by $(x - \alpha)$.

Proof 3.1 is true for $m-1$, then it is also true for $m$. Let $f(x)$ be divisible by $(x - \alpha)^{m+1}$. Then $f(x) = (x - \alpha) g(x)$, where $g(x)$ is divisible by $(x - \alpha)^m$, and from (16) it follows that $f'(x)$ is divisible by $(x - \alpha)^m$ ($g'(x)$ is divisible by $(x - \alpha)^{m-1}$ by the indyktion proposal).

Practice 3. a) Does the polynomial $x^3 - x^2 - 8x + 12$ have multiple roots?

6) Find $a, b$ and $c$ such that the polynomial $x^3 + ax^2 + bx + c$ is divisible by $(x+1)^2$.

Let us now return to our task. Equality (6') means exactly that the polynomial $f_m(x) = \sum_{k=0}^{k=n} k^m C_k^n x^{k-1}$ has the number $x = -1$ as its root.

Let us prove a stronger statement: the polynomial $x f_m(x)$ has the number $(-1)$ as a root of multiplicity $n-m$, that is, it is divisible by $(x+1)^{n-m}$ (if $m < n$).

For $xf_0(x) = \sum_{k=0}^{k=n} C_k^n x^k = (1+x)^n$ this is very convenient. For $0 < m < n$ we perform indykation on $m$. Let $xf_{m-1}(x)$ have the number $(-1)$ as a root multiple
