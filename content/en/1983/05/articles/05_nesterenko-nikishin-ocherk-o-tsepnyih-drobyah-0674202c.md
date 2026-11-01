---
id: 1983-5-nesterenko-nikishin-ocherk-o-tsepnyih-drobyah-0674202c
issue: kvant_1983_5
year: 1983
number: "5"
title: Essay on continued fractions
authors:
  - Нестеренко Ю. В.
  - Никишин Е. М.
rubric: osnovnye-stati
page_first: 18
page_last: 21
page_labels: 16-19
tag: B4WE
lang: en
source: kvant_digital
extraction: vision
content_sha256: 97e40be3b5e67629adb8813b840c278a3d613d4326bfa11bbe4329e27d87d6e7
prompt_sha256: draft-1
translated_from: content/ru/1983/05/articles/05_nesterenko-nikishin-ocherk-o-tsepnyih-drobyah-0674202c.md
source_content_sha256: dee0d5af84009ccedab00f6f433f5b635dd5ed008082e761dce55a79555d442f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 16⟧

Essay
about continued fractions

Candidate of Physical and Mathematical Sciences
Y. V. NESTERENKO,
Doctor of Physics and Mathematics
E. M. NIKISHIN

There are many examples when a scientific direction, considered promising and important, did not fulfill the hopes raised for it; Gradually, there was an outflow of scientific forces from it, and the direction itself lost its relevance. One of these areas in mathematics is the theory of continued (or continued) fractions. Until the end of the last century, continued fractions of various kinds often appeared in mathematical works. In the last century and a little earlier, important theorems about continued fractions were proven. The hope was that if we could understand the structure of continued fractions, it would be possible to obtain new results in number theory and mathematical analysis. The hope was only partially justified, and subsequently mathematics, especially in the field of number theory, continued on new paths so that the problems of the theory of continued fractions were pushed aside.

But all the same, just as the Northern Strip accepted its conquerors, simple in formulation, easy-looking problems of continued fractions attract mathematicians, forcing them to look again and again for the patterns of this strange object. Many important questions in modern mathematics and physics lead to objects like continued fractions. Therefore, the research methods they rely on turn out to be useful in a wide range of problems. We will touch here only on those issues related to number theory, where, in fact, the theory of continued fractions arose.

Calendar, gears and a little history

How many days are there in a year? Everyone knows that a common year has 365 days, and a high year has 366 days. Years whose number is divisible by 4 are declared leap years, for example, 1904, 1908, ..., 1980, 1984, ..., 1996. However, the years 1800, 1900, 2100, 2200 are not declared high, but the years 2000, 2400, 2800 will be high. Why?

The mechanics of the calendar are quite simple. The earth rotates uniformly around its axis, making one revolution per day. One revolution of the Earth around the Sun is one year and this year is equal to 365.24219878... days. Of course, we can say that the addition of 0.242... days is small. However, over time it heats up, if you put a year equal to 365 days. In ancient times, when knowledge of a long year in a day was very approximate, the growing error reached server proportions. So in Rome in 46 BC. e. The backlog is 90 days!

To establish the pattern of normal and high years in the calendar, you need to select the length of the cycle $q$ (after which all periodic ones are repeated) and the number $p$ of high years in the cycle. Let us write the values ​​of the year in the form $365+\alpha$, where $\alpha=0,242...$. The natural numbers $p$ and $q$ must be chosen so that the values

$$\beta = q\alpha - p$$

was as small as possible, while $p$ and $q$ were not very large. As a matter of fact, only the natural number $q$ can be selected, while the number $p$ is an integer close to $q\alpha$. Then in $q$ years $365q+p$ days will pass. From equality $365q+p=q(365+\alpha)-\beta$ it follows that during this time the Earth will make

$$q - \frac{\beta}{365+\alpha} \approx q$$

⟦folio 17⟧

revolutions around the Sun. An error in one day will occur in only $\frac{1}{\beta}$ such cycles or $\frac{q}{\beta}$ years.

In the Gregorian calendar, which we live by, $q=400$ years is taken as the cycle length. Of these years, 303 are normal and 97 are high. Years that are divisible by 4 are declared leap years, with the exception of those for which the number of hundreds is also divisible by 4. Thus, the average duration of a year according to the Gregorian calendar is 365.242500 days,

An error in one day will occur in approximately 3300 years. This accuracy is quite satisfactory. Even greater accuracy could be achieved by using $q=128$ and $p=31$, but the 128-year cycle design of the calendar is inconvenient to use.

It is important for us in this case that an error has arisen here in a mathematical task: for a given number $n$ find $p$ and $q$, if possible so that the number $\frac{p}{q}$ approximates the given value $\omega$ (the desired ratio of angular velocities) as best as possible. It is clear that from the savings messages one should select $p$ and $q$ as few as possible.

It would be possible to increase the list of examples that lead us to the problem of approximating real numbers using rational numbers. For example, the structure of the musical scale, applications in computational mathematics, in theoretical issues of celestial mechanics, etc.

Continued fractions are precisely a tool that, in some senses, provides real approximations to rational numbers. These fractions for computational purposes began at

2 «Kvant» № 5

change for a long time. Already in 1572, the Italian mathematician and engineer R. Bombelli (1526? - 1572) used them to calculate $\sqrt{13}$. Later, the Englishman W. Brounker (1620-1684) used them to teach the number $n$. H. Huygens (1629-1695), an outstanding physicist, astronomer, mathematician (inventor of magnetic clocks), was the first to indicate, when using continued fractions, in what sense they provide the best approximation of a real number. The great L. Euler (1707-1783) substantiated a number of provisions of the theory of continued fractions and found a continued fraction for the number $e$. It is already very difficult to list the mathematicians who contributed to this theory after Euler's work due to their large number. Beginning with the work of the outstanding Russian mathematician P. L. Chebyshev (1821–1894), a theory dealing with functional continued fractions has been actively developing.

Euclid's algorithm and continued fraction decomposition

Let $p$, $q$ be two natural numbers. Production with remainder, we will find

$$p = a_0 q + q_1, \quad 0 < q_1 < q$$

$$q = a_1 q_1 + q_2, \quad 0 < q_2 < q_1$$

$$q_1 = a_2 q_2 + q_3, \quad 0 < q_3 < q_2$$

$$q_{k-2} = a_{k-1} q_{k-1} + q_k, \quad 0 < q_k < q_{k-1}$$

$$q_{k-1} = a_k q_k.$$

The specified set of actions is called the Euclidean algorithm. It can be shown that the resulting number $q_k$ will be the most extensive common real of the numbers $p$, $q$. We do not need this fact, so we omit the proof*).

From the obtained equalities it follows

$$\frac{p}{q} = a_0 + \frac{q_1}{q} = a_0 + \frac{1}{a_1 + \frac{q_2}{q_1}} = \dots = a_0 + \frac{1}{a_1 + \frac{1}{a_2 + \dots + \frac{1}{a_k}}}.$$

⟦folio 18⟧

This process also leads to the same result. Let α be a real number. Let's put
$$\alpha = a_0 + \frac{1}{a_1}, a_0 - \text{целое},$$
where $a_1 > 1$. If $a_1$ is not an integer, then we will continue the process further. Let's represent $a_1$ as $a_1 = a_1 + \frac{1}{a_2}$, where $a_1$ is a positive integer and $a_2 > 1$. Thus,
$$\alpha = a_0 \frac{1}{a_1 + \frac{1}{a_2}}.$$
If $a_2$ is not an integer, then you can continue the process further. Thus, at the $k$th step we obtain the equality “Multi-story” notation of the fraction (1) is very cumbersome, so in the future we will often use the following more compact special notation:
$$\alpha = a_0 + \frac{1}{a_1} + \frac{1}{a_2} + \dots + \frac{1}{a_{k-1}} + \frac{1}{a_k},$$
where $a_k > 1$.
It is not difficult to prove that if $\alpha = \frac{p}{q}$ is a rational number, then for some $k$ the number $a_k$ will be an integer.

It is also clear that if for some $k$ the integer $a_k$ is obtained, then the number $a$ is rational. If $a$ is an irrational number, then the indicated process will never end and an infinite continued (or continued) fraction will arise
$$\alpha = a_0 + \frac{1}{|a_1|} + \frac{1}{|a_2|} + \dots +$$
$$\dots + \frac{1}{|a_{k-1}|} + \frac{1}{|a_k|} + \dots$$
The equal sign here is arbitrary, since it is not clear what the expression on the right means. In order to give it meaning, consider finite sums of the form
$$\pi_k = a_0 + \frac{1}{a_1 + \dots} + \frac{1}{a_k},$$
which are called suitable continued fractions (2). By definition, it is assumed that the right side of equality (2) is represented by the limit of suitable fractions:
$$\lim_{k \to \infty} \pi_k$$
Let us now formulate in the form of a set of problems those properties of continued fractions that form the basis of their elementary theory and, in particular, establish equality (2).

Basic properties of continued fractions
1. Let $\pi_k = \frac{p_k}{q_k}$ be a suitable fraction of the continued fraction (2). Prove the validity of the recurrence relations:
$$p_0 = a_0, p_1 = a_0 a_1 + 1, \dots,$$
$$p_{k+1} = a_{k+1} p_k + p_{k-1}, \dots$$
$$q_0 = 1, q_1 = a_1, \dots,$$
$$q_{k+1} = a_{k+1} q_k + q_{k-1}, \dots$$
for $k = 1, 2, 3, \dots$.
2. Set up the following ratios:
a) $q_n p_{n-1} - p_n q_{n-1} = (-1)^n, n \geqslant 1$;
b) $q_k p_{k-2} - p_k q_{k-2} = (-1)^{k-1} a_k, k \geqslant 2$;
c) $\pi_{n-1} - \pi_n = \frac{(-1)^n}{q_n q_{n-1}}, n \geqslant 1$;
d) $\pi_{k-2} - \pi_k = \frac{(-1)^{k-1} a_k}{q_k q_{k-2}}, k \geqslant 2$.

⟦folio 19⟧

3. Show that the fractions $\pi_0, \pi_2, \pi_4, \dots$ are monotically increasing:
$$\pi_0 < \pi_2 < \pi_4 < \pi_6 < \dots,$$
and the fractions $\pi_1, \pi_3, \dots$ monotically decrease:
$$\pi_1 > \pi_3 > \pi_5 > \dots$$

4. Let the numbers $a_k$ be defined by equality (1). Prove compliance:
$$\alpha = \frac{p_{k-1}a_k + p_{k-2}}{q_{k-1}a_k + q_{k-2}}, k \geqslant 2.$$

5. Prove the inequality
$$\frac{1}{2q_{n+1}} < |q_n\alpha - p_n| \leqslant \frac{1}{q_{n+1}}.$$

6. Prove that
$$\lim_{k \to \infty} \pi_k = \alpha.$$
As can be seen from problems 1–6, the approximation of the fraction $\pi_n$ approximates the number $\alpha$ quite well. Thus, from the estimates of Problem 5 and the inequality $q_{n+1} < q_n$ it follows that if $\alpha$ is irrational, then the inequality
$$\left| \alpha - \frac{p_n}{q_n} \right| < \frac{1}{q_n^2}$$
holds for all matching fractions $\pi_n = \frac{p_k}{q_k}$ of the continued fraction of the number $\alpha$.

Numerical examples

The continued fraction (2) of the number $\alpha$ is sometimes denoted $[a_0; a_1, a_2, \dots, a_k, \dots]$. It can be proven that for every sequence of integers $a_0, a_1, a_2, \dots, (a_0 \geqslant 0$ and $a_j \geqslant 1$ for $j \geqslant 1$) there is a unique positive number $\alpha$ such that
$$\alpha = [a_0; a_1, a_2, \dots].$$
If the sequence $a_0, a_1, a_2, \dots$ is known, then the sequence of matching fractions $\pi_k = \frac{p_k}{q_k}$ can be easily calculated; use the equalities from Problem 1 to fill out the following table:

| $a$ | $a_0$ | $a_1$ | $a_2$ | ... | $a_{n-1}$ | $a_k$ | $a_{k+1}$ | $a_{k+2}$ | ... |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $p$ | 1 | $a_0$ | $p_1$ | $p_2$ | ... | $p_{k-1}$ | $p_k$ | ... | ... |
| $q$ | 0 | 1 | $q_1$ | $q_2$ | ... | $q_{k-1}$ | $q_k$ | ... | ... |

Example 1. Find the continued fraction decomposition of the number $\sqrt{2}$.
We have $a_0 = 1$,
$$a_1 = \frac{1}{\sqrt{2} - 1} = \sqrt{2} + 1, \quad a_1 = 2,$$
$$a_2 = \frac{1}{\sqrt{2} - 1} = \sqrt{2} + 1, \quad a_2 = 2.$$
It is clear that in the sequence $a_j, j = 1, 2, \dots$, all terms are equal to $\sqrt{2} + 1$, and in the sequence $a_j, j = 1, 2, \dots$, all terms are equal to 2. So,
$$\sqrt{2} = [1; 2, 2, 2, \dots].$$
Let's calculate several suitable fractions for $\sqrt{2}$:

| $a$ | 1 | 2 | 2 | 2 | 2 | 2 | 2 | ... |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $p$ | 1 | 1 | 3 | 7 | 17 | 41 | 99 | ... |
| $q$ | 0 | 1 | 2 | 5 | 12 | 29 | 70 | 169 | ... |

We got the sequence of matching fractions: $\frac{1}{1}, \frac{3}{2}, \frac{7}{5}, \frac{17}{12}, \frac{41}{29}, \frac{99}{70}, \dots$

From Problem 5 it follows that
$$\left| \sqrt{2} - \frac{99}{70} \right| < \frac{1}{70 \cdot 169} < 10^{-4}.$$
Thus, the field fraction
