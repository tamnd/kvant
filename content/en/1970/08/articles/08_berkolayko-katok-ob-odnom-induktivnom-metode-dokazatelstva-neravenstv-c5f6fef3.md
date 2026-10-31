---
id: 1970-8-berkolayko-katok-ob-odnom-induktivnom-metode-dokazatelstva-neravenstv-c5f6fef3
issue: kvant_1970_8
year: 1970
number: "8"
title: On one inductive method for proving inequalities
authors:
  - Берколайко С. Т.
  - Каток С. Б.
rubric: raznoe
page_first: 35
page_last: 38
page_labels: 33, 34, 36
tag: 77TL
lang: en
source: kvant_digital
extraction: vision
content_sha256: c0f29b207b93677ec84a70c78b4cb14184ac67e2bcfda8aab3a790bf24df353e
prompt_sha256: draft-1
translated_from: content/ru/1970/08/articles/08_berkolayko-katok-ob-odnom-induktivnom-metode-dokazatelstva-neravenstv-c5f6fef3.md
source_content_sha256: 6f4d9a2f9d09e38d95b6d58331bf71718fc154ce47859013578e568aa504621a
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 33⟧

One inductive method for proving inequalities

S. T. Berkolaiko,
S. B. Skating rink

The arithmetic mean and geometric mean theorem, which states that for any positive $x_1, x_2, \dots, x_n$ the inequality

$$\frac{1}{n} (x_1 + x_2 + \dots + x_n) \geq \sqrt{x_1 x_2 \dots x_n},$$

is one of those mathematical facts whose proofs are less known than their formulations. (Other examples of this kind: in arithmetic - the only factorization of a number into prime factors; in geometry - the theorem that the altitudes of a triangle intersect at one point.) Meanwhile, there are many different ways to prove this remarkable inequality, including elementary ones (for example, in [1] (solution to problem 268) 3 elementary proofs are given, and at the beginning of [5] 12 different proofs are proposed). This note provides another short proof by induction, which also works for other positive inequalities.

We must prove that

$$x_1 + \dots + x_n \geq n (x_1 \dots x_n)^{\frac{1}{n}}$$

(1)

for all integers $n \geq 2$ and positive $x_1, \dots, x_n$.

For $n=2$ this inequality looks like this:

$$x_1 + x_2 \geq 2 (x_1 x_2)^{\frac{1}{2}}$$

(2)

and immediately follows from the obvious inequality

$$(x_1^{\frac{1}{2}} - x_2^{\frac{1}{2}})^2 \geq 0.$$

Let us assume that inequality (1) is true for $n=k$ and prove it for $n=k+1$.

To do this, consider the following expression:

$$x_1 + x_2 + \dots + x_k + x_{k+1} + (k-1) (x_1 x_2 \dots x_{k+1})^{\frac{1}{k+1}}.$$

Divide this sum into two, $k$ terms, and estimate which of them, applying inequality (1) for $n=k$:

$$x_1 + x_2 + \dots + x_k \geq k (x_1 \dots x_k)^{\frac{1}{k}},$$

$$x_{k+1} + (k-1) (x_1 \dots x_{k+1})^{\frac{1}{k+1}} \geq k (x_{k+1} x_1^{\frac{k-1}{k+1}} \dots x_{k+1}^{\frac{k-1}{k+1}})^{\frac{1}{k}}.$$

We consider $(k-1) (x_1 x_2 \dots x_{k+1})^{\frac{1}{k+1}}$ as the sum of $(k-1)$ identical terms $(x_1 x_2 \dots x_{k+1})^{\frac{1}{k+1}}$.

⟦folio 34⟧

Applying inequality (2) to the right-hand sides of the two inequalities stated above, we obtain

$$k \left(x_1 \dots x_k\right)^{\frac{1}{k}} + k \left(x_{k+1} x_1^{\frac{k-1}{k+1}} \dots x_k^{\frac{k-1}{k+1}}\right)^{\frac{1}{k}} \geq 2k \left(x_1 \dots x_{k+1}\right)^{\frac{1}{k+1}},$$

where

$$x_1 + x_2 + \dots + x_{k+1} \geq (k + 1) \left(x_1 x_2 \dots x_{k+1}\right)^{\frac{1}{k+1}}.$$

To get a feel for this algebraic transformation, let's see what it looks like for $n=3$:

$$x_1 + x_2 + x_3 + \left(x_1 x_2 x_2\right)^{\frac{1}{3}} \geq 2 \left(x_1 x_2\right)^{\frac{1}{2}} + 2 \left(x_1^{\frac{1}{3}} x_2^{\frac{1}{3}} x_3^{\frac{4}{3}}\right)^{\frac{1}{2}} \geq$$

$$\geq 2 \cdot 2 \left[ \left(x_1 x_2\right)^{\frac{1}{2}} \left(x_1^{\frac{1}{3}} x_2^{\frac{1}{3}} x_3^{\frac{4}{3}}\right)^{\frac{1}{2}} \right]^{\frac{1}{2}} \geq 4 \left(x_1 x_2 x_3\right)^{\frac{1}{3}},$$

whence $x_1 + x_2 + x_3 \geq 3 \left(x_1 x_2 x_3\right)^{\frac{1}{3}}$. Here inequality (2) was used three times.

In approximately the same way one can prove the following inequality:

a) $a_1^p + a_2^p + \dots + a_n^p \geq n \left(\frac{a_1 + a_2 + \dots + a_n}{n}\right)^p$,

where $n$ and $p$ are natural numbers, $a_i > 0$ ($i = 1, 2, \dots, n$);

b) $\sin \alpha_1 + \sin \alpha_2 + \dots + \sin \alpha_n \leq n \sin \left(\frac{\alpha_1 + \alpha_2 + \dots + \alpha_n}{n}\right)$,

where $0 < \alpha_i < \frac{\pi}{2}$ ($i = 1, 2, \dots, n$);

b) $\sin \alpha_1 \sin \alpha_2 \dots \sin \alpha_n \leq \sin^n \left(\frac{\alpha_1 + \alpha_2 + \dots + \alpha_n}{n}\right)$,

where $0 < \alpha_i < \frac{\pi}{2}$ ($i = 1, 2, \dots, n$);

d) $\frac{1}{a_1^p} + \frac{1}{a_2^p} + \dots + \frac{1}{a_n^p} \geq \frac{n}{\left(\frac{a_1 + a_2 + \dots + a_n}{n}\right)^p}$,

where $p$ and $n$ are natural numbers, $a_i > 0$ ($i = 1, 2, \dots, n$);

e) $(a_1 + b_1) (a_2 + b_2) \dots (a_n + b_n) \geq \left(\sqrt[n]{a_1 a_2 \dots a_n} + \sqrt[n]{b_1 b_2 \dots b_n}\right)^n$,

where $a_i > 0, b_i > 0$ ($i = 1, 2, \dots, n$).

⟦folio 36⟧

In words, prove the required inequality only for $n=2$.

And if we prove the upward convexity of the function $\lg x$ (which is evidence of the proof of inequality (2)), then from our theorem, as one of the special cases, we obtain a theorem about the arithmetic mean and the geometric mean:

$$\lg \left( \frac{x_1 + \ldots + x_n}{n} \right) \leq \frac{\lg x_1 + \ldots + \lg x_n}{n},$$

i.e.

$$\lg \left( \frac{x_1 + \ldots + x_n}{n} \right) \leq \lg \left( x_1 \ldots x_n \right)^{\frac{1}{n}}, \quad \frac{1}{n} \left( x_1 + \ldots + x_n \right) \leq \left( x_1 \ldots x_n \right)^{\frac{1}{n}}.$$

In conclusion, we will provide a list of books in which you can read other proofs of the arithmetic mean and geometric mean theorem.

[1] D. O. Shklyarsky, N. N. Chentsov, I. M. Yaglom, Selected problems and theorems of elementary mathematics, Part I, M., “Nauka”, 1965.

Consider the first of three proofs given in this book (“By Reverse Indication”).

[2] Kretschmar, Algebra Problem Book. M., “Science”, 1968.

[3] E. Beckenbach and R. Belman, Introduction to Inequalities, M., “Mir”, 1965.

[4] G. G. Hardy, D. E. Littelwood, G. Polyana, Inequalities, IL, 1948.

[5] E. Beckenbach and R. Belman, Inequalities, M., “World”, 1965.

Exercises

1. What inequality results if we apply the theorem to the function $y=x^2$? Try to prove this inequality directly.

2. Derive from the general theorem inequalities a)-e). What functions need to be proven to be convex for this?

3. Come up with a few more examples of convex functions and write down the inequality that follows from Theorem 1 when applied to these functions.

4. The function $f$ is defined on the interval $[a, b]$ and has an inverse**) function $g$. Prove that if $f$ is convex upward, then $g$ is convex downward, and vice versa.

5. The function $f(x)$, defined on the interval $[a, b]$, is convex upward. Prove that for any points $x_1, \ldots, x_n$ lying on the segment $[a, b]$ and any positive points $a_1, \ldots, a_n$ the following inequality holds:

$$\frac{a_1 f(x_1) + \ldots + a_n f(x_n)}{a_1 + \ldots + a_n} \leq f\left(\frac{(a_1 x_1 + \ldots + a_n x_n)}{a_1 + \ldots + a_n}\right).$$

(Note that this problem is a generalization of the previously proven theorem, which is obtained for $a_1=a_2=\ldots=a_n=1$.)

Note. To solve this problem, you can use the same technique that we use when proving the theorem.

*) You can take the logarithm to any base greater than one.
**) See «Kvant», No. 1, page 22.
