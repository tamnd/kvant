---
id: 1978-7-geyn-na-puti-k-resheniyu-0bd60bf3
issue: kvant_1978_7
year: 1978
number: "7"
title: On the way to a solution
authors:
  - Гейн А. Г.
rubric: osnovnye-stati
page_first: 12
page_last: 16
page_labels: 10-14
tag: DITD
lang: en
source: kvant_digital
extraction: vision
content_sha256: 05cdc5547b4f5f02ebbae78c6722d673804036d31c959804e977da25ff2ce46d
prompt_sha256: draft-1
translated_from: content/ru/1978/07/articles/03_geyn-na-puti-k-resheniyu-0bd60bf3.md
source_content_sha256: 22365aacc3e5f159f83da5ef277bc65256e2effd7828a12ff0947a265eb48cbc
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 10⟧

1. Repetition

- Don't you see?
- No.
- Me too!

Izagrovora Eeyore Winnie the Pooh*)

Where to start? First of all, from the answers in the school versions of the problem (n=2, 3, 4). Let's write these answers in a table:

| n = 2 | (1, 1) | (1, 2) | (2, 3) | |
| :--- | :--- | :--- | :--- | :--- |
| n = 3 | (1, 1, 1) | (1, 1, 2) | (1, 2, 3) | (2, 3, 7) |
| n = 4 | (1, 1, 1, 1) | (1, 1, 1, 2) | (1, 1, 2, 3) | (2, 3, 7, 43) |

Isn't it true that the solution for different n estimates are similar? They form vertical series and are obtained by adding units. This observation extends to all possible n using the following evaluated lemma:

Lemma 1. Let the set of numbers (x₁, x₂, ..., xₙ) be a solution to the problem for n=k. Then the set of numbers (x₁, x₂, ..., xₙ, 1) is a solution to the problem for n=k+1. And by a set: if among the k+1 numbers that are a solution to the problem for n=k+1, there is one, then by removing it from the set, we obtain a solution to the problem for n=k.

How are new series born: (2, 3), (2, 3, 7), ...?

Let (x₁, ..., xₙ) be the solution to the problem for n=k. According to the conditions of the problem, if (x₁, ..., xₙ, xₙ+1) is a solution to the problem for n=k+1, then x₁ ... xₙ+1 + 1 = Cxₙ+1, where C is some natural number. Let's try to set C equal to one (this gives the numbers 3=2+1, 7=2·3+1, 43=2·3·7+1). Let us prove the following lemma:

Lemma 2. If a set of numbers (x₁, ..., xₙ) is a solution to a problem for n=k, then a set (x₁, ..., xₙ, xₙ+1) is a solution to a problem for n=k+1.

*) All epigraphs are taken from Milne’s fairy tale “Winnie the Pooh and Everything, Everything, Everything.”

Using Lemmas 1 and 2, from each solution to the problem for n=k, two solutions to the problem for n=k+1 can be obtained. figure 1 shows how from solving the problem for n=2 using Lemma 1 (red arrows) and using Lemma 2 (blue arrows) in this way, solutions to the problem are obtained first for n=3, and then for n=4.

It does not follow from anywhere that we will get all the solutions this way. However, it is easy to prove that the set indicated at figure 1 exhausts all solutions to our problem for n=2, 3, 4. Unfortunately, from the solution for n=4, not all solutions for n=5 are obtained in this way; In addition to the solution (2, 3, 7, 43, 1807), obtained by the lattice of Lemma 2, there is also this: (2, 3, 7, 47, 395).

2. Details of the equation

Beyond that, just a teaspoon, that’s already good.

Winnie the Pooh

Lemma 1 allows us here and further not to consider solutions containing 1—everything is clear with them. Then, if the set (x₁, ..., xₙ) is a solution to the problem for n=k, then all the numbers xᵢ are different (think about why).

⟦folio 11⟧

Fig. 1.

By analyzing the answers to the problem at $n = 2, 3$ and 4, we can create hypotheses only about the structure of these answers, and not at all about how to solve the problem. Let's now see how these answers are obtained for $n = 3$.

Let $(x, y, z)$ be some solution to a problem with three numbers. Then the equalities must hold

$$\begin{cases} xy + 1 = k_1z, \\ xz + 1 = k_2y, \\ yz + 1 = k_3x, \end{cases}$$

where $k_1, k_2, k_3$ are some natural numbers.

Multiplying these ratios, we get

$$xyz (xyz + x + y + z) + xy + xz + yz + 1 = k_1k_2k_3xyz.$$

It follows that $xy + xz + yz + 1$ is divisible by $xyz$, that is

$$xy + xz + yz + 1 = Axyz,$$

where $A$ is a natural number. Dividing both sides of this equality by $xyz$, we get

$$\frac{1}{x} + \frac{1}{y} + \frac{1}{z} = A. \quad (1)$$

So, any solution to the problem for $n = 3$ satisfies equation (1). Separating ourselves from the denominator, it is easy to see that the converse is true: if $x, y, z$ are natural numbers that satisfy, for some natural $A$, equation (1), then $(x, y, z)$ is a solution to the problem for $n = 3$.

The left side of (1) takes on the greatest value for the smallest values ​​of $x, y, z$; if $2 \leq x < y < z$, then

$$A \leq \frac{1}{2} + \frac{1}{3} + \frac{1}{4} + \frac{27}{24} < 2.$$

Therefore, $A = 1$ and $x, y, z$ satisfy the equation

$$\frac{1}{x} + \frac{1}{y} + \frac{1}{z} = 1.$$

Well, the first step is very natural. Using the definition of divisibility, we use several vague words - one number is divided into concrete and familiar objects. True, new unknowns $k_1, k_2, k_3$ have appeared that were not there before, but this is a general retribution for “some definition.” And the second step is quite understandable - the desire to get rid of “extra” unknowns (by moving from a system to a single equation).

Having performed a similar operation for an arbitrary $n$, we again obtain an equation of the form

$$\frac{1}{x_1} + \frac{1}{x_2} + \dots + \frac{1}{x_n} + \frac{1}{x_1 \dots x_n} = A, \quad (2)$$

where $A$ is a natural number. Again, the converse is easy to verify:

if $x_1, x_2, \dots, x_n$ are natural numbers that satisfy, for some natural $A$, equation (2), then the set $(x_1, x_2, \dots, x_n)$ is a solution to our problem.

So, the original problem is equivalent to the problem of finding a solution to equation (2) in the smallest numbers for all possible natural numbers $A$. Promotion, of course, is not easy, but “just a little bit... that’s already good!”

Inspired by the conditions, we can try to prove that in the equation

⟦folio 12⟧

(2) $A = 1$. Since we can assume that $2 \leqslant x_1 < x_2 < \dots < x_n$, for $A$ we obtain the estimate:

$$A = \frac{1}{x_1} + \dots + \frac{1}{x_n} + \frac{1}{x_1 \dots x_n} \leqslant \frac{1}{2} + \frac{1}{3} + \dots + \frac{1}{n} + \frac{1}{n!}.$$

However, already for $n = 14$ the sum on the right side is greater than 2. But perhaps from this estimate it can still be concluded that the value $A$ is limited and therefore can take only a finite number of values? But no: the sum $\frac{1}{2} + \dots + \frac{1}{n}$ increases without limit with increasing $n$.

Exercise 1. Prove it.

Apparently our estimation method is too crude. Is it possible to incriminate him? It is clear, for example, that all numbers included in the solution are mutually prime in pairs. Therefore, in particular, if $x_1 = 2$, then $x_3 > 4$.

Let us show that the sum $\frac{1}{x_1} + \dots + \frac{1}{x_n} + \frac{1}{x_1 \dots x_n}$ can be estimated from above by the number $\frac{1}{2} + \frac{1}{3} + \frac{1}{5} + \dots + \frac{1}{p} + \frac{1}{2 \cdot 3 \cdot 5 \cdot \dots p}$, where $p$ is just a number.

Indeed, let us denote by $p_i$ some prime divisor of the number $x_i$. Note that $p_i \leqslant x_i$. Since the numbers $x_i$ are pairwise prime, all $p_i$ are distinct. We will consider them ordered by size. Then $2 \leqslant p_1, 3 \leqslant p_2, 5 \leqslant p_3$, etc. Replacing $x_i$ with $p_i$, we obtain the required estimate.

Maybe the sum of the reciprocals of prime numbers does not exceed some prime number $M$? This means that $A < M + 1$. It turns out that this is not true: with increasing quantity, the sum $\frac{1}{2} + \frac{1}{3} + \dots + \frac{1}{p}$ increases without limit *). Nevertheless, we obtain an estimate that allows us to state that $A = 1$ for all $n \leqslant 58$. There is little comfort, but at least it is clear why, when analyzing the answers, we did not come across a solution with the constant $A = 2$: it is unlikely that anyone would think of considering the problem for sixty numbers at once.

3. Adding one - nothing new

Free of charge, that is, for nothing.

Who can know in advance which path will lead to success? Patience (but not stubbornness) are the principles of research. Let's return once again to the beginning of our journey. We now have in our hands an analysis of the answers and methods for solving the problem for special cases. Lemma 1 and 2 deserve attention - they contain at least some algorithm for finding some solutions. What approach do they propose? Both lemmas talk about how to obtain a solution to the problem for $n = k + 1$ from the solution to the problem for $n = k$. This approach is quite familiar to us (remember the method of mathematical induction). Let's try, assuming that the solution problem is for $n = k$, to solve it for $n = k + 1$.

So, path $(x_1, \dots, x_k)$ is a solution to the problem for $n = k$. Let us denote the product $x_1 \dots x_k$ by $f_k$. Then $\frac{1}{x_1} + \frac{1}{x_2} + \dots + \frac{1}{x_k} + \frac{1}{f_k} = A$.

If the number $x_{k+1}$ is complemented by the set $x_1, \dots, x_k$ to solve the problem for $n = k + 1$ and $x_{k+1} \neq 1$, then there is a correspondence:

$$\frac{1}{x_1} + \dots + \frac{1}{x_k} + \frac{1}{x_{k+1}} + \frac{1}{f_k x_{k+1}} = A$$

with the same $A$ (think it through).

Equating the left sides of these two equalities and discarding identical slugs, we obtain

$$\frac{1}{x_{k+1}} + \frac{1}{f_k x_{k+1}} = \frac{1}{f_k};$$

follow, $x_{k+1} = f_k + 1$. This is exactly how the solution is obtained

⟦folio 13⟧

Lemma 2! This means that the equality $x_1 \dots x_k + 1 = C \cdot x_{k+1}$CONSTANTA $C$ is equal to 1 is not accidental: the point here is not in simplicity, but in equation (2). By the way, Lemma 2 $\delta$-rom follows from this equation.

Thus, if the solution to the problem for $n = k + 1$ is obtained by adding one number to the solution to the problem for $n = k$, then it is formed either by Lemma 1 or by Lemma 2.

4. What if we add two?

I wonder what made that noise? I can’t make that much noise alone! And where, I wonder, did my balloon go?

Piglet

So, the origin of Lemma 2 is at least clarified. True, we did not obtain new solutions and it is still unclear where the solutions come from that are not formed by applying Lemmas 1 and 2 (for example, the solution (2, 3, 7, 47, 395) for the problem with $n = 5$). Dead end again? Let's think again before we abandon our chosen path. Have we exhausted all the possibilities of our approach? Who's stopping us from adding, well, at least two numbers? Let's try.

Let us first assume that $(x_1, \dots, x_k)$ is a solution to the problem for $n = k$. Then

$$\frac{1}{x_1} + \dots + \frac{1}{x_k} + \frac{1}{f_k} = A.$$ (3)

Let $(x_1, \dots, x_k, x_{k+1}, x_{k+2})$ be the solution to the problem for $n = k + 2$ and $x_{k+1} \neq 1, x_{k+2} \neq 1$. It turns out that in this case too

$$\frac{1}{x_1} + \dots + \frac{1}{x_k} + \frac{1}{x_{k+1}} + \frac{1}{x_{k+2}} + \frac{1}{f_k x_{k+1} x_{k+2}} = A$$ (4)

with the same $A$.

Hence,

$$\frac{1}{x_{k+1}} + \frac{1}{x_{k+2}} + \frac{1}{f_k x_{k+1} x_{k+2}} = \frac{1}{f_k},$$ (5)

where

$$x_{k+2} = f_k + \frac{f_k^2 + 1}{x_{k+1} - f_k}.$$ (6)

Since $x_{k+2}$ must be an integer, $d = x_{k+1} - f_k$ is a divisor of $f_k^2 + 1$. So,

$$\begin{cases} x_{k+1} = f_k + d, \\ x_{k+2} = f_k + \frac{f_k^2 + 1}{d}. \end{cases}$$ (7)

Let us now denote by $d$ an arbitrary divisor of the number $f_k^2 + 1$ and define the numbers $x_{k+1}, x_{k+2}$ by equalities (7). Then for the numbers $f_k, x_{k+1}, x_{k+2}$ (6) is satisfied, and hence (5). From (3) and (5) follows (4). This means that the extended set $(x_1, \dots, x_k, x_{k+1}, x_{k+2})$ is a solution to our problem for $n = k + 2$. So, we have proven it.

Lemma 3. Let $(x_1, \dots, x_k)$ be the solution to the problem for $n = k, f_k = x_1 \dots x_k$ and $d$ the divisor of $f_k^2 + 1$. Then the set $(x_1, \dots, x_k, f_k + d, f_k + \frac{f_k^2 + 1}{d})$ is a solution to the problem for $n = k + 2$. And vice versa: if the solution to the problem for $n = k$ we add two numbers $n = k$ we add two numbers different from 1, then the added numbers satisfy equalities (7).

Thus, if the solution to the problem for $n = k + 2$ is obtained by adding two numbers to the solution to the problem for $n = k$, then it is formed either by Lemma 2 or by Lemma 3.

The two divisors of $y f_k^2 + 1$ are always 1 and $f_k^2 + 1$. However, it is easy to see that for such divisors Lemma 3 does not give anything new compared to Lemma 2. But then, if $f_k^2 + 1$ is not a prime number, then Lemma 3 gives rise to a new series of solutions $(x_{k+3}$ can be constructed again using Lemma 2, etc.). For example, for the solution (2, 3, 7) we have $f_k^2 + 1 = 1765 = 5 \cdot 353$, and from it we obtain by Lemma 3 the solution (2, 3, 7, 47, 395), which we mentioned in paragraph 1. Similarly, from the solution (2, 3, 7, 43) by Lemma 3 we obtain the solutions (2, 3, 7, 43, 1823, 193,667) (here $f_k^2 + 1 = 3261637 = 17 \cdot 191861$).

Consider the sequence of solutions resulting from the solution

⟦folio 14⟧

(2, 3) by Lemma 2. Let us make it basic. Each time the number $f_k^2 + 1$ turns out to be composite in it, at least one branch (Fig. 2) is split from it according to Lemma 3.

Are there many composite numbers among the numbers $f_k^2 + 1$ for the basic sequence?

Tense 2. Prove that in the basic sequence all numbers $f_{2k+1}^2 + 1$ are divisible by 5.

From Exercise 2 it follows that at least for every odd $n$ a solution will be derived from the basis sequence by Lemma 3, generating a new solution sequence by Lemma 2. It is easy to check that solutions belonging to different sequences do not coincide.

So, just one basis sequence for each $n > 2$ generates at least $\left[\frac{n-1}{2}\right]$ solutions not containing 1. And the hypothesis that there are not so “many” solutions without 1s (more precisely, that their number is limited by a constant, independent of $n$), “thumped”. It would be valid if, starting from some $n$, all solutions were actually obtained only by applying Lemma 2.

5. Another approach

And why all? For what reason?
And what conclusion follows from this?

Eeyore

Of course, the one who was chosen is far from the only one. In a letter from reader A. N. Brotsky from Knev, a different approach is proposed: instead of obtaining a solution to the problem for $n = k + 1$ or $n = k + 2$ from the solution of the problem for $n = k$, let’s try to obtain other solutions to the problem for the same $n$ from the solution of the problem for some $n$. Brotsky proposed the following theorem:

Let $(x_1, \dots, x_{n-2}, x_{n-1}, x_n)$ be the solution obtained by Lemma 2 from the solutions $(x_1, \dots, x_{n-2}, x_{n-1})$ and $\frac{f_{n-2}x_n + 1}{x_{n-1}} = d_1d_2$.

If the system of equations

$$\begin{cases} f_{n-2}x + 1 = d_1y, \\ f_{n-2}y + 1 = d_2x \end{cases}$$

we have a solution in natural numbers, then the set $(x_1, \dots, x_{n-2}, x, y)$ can be a solution to the problem.

Tense 3. Prove Brotsky's theorem.

Using his method, A. N. Brotsky from the solution (2, 3, 7, 47, 395, 779 731) obtained the solution (2, 3, 7, 47, 415, 8111), which was not formed by applying Lemma 3.

Tension 4. Check that for a solution from the basic sequence, system (8) always has a solution in natural numbers,

Tension 5. Check whether A. N. Brotsky’s method, applied to the basis sequence, gives a solution that cannot be obtained using Lemmas 2 and 3.

We have not solved the problem completely; we do not know how many solutions the problem has for a given (arbitrary) $n$. But we have only taken a few steps, and it may still take a long time. In this our task is no different from the problems that major mathematicians deal with. The process of learning the truth is endless. It does not even end with the solution of one or another problem; it is followed by new, more general ones, which require rethinking old methods and inventing new ones to solve them. You saw in this article how such a rethinking occurs and what principles a researcher should be guided by.
