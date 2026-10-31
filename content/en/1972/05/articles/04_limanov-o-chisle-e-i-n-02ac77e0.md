---
id: 1972-5-limanov-o-chisle-e-i-n-02ac77e0
issue: kvant_1972_5
year: 1972
number: "5"
title: About the number e and n!
authors:
  - Лиманов Л. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 16
page_last: 21
page_labels: 14, 15, 16, 18
tag: YNV0
lang: en
source: kvant_digital
extraction: vision
content_sha256: b28a902fab9340e29952394bfddee4650f29492a7955c3c2301cddd42bc5f91e
prompt_sha256: draft-1
translated_from: content/ru/1972/05/articles/04_limanov-o-chisle-e-i-n-02ac77e0.md
source_content_sha256: c3a0815a4d01d792946f6e0a0c627ea58e2f4726c450a2980de7d5d0c522d0e8
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

About the number e and n!
L. G. LIMANOV

In this note we will analyze problems from M.I. Bashmakov’s article “On Bertrand’s Arrival” (see «Kvant» No. 5, 1971).

Recall that Bertrand's procedure is called the following iteration: if $x > 1$, then there is a prime number between $x$ and $2x$.

This statement was formulated by the French mathematician Bertrand, but he was unable to find evidence for it. Chebyshev managed to do this, and to do it quite simply. True, he used one non-elementary formula - the Stirling formula:

$$n! = \sqrt{2\pi n} \left(\frac{n}{e}\right)^n e^{\theta_n/12n},$$

where $0 < \theta_n < 1$.

This formula includes two perhaps the most remarkable numbers. The first is the well-known number $n$ - the ratio of the circumference of a circle to its diameter. the second number is the number $e$—the limit of the sequence $\left(\frac{n+1}{n}\right)^n$ as $n$ tends to infinity. Chebyshev needed this formula in order to estimate the values ​​of $n! = 1 \cdot 2 \cdot \dots \cdot n$.

In fact, to prove Bertrand's action, one can use significantly less accurate estimates of the value $n$!

It is these estimates that the reader was asked to prove in Bashmakov’s article (task 3). We will teach you by analyzing this problem.

Here is its wording:

Prove that there exists a real number $e$ such that for all natural $n$, large non-comoroso $n_0$,

$$\left(\frac{n+1}{e}\right)^n < n! < n \left(\frac{n}{e}\right)^n.$$

The $\left(\frac{n+1}{e}\right)^n < n! < n \left(\frac{n}{e}\right)^n$ inequalities can be used together with the Stirling formulas. They are, of course, less accurate, but they are much easier to prove.

The remaining problems from the article are, in fact, lemmas from Chebyshev's proof of Bertrand's procedure. Solving them is much easier than Problem 3. Chebyshev's merit is not that he solved them - this is not difficult to do - but that he formulated them and found how, using these statements, to obtain estimates for the product (and, thereby, for the quantity) of prime numbers not exceeding $x$, and to prove Bertrand's procedure.

Solution of Problem 3. Reception without proof yet, what is the number $e$, that for all natural $n$,

$$\left(\frac{n+1}{n}\right)^n < e < \left(\frac{n+1}{n}\right)^{n+1},$$

really exists. (The proof of existence will be given below.)

⟦folio 15⟧

We want to prove that $\left(\frac{n+1}{e}\right)^n < n! < n \left(\frac{n}{e}\right)^n$ or (which is the same)
$\frac{(n+1)^n}{n!} < e^n < \frac{n^n}{(n-1)!}$ for $n$ greater than some $n_0$.

Let it be proven for some $k$ that $\frac{(k+1)^k}{k!} < e^k$. But
$\frac{(k+2)^{k+1}}{(k+1)!} / \frac{(k+1)^k}{k!} = \left(\frac{k+2}{k+1}\right)^{k+1} < e$. Therefore $\frac{(k+2)^{k+1}}{(k+1)!} < e^{k+1}$.

Thus, our statement is true for $k+1$, and therefore also for $k+2, k+3$, etc. Similarly, from the assumption

$$e^k < \frac{k^k}{(k-1)!}$$

it is concluded that

$$e^{k+1} < \frac{(k+1)^{k+1}}{(k)!}.$$

Really,

$$\frac{(k+1)^{k+1}}{k!} / \frac{k^k}{(k-1)!} = \left(\frac{k+1}{k}\right)^{k+1} > e.$$

It remains to prove that $e$ exists and find the initial values ​​for $n$ in each of the inequalities

$$\left(\frac{n+1}{e}\right)^n < n!, n! < n \left(\frac{n}{e}\right)^n.$$

Proof of the existence of $e$

Conditions to call the set of real numbers $x$ satisfying the inequality $a \leqslant x \leqslant b$ a segment with endpoints $a$ and $b$ (a segment with endpoints $a$ and $b$ is denoted by $[a, b]$).

When proving the existence of the number $e$, we will use the following properties of real numbers: if there is a sequence of segments $[a_i, b_i]$, where $a_i \leqslant a_{i+1} < b_{i+1} \leqslant b_i$ ($i=1, 2, \dots$) (such a sequence is said to be a sequence of nested segments), then there is a point $\alpha$ common to all these segments.

We will not prove this property. The fact is that with a clear definition of what we understand by the set of real numbers, this (or some equivalent) property is accepted as an axiom.

Exercises

1. Check that the following properties of real numbers are equivalent; If you accept any of them without proof, then the rest are deduced from it.
a) Every sequence of nested segments has at least one common point.
b) Every bounded monotonically increasing sequence has a limit.
b) Any sequence $\{a_i\}(i=1, 2, \dots)$ in which for any $\varepsilon > 0$ one can specify a $N$ (depending, of course, on $\varepsilon$) such that $|a_n - a_m| < \varepsilon$ for $m, n > N$ has a limit. (Such sequences are called Cauchy sequences.)
r) Every set of real numbers bounded above has an exact version of the grana, that is, one can specify a number $\alpha$ such that all numbers belonging to this set are not greater than $\alpha$, but for any number $\beta$, less than $\alpha$, one can find a number from this set greater than $\beta$.
d) From any family of segments covering the segment $[a, b]$, we can select a finite family of segments covering the segment $[a, b]$. (We say that a system $M$ of segments covers the segment $[a, b]$ if for every $x$ belonging to the segment $[a, b]$ there is a segment from the system $M$ containing $x$.)

⟦folio 16⟧

Let us now show that the sequence $\left(\frac{n+1}{n}\right)^n$ is monotonically increasing. To do this, it is necessary that for any $n\left(\frac{n+1}{n}\right)^n$ there be less than $\left(\frac{n+2}{n+1}\right)^{n+1}$.

$$\left(\frac{n+1}{n}\right)^n < \left(\frac{n+2}{n+1}\right)^{n+1}$$

With the help of simple transformations, this inequality can be reduced to the following form:

$$[(n^2+2n+1)^n - (n^2+2n)^n](n+1) < (n^2+2n)^n.$$

[Here are the intermediate inequalities: $(n+1)^{2n+1} < (n+2)^{n+1}n^n$ and $(n^2+2n+1)^n(n+1) < (n^2+2n)^n(n+2)$.] Using the formula $a^k - b^k = (a-b)(a^{k-1} + a^{k-2}b + \ldots + ab^{k-2} + b^{k-1})$, we get: $(n^2+2n+1)^n - (n^2+2n)^n < n(n^2+2n+1)^{n-1}$. Therefore, inequality (1) will be proven if we prove the following inequality:

$$(n^2+2n+1)^{n-1}(n+1) < (n^2+2n)^{n-1}(n+2).$$

This in turn (it turns out to be exactly the same) follows from the inequality

$$(n^2+2n+1)^{n-2}(n+1) < (n^2+2n)^{n-2}(n+2).$$

Repeating these arguments, we are convinced that inequality (1) follows from the obvious inequality

$$n+1 < n+2.$$

It is even simpler to show that for any natural number $n$

$$\left(\frac{n+1}{n}\right)^{n+1} > \left(\frac{n+2}{n+1}\right)^{n+2}.$$

Indeed, inequality (2) is equivalent to the inequality

$$(n+1)^{2n+3} > (n+2)^{n+2}n^{n+1}.$$

It is enough for Pozny to show that

$$[(n^2+2n+1)^{n+1} - (n^2+2n)^{n+1}](n+1) > (n^2+2n)^{n+1}.$$

But

$$(n^2+2n+1)^{n+1} - (n^2+2n)^{n+1} > (n^2+2n)^{n+1}(n+1),$$

where

$$[(n^2+2n+1)^{n+1} - (n^2+2n)^{n+1}](n+1) > (n^2+2n)^{n+1}(n+1)^2 > (n^2+2n)^{n+1}(n^2+2n) = (n^2+2n)^{n+1},$$

that is, inequality (3), and therefore inequality (2), has been proven.

So, we have proven that the sequence $a_n = \left(\frac{n+1}{n}\right)^n$ is monotonically increasing, and the sequence $b_n = \left(\frac{n+1}{n}\right)^{n+1}$ is monotonically killing. Also, $a_n < b_n$ since $\frac{n+1}{n} > 1$. Thus, the sequence of segments with endpoints $a_i$, $b_i$ is a sequence of nested segments and the length of the $k$-th segment is equal to $\left(\frac{k+1}{k}\right)^k \cdot \frac{1}{k}$, that is, as $k$ grows, it tends to zero. Therefore, all these segments have exactly one common point. The corresponding number is called the number $e$.

You can calculate as many decimal places of the number $e$ as you like. Here are the first few: $e=2,71828...$

⟦folio 18⟧

1. Prove that
$$T(x) = \psi(x) + \psi\left(\frac{x}{2}\right) + \psi\left(\frac{x}{3}\right) + \dots$$

2. Prove that
$$\psi(x) = \theta(x) + \theta(\sqrt{x}) + \theta(\sqrt[3]{x}) + \theta(\sqrt[4]{x}) + \dots$$

Using the result of Problem 1, $S(x)$ can be written as follows:
$$S(x) = A_1\psi(x) + A_2\psi\left(\frac{x}{2}\right) + A_3\psi\left(\frac{x}{3}\right) + \dots$$

3. Check that the coefficients $A_1, A_2, A_3, \dots$ change with period 30 and that for the first thirty values $n$ the coefficients $A_n$ form the following sequence: 1, 0, 0, 0, 0, -1, 1, 0, 0, -1, 1, -1, 1, 0, -1, 0, 1, -1, 1, -1, 0, 0, 1, -1, 0, 0, 0, 0, 1, -1.

4. Prove that the coefficients $A_1, A_2, A_3, \dots$ change with period 30 and that for the first thirty values of $n$ the coefficients $A_n$ form the following sequence: 1, 0, 0, 0, 0, -1, 1, 0, 0, -1, 1, -1, 1, -1, 0, 0, 1, -1, 1, -1, 0, 0, 0, 0, 1, -1.

5. Prove that
$$\psi(x) - 2\psi(\sqrt{x}) \leq \theta(y) \leq \psi(x) - \psi(\sqrt{x}).$$

6. Prove that
$$\frac{\psi(x)}{\log x} < \pi(x) < \frac{\psi(x) + \theta(x)}{\log x}.$$

Solution to Problem 1. Note that $a_p = [\log_p x]$. We calculate with what coefficient $\log p$ enters the sum $\psi(x) + \psi\left(\frac{x}{2}\right) + \dots$ In $\psi\left(\frac{x}{i}\right)$ the logarithm $p$ enters with the coefficient $\left[\log_p \frac{x}{i}\right]$, which means that the total coefficient for $\log p$ is equal to $\sum_{i=1}^{\infty} \left[\log_p \frac{x}{i}\right]$. Let's subtract one from each term and transform it: $\left[\log_p \frac{x}{i}\right] - 1 = \left[\log_p \frac{x}{i} - 1\right] = \left[\log_p \frac{x_1}{i}\right]$, where $x_1 = \frac{x}{p}$. Therefore $\sum \left[\log_p \frac{x}{i}\right] = \left[\frac{x}{p}\right] + \sum \left[\log_p \frac{x_1}{i}\right]$. Repeating our transformation, we get the following equality:
$$\sum \left[\log_p \frac{x}{i}\right] = \sum_{i=1}^{\infty} \left[\frac{x}{p^i}\right].$$

So, the coefficient of $\log p$ in the sum of $\psi(x) + \psi\left(\frac{x}{2}\right) + \dots$ is equal to $\sum_{i=1}^{\infty} \left[\frac{x}{p^i}\right]$. Let us now note that $T(x) = \sum_{i \leq x} \log i$ can also be represented in this form: $T(x) = \sum_{p \leq x} c_p \log p$, where $p$ are prime numbers.

Exercises

12. Prove that if $k$ is a natural number, then $\left[\frac{x}{k}\right] = \left[\frac{x}{k}\right]$ is also true for $x > 1 [\log_h[x]] = [\log_hx]$.

⟦folio none⟧

13. Make sure that the coefficient $c_p$ is equal to

$$\sum_{i=1} \left[ \frac{[x]}{p^i} \right].$$

Note. Represent $T(x)$ as $\log([x])$.

Having solved exercises 12 and 13, solve problem 1 completely.

Solution to Problem 2. The solution to this problem is similar to the solution to Problem 1: you need to make sure that the coefficient of $p$ in the sum of $\theta(x) + \theta(\sqrt{x}) + \cdots$ is equal to $[\log_p x]$. It's quite easy to follow. $\log p$ is included as a term in $\theta(\sqrt{x})$ if $\sqrt{x} \geq p$, that is, $\log_p x \geq i$. Therefore, in $\sum \theta(\sqrt{x})$ the logarithm $p$ is included as a term $k$ times, where $k$ is determined from the inequality $k + 1 > \log_p x \geq k$, that is, $[\log_p x]$ times.

Solution to Problem 4. This problem is very similar to Problem M92 (see «Kvant» No. 7, 1971).

Indeed, it can be formulated as follows:

On the first train to Maazin, Petya bought himself a lot of small chocolates. He decided that on boring days he should eat three chocolates, on those days when he is busy with only one thing - two, and on the rest - one. Then $A_i + 2$ is equal to the number of chocolates that Petya ate on day $i + 1$. (Recall that Petya went swimming every second day, every third day went to the maazin, and every fifth day solved mathematical problems).

Here is the formula for $A_i$:

$$A_i = 1 - [2^{[i/2] - i/2}] - [2^{[i/3] - i/3}] - [2^{[i/5] - i/5}] + [2^{[i/30] - i/30}].$$

Exercises

14. Prove formula (4).
15. Derive a formula for the number of things Petya will do on the $k$th day.

From formula (4) it is immediately clear that $A_{i+30} = A_i$. Of course, you can calculate the values ​​of the first thirty coefficients yourself.

Solution to Problem 5. This problem follows from Problem 2. Indeed,

$$\psi(x) - \psi(\sqrt{x}) = \theta(x) + \theta(\sqrt{x}) + \cdots \geq \theta(x),$$

$$\psi(x) - 2\psi(\sqrt{x}) = \theta(x) - \theta(\sqrt{x}) + \cdots \leq \theta(x).$$

Solution to Problem 6. Since $a_p = [\log_p x]$,

$$a_p \log p \leq \log_p x \log p = \log x, \quad (a_p + 1) \log p > \log x.$$

Pozny

$$\psi(x) = \sum_{p \leq x} a_p \log p \leq \sum_{p \leq x} \log x = \pi(x) \log x,$$

$$\psi(x) + \theta(x) = \sum_{p \leq x} (a_p + 1) \log x > \sum_{p \leq x} \log x = \pi(x) \log x,$$

where

$$\frac{\psi(x)}{\log x} < \pi(x) < \frac{\psi(x) + \theta(x)}{\log x}.$$
