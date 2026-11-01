---
id: 1981-6-vasilev-malikov-rassmotrim-raznost-4207e8fd
issue: kvant_1981_6
year: 1981
number: "6"
title: Let's consider the difference
authors:
  - Васильев Н. Б.
  - Маликов Т. С.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 29
page_last: 32
page_labels: 27, 29, 30
tag: KKJ5
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7410cf34e64338012cf3f53fc46a4c10f8c422afdf60d2e0610f380acfaf04be
prompt_sha256: draft-1
translated_from: content/ru/1981/06/articles/10_vasilev-malikov-rassmotrim-raznost-4207e8fd.md
source_content_sha256: d075b5209c26faafbb4981f49f97c1a39f66bf003adec84e49969af97569f606
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 27⟧

Let's consider the difference

It is difficult to find a collection of Olympic or algebraic problems where problems of this type would not be found: to prove that for any natural number n

a) $7^{2n} - 5^{2n}$ is divisible by 24;
b) $n^3 - n$ is divisible by 6;
c) $\frac{n^5 - 5n^3 + 4n}{120}$ integer;
d) $3^{2n+3} + 40n - 27$ is divisible by 64;
e) $2^{2n-1} - 9n^2 + 21n - 14$ is divisible by 27;
f) $5^n(5^n + 1) - 6^n(3^n + 2^n)$ is divisible by 91;
g) $\frac{n^5}{5} + \frac{n^3}{3} + \frac{7n}{15}$ integer.

Try to solve these problems. You will likely see various messages like the following:
in the problem
a) take advantage of the fact that $7^2 - 5^2 = 24$ and the same sign
$$a^n - b^n = (1) = (a - b)(a^{n-1} + a^{n-2}b + \ldots + b^{n-1})$$,
showing that $a^n - b^n$ is always divisible by $a - b$;
b) expand the polynomial in the numerator into five factors $(n-2)(n-1)n(n+1)(n+2)$ and replace that of the heel of consecutive numbers there is one divisible by 3, one by 5, one by 4 and one more divisible by 2 (and not divisible by 4);

e) represent the difference as $(25^n - 18^n) - (12^n - 5^n)$ and as $(25^n - 12^n) - (18^n - 5^n)$ to prove its divisibility by 7 and 13;
g) prove separately the divisibility of $5n^3 + 7n$ by 3 and the divisibility of $3n^5 + 7n$ by 5.

Without detracting from the beauty and usefulness of these and other similar wonders, we want to understand one general recipe for all such tasks.

We will see that it is enough to check the validity of each of statements a) - g) only for a small number of the first values ​​n (in problem a) - for two, d) - for three, etc.) in order to be sure of their validity for all n.

And the reader who understands the note thoroughly enough will be able to create new problems in an unlimited number (even those where irrational numbers are found):

3) the number $45^n + (-44)^n - 1$ is divisible by 1980;
i) the number $[(6 + \sqrt{31})^n] - 2^n + 1$ is divisible by 10; In general, if m, a, b are natural numbers and b < 2a, then the number $[(am + 1 + \sqrt{a^2m^2 + bm + 1})^n] - 2^n + 1$ is divisible by 2m (here [x] is the integer part of the number x) *).

Sum of differences

Before formulating general theorems, let us demonstrate the course of our explanations using example d). This problem, as well as the following corollary from Theorem 2 and Lemma 1, constitute the content of Problem M629 from Zadaniak «Kvant».

Let's consider the difference between the values ​​of this function
$$f(n) = 2^{2n-1} - 9n^2 + 21n - 14$$
at points n+1 and n:
$$g(n) = f(n+1) - f(n) = 3 \cdot 2^{2n-1} - 18n + 12.$$
We want to prove that $f(n)$ is divisible by 27 for all n=1, 2,...

*) These two problems were sent last year by our readers B. Chuchin from the village. Voznesenskoye, Khabarovsk Territory, and Walter Janous from Innsbruck (Austria).

⟦folio 29⟧

How to come up with a new task?

Nothing could be simpler. Let us select, for example, $a, b$ and $c$ so that the expression $f(n) = an + b + c \cdot 9^n$ belongs to (whatever!) integer values ​​for $n = -1$, $n = 0$ and $n = 1$. then by Theorem 2 (for $k = 2$) the number $f(n)$ will be an integer for any integer $n \geq -1$.

Let's take, say, $f(-1) = -1$, $f(0) = 0$, $f(1) = 4$. Having solved the system

$$\begin{cases}
-a + b + c/9 = -1, \\
b + c = 0, \\
a + b + 9c = 4.
\end{cases}$$

we will find $a = \frac{5}{8}$, $b = -\frac{27}{64}$, $c = \frac{27}{64}$.

This is probably exactly how example d) was invented a long time ago. We advise the reader to come up with a few new examples himself.

But our path is not over yet: we would like to generalize the theorem so that it also includes examples where there are several geometric progressions.

Sum of progressions

Try to prove this analogue of our Theorems 1 and 2:

Theorem 3. If $q_1, q_2, \dots, q_r$ are integers $u$
$f(n) = c_1 q_1^n + c_2 q_2^n + \dots + c_{r-1} q_{r-1}^n + c_r q_r^n$
is an integer for $n = 1, 2, \dots, r$, then $f(n)$ is an integer for any natural number $n$.
(Lemma 1 is a special case of the theorem for $r = 2, q_2 = 1$).

Note. To prove Theorem 3, it is useful to consider the difference $g(n) = f(n+1) - q_r f(n)$. Since $g(n) = c_1 (q_1 - q_r) q_1^n + \dots + c_{r-1} (q_{r-1} - q_r) q_{r-1}^n$ is the sum of $r-1$ geometric progressions and in the conditions of the theorem the number $g(n)$ is an integer for $1 \leq n \leq r-1$, the theorem can be proven by induction on $r$: after all
$$f(n) = g(n-1) + q_r g(n-2) + \\
+ q_r^2 g(n-3) + \dots + q_r^{n-1} g(1) + q_r^n f(1).
$$
(Tak, in problem 3) we can consider the difference $f(n+1) - 45f(n)$.

Exercise 1. Check examples a), e) using Theorem 3 and come up with some new examples for it.

We hope that we have awakened the reader's passion for generalizations, and we offer him the following, more difficult exercises:

2. Form and prove analogues of Theorems 1–3

a) for the sum $r$ of progressions and a polynomial of degree $k-1$;

6) for the product of a progression (with an integer value) by a polynomial.

Come up with some examples to apply your theorems.

3. What more general theorem of this type can you formulate?

4. Is it possible, under the conditions of our theorems, to reduce the number of points at which verification is required?

5. Prove the statement and and state the generalization and and state the generalization is proven more clearly and simply than the particular one. An excellent illustration of this is the following theorem, which is rather cumbersome in formulation, but generalizes the previous ones and allows you to answer all the questions in exercises 2–5.

Theorem 4. Let the expression $f(n)$ be the sum of $r$ polynomials multiplied by some geometric progression. Let's construct a polynomial with leading coefficient 1, the roots of which are the denominators of these $r$ progressions, and the multiplicity of each root is one greater than the degree of the corresponding polynomial. (The degree $k$ of this characteristic polynomial is equal to the sum of the number $r$ of progressions and the degree of all the polynomials by which they are multiplied.) If (1) all coefficients of the characteristic polynomial are integers and (2) the values of $f(n)$ are integers at $n=1, 2, \dots, k$, where $k$ is the degree of the characteristic polynomial, then $f(n)$ will be intact even with all natural $n>k$.

Of course, for condition (1) to be fulfilled, it is sufficient (but not necessary) that all the indicated progressions be integers. What is the role of the coefficients of a characteristic polynomial is clear from the following obvious important lemma, the verification of which we leave to the reader:

⟦folio 30⟧

Lemma 2. Let
$$f(x) = B_1(x)q_1^x + B_2(x)q_2^x + \dots + B_r(x)q_r^x,$$
(3)
food $B_i(x)$ is a polynomial of degree $k_i-1$ ($i=1, 2, \dots, r$), and
$$D(\lambda) = (\lambda-q_1)^{k_1}(\lambda-q_2)^{k_2} \dots (\lambda-q_r)^{k_r} = \lambda^k + d_1\lambda^{k-1} + d_2\lambda^{k-2} + \dots + d_{k-1}\lambda + d_k.$$
Then food for all $x$ the equality is fulfilled:
$$f(x) + d_1f(x-1) + d_2f(x-2) + \dots + d_kf(x-k) = 0.$$

Theorem 4 follows from here immediately: if all coefficients $d_1, \dots, d_k$ are characterized by the polynomial $D(\lambda)$ - integers, then from equality (3) it follows that $f(n)$ for each $n > k$ is obtained by adding the integer values ​​$f(n-1), f(n-2), \dots, f(n-k)$ multiplied by fixed integer coefficients.

To illustrate, consider two cutting examples.

e) Let $f(n) = \frac{1}{2} \cdot 4^n + (-9n^2 + 21n-14) \cdot 1^n$. Here $D(\lambda) = (\lambda-4)(\lambda-1)^3 = \lambda^4 - 7\lambda^3 + 15\lambda^2 - 13\lambda + 4$. Pozny for everyone $n$
$$f(n) = 7f(n-1) - 15f(n-2) + 13f(n-3) - 4f(n-4).$$

In particular, after $f(1) = f(2) = f(3) = 0$ and $f(4) = 54$ there are $f(5) = 7 \cdot 54 = 378$, $f(6) = 7 \cdot 378 - 15 \cdot 54 = 1836, \dots$; Naturally, they will all be divisible by 27 (hereinafter by 54).

i) Let $f(n) = \frac{(6+\sqrt{31})^n}{10} + \frac{(6-\sqrt{31})^n}{10} - \frac{2^n}{10}$. Here the coefficients of the polynomial $D(\lambda) = (\lambda^2 - 12\lambda + 5)(\lambda-2) = \lambda^3 - 14\lambda^2 + 19\lambda - 10$ are also integers. Following the first terms $f(0) = \frac{1}{10}, f(1) = 1, f(2) = 13$, all further $f(n)$ are determined by recursive correspondence
$$f(n) = 14f(n-1) - 19f(n-2) + 10f(n-3).$$

In particular, $f(3) = 14 \cdot 13 - 19 \cdot 1 + \frac{10}{10} = 124$ is an integer, therefore, all $f(n)$ with $n=4, 5, \dots$ will also be integers.

As a final exercise, we invite the reader to understand how, using Lemma 2, one can prove the partial cases of Theorem 4 discussed
