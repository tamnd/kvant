---
id: 1974-3-gerver-20-zadach-na-predelyi-cc0406dc
issue: kvant_1974_3
year: 1974
number: "3"
title: 20 limit problems
authors:
  - Гервер М. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 29
page_last: 33
page_labels: 27, 28, 30, 31
tag: QO67
lang: en
source: kvant_digital
extraction: vision
content_sha256: af37267d4fb197f6019e59546f14f6c0e16f9e5cbf1e125b20909a66f074e024
prompt_sha256: draft-1
translated_from: content/ru/1974/03/articles/14_gerver-20-zadach-na-predelyi-cc0406dc.md
source_content_sha256: e402d349b78a7ddafa566a63c103f1c2f1f4193d23a46a5fb4a817850baf4450
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

20 challenges to the limits

M.P. Gerver

Many people probably know the definition of the limit of a sequence: “A number a is called the limit of the sequence $x_n$ if for any $\varepsilon > 0$ there is a $N$ such that for all $n > N...$. But it’s one thing to remember it, and quite another thing to be able to handle it freely, prove theorems, without getting confused with all the “there is”, “for anyone”, etc. This is perhaps the biggest step on the path to “higher mathematics”, which not only schoolchildren, but also students have difficulty surmounting.

If you manage to solve the problems that are collected in this article - or at least understand their solutions - then further mathematical analysis will be much easier and more interesting for you.

1. Prove that for any natural number $n$
a) $\frac{1}{2 \cdot 3} + \frac{1}{3 \cdot 4} + \dots + \frac{1}{n(n+1)} = \frac{1}{2} \cdot \frac{n-1}{n+1}$;
b) $\frac{1}{n+1} + \frac{1}{n+2} + \dots + \frac{1}{2n} \geq \frac{1}{2}$.

In what follows, we will use the letter $n$ to denote only natural numbers.

2. a) Prove that you can find $n$ such that $2^n > 10^{10}$.
b) Prove that you can find $k$ such that for any $n > k$ $1 + a)^n \geq 1 + na$ is true.
b) Prove that you can find $k$ such that for any $n > k$ $10^n > n^{10}$ is true.
d) Let $|q| < 1$. Prove that you can find $k$ such that for any $n > k$ $|q|^n < 10^{-10}$ is true.
e) Is there a positive number such that for any $n$ it is less than $1/n$?

e) Let $|q| < 1$. Prove that for any $\varepsilon > 0$ there is a $k$ such that for any $n > k$ $\left|q\right|^n < \varepsilon^*$ is true.
g) Is it possible to find $k$ such that for any $n > k$ and for any $\varepsilon > 0$ the equality $\left(\frac{1}{2}\right)^n < \varepsilon$ holds?
Then ee. Comparing 2e and 2g, we see that the word order is thing!
h) Set $s_n = \frac{1}{2} + \frac{1}{4} + \frac{1}{8} + \dots + \frac{1}{2^n}$. Prove that for any $\varepsilon > 0$ there is a $k$ such that for any

*) $\varepsilon$ is a Greek letter, read: “episilon”, usually used to denote small positive numbers. The exact meaning of the word “small numbers” is available - what does “small” mean: 0.01 or $10^{-10}$? So they say; “for any $\varepsilon > 0$” - meaning by this usually: “no matter how small it may be.” 1In relation to the problem it is said very much: center: put $\varepsilon = 0,01$, then find a $k$ such that for any $n > k$ there will be $|q|^n < 0,01$; put $\varepsilon = 10^{-10}$, then find another $k$ (larger) such that for every $n$ greater than this new $k$, there will be $|q|^n < 10^{-10}$; in general, for any $\varepsilon > 0$ (no matter how small it may be), you can choose a $k$ (maybe very large), such that for any $n > k$ there will be $|q|^n < \varepsilon$.

⟦folio 28⟧

bogo $n > k$
$$|s_n - 1| < \varepsilon.$$
Number sequences. Let's write some number: $x_1$, then another: $x_2$, then a third: $x_3$, etc.

We will get a number sequence
$$x_1, x_2, x_3, \dots, x_n, \dots$$
The number next to the letter $x$ indicates where the number is in the sequence: $x_1$ - on the 1st, $x_2$ - on the 2nd, $\dots$, $x_n$ - on the $n$, $\dots$.

In short, it is denoted by the symbol $\{x_n\}$. Of course, other letters can be used to denote sequences: $\{s_n\}, \{y_n\}, \{z_n\}$, etc.

Let's write down a dozen sequences used in the following tasks:

(1) $1, \frac{1}{2}, \frac{1}{3}, \frac{1}{4}, \dots$

(2) $1, 0, \frac{1}{2}, 0, 0, \frac{1}{3}, 0, 0, 0, \frac{1}{4}, 0, 0, 0, 0, \dots$

(3) $\{s_n\}, s_n = \frac{1}{2} + \frac{1}{4} + \frac{1}{8} + \dots + \frac{1}{2^n}$.

(4) $\{y_n\}, y_n = \frac{1}{2} - \frac{1}{4} + \frac{1}{8} - \dots - \frac{(-1)^n}{2^n}$.

(5) $1, 1, 1, 1, \dots$.

(6) $1, -1, 1, -1, \dots$.

(7) $1, \frac{1}{2}, 1, \frac{1}{3}, 1, \frac{1}{4}, 1, \frac{1}{5}, \dots$.

(8) $1, -\frac{1}{2}, \frac{1}{3}, -\frac{1}{4}, \frac{1}{5}, -\frac{1}{6}, \dots$.

(9) $\frac{1}{1}, \frac{1}{1}, \frac{1}{2}, \frac{1}{1}, \frac{1}{3}, \frac{1}{1}, \dots, \frac{1}{9}, \frac{1}{1}, \frac{1}{10}, \frac{1}{2}, \frac{1}{11}, \frac{1}{2}, \dots, \frac{1}{99}, \frac{1}{2}, \frac{1}{100}, \frac{1}{3}, \dots$

(the denominator of a fraction in an even place is equal to the number of digits of the denominator of the previous fraction).

(10) $\frac{1}{2}, \frac{2}{1}, \frac{2}{3}, \frac{3}{2}, \frac{3}{4}, \frac{4}{3}, \frac{4}{5}, \frac{5}{4}, \dots$

Definition 1. The number $a$ is called *the limit of the sequence* $\{x_n\}$ if for any $\varepsilon > 0$ there is a $k$ such that for any $n > k$
$$|a - x_n| < \varepsilon.$$
The fact that the number $a$ is the limit of $\{x_n\}$ is written like this:
$$\lim_{n \to \infty} x_n = a$$
(reads: “the limit of $x_n$ as $n$ tends to infinity is equal to $a$”) or like this:
$$x_n \rightarrow a \text{ при } n \rightarrow \infty$$
(reads: "$x_n$ tends to $a$ as $n$ tends to infinity"). In some countries, the mention of $n$, tending to infinity, is omitted and simply written:
$$\lim x_n = a \text{ при } x_n \rightarrow a.$$
Sequences that have a limit are called *convergent*.

3. a) Form problems 2e and 23 using definition 1.

6) Prove that 0 is the limit of the sequence (1), (2), (8) and (9).

b) Find the limit of the sequence (3), (4) and (10).

d) Prove that 1 is not the limit of sequence (1).

d) Do the sequences (5), (6) and (7) have limits?

e) Let $x_n - n$ be a term of sequence (9). Specify $k$ such that the inequality $x_n < \frac{1}{2}$ holds for $n > k$.

g) Can two different numbers be limits of the same sequence?

4. Let $\{x_n\}$ be an arbitrary sequence. Let's write down some

⟦folio 30⟧

About the limit 4. They say that the sequence $\{x_n\}$ tends to infinity (this is written like this: $x_n \to \infty$ for $n \to \infty$) if for any $C$ there is a $k$ such that for any $n > k$ $|x_n| > C$.

7. Which of the following sequences are towards infinity and which are unbounded?

a) $x_n = n$, $6)$ $x_n = (-1)^n \cdot n$,
b) $x_n = n^{(-1)^n}$
g) $x_n = \begin{cases} n^2 \text{ при } n \text{ четном,} \\ \sqrt{n} \text{ при } n \text{ нечетном.} \end{cases}$

On the limit 5. The number $a$ is called a *limit point* of the sequence $\{x_n\}$ if for any $\varepsilon > 0$ and for any $k$ there is a $n > k$ such that $|a - x_n| < \varepsilon$.

8. Prove a) that the limit of a convergent sequence is its limit point,
6) that if $x_n \to a$ and $b \neq a$, then $b$ is not a limit point of $\{x_n\}$.
b) that if $a$ is a limit point of $\{x_n\}$, then $\{x_n\}$ contains a subsequence converging to $a$.

9. Come up with a sequence $\{x_n\}$ whose limit points are:
a) all natural numbers (and only them),
b) all numbers $1/n$,
b) all rational numbers.

10. a) Come up with a sequence that satisfies Problem 9a, but does not contain integers.
6) Let $\{x_n\}$ satisfy Problem 96. Is it possible for 0 not to be its limit point?
b) List all limit points of the sequence satisfying Problem 9b.

16 conditions. “Apu” in English means “any”, “Exist” means “to exist”. The symbols $\vee$ and $\exists$ - reverse the 1st letters of these words - respectively:
“for anyone” and “there is something ... that.”
Consider the following 16 conditions:

1) $\exists \varepsilon > 0 \exists k \exists n > k |x_n - a| < \varepsilon$,
2) $\exists \varepsilon > 0 \exists k \exists n > k |x_n - a| \geqslant \varepsilon$,
3) $\exists \varepsilon > 0 \exists k \forall n > k |x_n - a| < \varepsilon$,
4) $\exists \varepsilon > 0 \exists k \forall n > k |x_n - a| \geqslant \varepsilon$,
5) $\exists \varepsilon > 0 \forall k \exists n > k |x_n - a| < \varepsilon$,
6) $\exists \varepsilon > 0 \forall k \exists n > k |x_n - a| \geqslant \varepsilon$,
7) $\exists \varepsilon > 0 \forall k \forall n > k |x_n - a| < \varepsilon$,
8) $\exists \varepsilon > 0 \forall k \forall n > k |x_n - a| \geqslant \varepsilon$,
9) $\forall \varepsilon > 0 \exists k \exists n > k |x_n - a| < \varepsilon$,
10) $\forall \varepsilon > 0 \exists k \exists n > k |x_n - a| \geqslant \varepsilon$,
11) $\forall \varepsilon > 0 \exists k \forall n > k |x_n - a| < \varepsilon$,
12) $\forall \varepsilon > 0 \exists k \forall n > k |x_n - a| \geqslant \varepsilon$,
13) $\forall \varepsilon > 0 \forall k \exists n > k |x_n - a| < \varepsilon$,
14) $\forall \varepsilon > 0 \forall k \exists n > k |x_n - a| \geqslant \varepsilon$,
15) $\forall \varepsilon > 0 \forall k \forall n > k |x_n - a| < \varepsilon$,
16) $\forall \varepsilon > 0 \forall k \forall n > k |x_n - a| \geqslant \varepsilon$.

11. Which of these conditions express properties of a sequence already familiar to you (to be limited, to have $a$ as a limit or limit point, to tend to infinity) or the negation of these properties? What is the meaning of the remaining conditions?

About the limit 6. The sequence $\{x_n\}$ is called *monotonous* if one of two conditions is satisfied:
1) $x_1 \leqslant x_2 \leqslant x_3 \leqslant \dots \leqslant x_n \leqslant \dots$,
2) $x_1 \geqslant x_2 \geqslant x_3 \geqslant \dots \geqslant x_n \geqslant \dots$.
In the first case, $\{x_n\}$ is called *increasing*, in the second - *decreasing*.

12. a) Prove that any sequence contains a monotonic subsequence.
6) Prove that the limit point of a monotonic sequence is its limit.
b) Prove that every monotonic bounded sequence has a limit (sometimes this property of real numbers is taken as an axiom).
13. a) Prove that every bounded sequence has at least one limit point.
6) Check that statements 12c and 13a are equivalent: each can be deduced from the other (so 13a can also be taken as an axiom).
14. a) Let $|q| < 1$, $s_n = 1 + q + \dots + q^{n-1}$. Prove that the sequence $\{s_n\}$ converges, and

⟦folio 31⟧

find its limit.

6) Check that for $|q| \geq 1$ the sequence $\{s_n\}$ has no limit.

15. Let $x_n \rightarrow a$, $y_n \rightarrow b$ at $n \rightarrow \infty$. Prove that then

a) $x_n + y_n \rightarrow a + b$,
b) $x_n - y_n \rightarrow a - b$,
c) $x_n y_n \rightarrow ab$,
d) if $b \neq 0$, then $x_n/y_n \rightarrow a/b$.

Sweeping. Among $y_n$ there may be zeros, but if $b \neq 0$ there are (prove this) only a finite number: $\exists N \forall n > N y_n \neq 0$; the sequence $x_n/y_n$ depends on the limit, thus for $n > N$.

e) If $b = 0$, then the sequence $x_n/y_n$ (if it is defined) may not have a limit, may tend to any number or to infinity—give relevant examples.

16. a) Prove that if $x_n \geq 0$ for all $n$ and $x_n \rightarrow a$ for $n \rightarrow \infty$, then $a \geq 0$.

6) Is it possible to say that $\lim_{n \rightarrow \infty} x_n > 0$ if everything is $x_n > 0$?

b) Let $x_n \leq y_n \leq z_n$, and let $x_n \rightarrow a$ and $z_n \rightarrow a$ with $n \rightarrow \infty$. Prove that then $y_n \rightarrow a$ for $n \rightarrow \infty$.

17. a) The sequence $\{x_n\}$ has the following property: for any $\varepsilon > 0$ there is a $k$ such that for any $n > k$ and any natural number $p$
$$|x_{n+p} - x_n| < \varepsilon.$$
Prove that then $\{x_n\}$ has a limit.

6) Prove the converse: if $x_n$ is a convergent sequence, then $\forall \varepsilon > 0 \exists k \forall n > k \forall p |x_{n+p} - x_n| < \varepsilon.$
b) The sequence $\{x_n\}$ has the following property: $\forall \varepsilon > 0 \exists k \forall n > k |x_{n+p} - x_n| < \varepsilon.$
Is $\{x_n\}$ obligated to the property?

18. Let's construct the sequence $\{x_n\}$ like this: $|x_n| = 1/2^n$, choose the signs $x_1, x_2, x_3, \dots$ arbitrarily. Next we put $s_n = x_1 + \dots + x_n$.

a) Prove that the sequence $\{s_n\}$ converges.

6) List all the values ​​that $\lim_{n \rightarrow \infty} s_n$ can take (when the signs $x_n$ are chosen in all sorts of different ways).

Complex $\{x_n\}$. So far we have considered sequences consisting of real numbers.

Now let $x_n$ be any complex numbers.

The definition of the limit in this case is literally the same as before. But its geometric meaning is different: inequality $|x_n - a| < \varepsilon$ now means that $x_n$ lies inside a circle of radius $\varepsilon$ with center at point $a$; Consequently, the number $a$ serves as a limit to $\{x_n\}$, if all of any circle with center $a$ lies only a finite number $\{x_n\}$.

19. a) Let $x_n = a_n + ib_n$. The sequence $\{x_n\}$ converges if and only if the sequences $\{a_n\}$ and $\{b_n\}$ converge. Prove it.

6) Let $|x_n| = r_n$, arg $x_n = \alpha_n$. Is it true that $\{x_n\}$ converges if and only if both $\{r_n\}$ and $\{\alpha_n\}$ converge?

20. Let the sequence $\{x_n\}$ tend to 0. Let us construct the sequence $\{s_n\}$ like this:
$$s_1 = x_1, \quad s_2 = x_1 + x_2, \dots, \quad s_n = x_1 + x_2 + \dots + x_n, \dots$$
Find out whether $\{s_n\}$ can have exactly two limit points:

a) if $x_n$ are real numbers,
b) if $x_n$ are complex numbers (in this case the definition of the limit point is literally the same as before).
