---
id: 1978-5-boltyanskiy-chasto-li-stepeni-dvoyki-nachinayutsya-s-edinitsyi-119f0ff1
issue: kvant_1978_5
year: 1978
number: "5"
title: Do powers of two often begin with one?
authors:
  - Болтянский В. Г.
rubric: osnovnye-stati
page_first: 4
page_last: 8
page_labels: 2, 4, 6
tag: GLE7
lang: en
source: kvant_digital
extraction: vision
content_sha256: eb8343e2bd5a69f4fd2232507dc40bb53a5939332b1ee56c75d5035be45043e5
prompt_sha256: draft-1
translated_from: content/ru/1978/05/articles/02_boltyanskiy-chasto-li-stepeni-dvoyki-nachinayutsya-s-edinitsyi-119f0ff1.md
source_content_sha256: 6a0557be44f15c8e056cf405895e1e8f515ea49c1c41fd5d509391b3ac00cdee
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

V. Boltyansky

Do powers of two often begin with one?

Statement of the problem
Middle powers of two numbers starting with one appear again and again. How often do they occur? In other words, what is the probability that a number chosen at random from the numbers $2^1, 2^2, \ldots, 2^n$ begins with the digit 1, is $a_n/n$. This probability depends on $n$, i.e., on how many first powers of two were taken. Limit

$$p_1 = \lim_{n \to \infty} \frac{a_n}{n},$$

(if it exists) and is called the probability that any given natural number is divisible by 3?

1. What is the probability that an arbitrary digit of the decimal expansion of the number $\frac{161}{222}$ is a five? Double?

2. What is the probability that any given natural number is a perfect square?

⟦folio none⟧

Over limit (1)

Among the two-digit numbers that are powers of two, exactly one (namely, 16) begins with one. Among the three-digit powers of two, exactly one number (namely, 128) begins with one. The same is true for four-digit powers of two.

In general, for $k > 1$, among the $k$-digit numbers that are powers of two, there is exactly one that begins with the digit 1. Indeed, the smallest $k$-digit number that is a power of two necessarily begins with one (otherwise, dividing by 2, we would get that the previous power of two is a $k$-digit number). There is no other number beginning with the number 1 among the $k$-digit powers of two: the next power of two will have the number 2 or 3 in the first place, the next one will have an even higher number, until we get a $(k+1)$-digit number.

From the above it follows that if the number $2^n$ is $m$-digit, then among the numbers $2^1, 2^2, \dots, 2^n$ there are exactly $m-1$ numbers starting with one, i.e. $a_n = m-1$. But the statement "the number $2^n$ is $m$-digit" means that

$$10^{m-1} \leq 2^n < 10^m,$$

that is

$$m-1 \leq n \lg 2 < m.$$

Remembering that $a_n = m-1$, we get

Fig. 1.

$$\lg 2 - \frac{1}{n} < \frac{a_n}{n} \leq \lg 2,$$

and therefore

$$p_1 = \lim_{n \to \infty} \frac{a_n}{n} = \lg 2 = 0,30103...$$

So, a little more than 30% of powers of two begin with one.

3 adachs and

4. Let us denote by $p_q$ the probability that an arbitrary power of two begins with the number $q^*$. Prove the equalities

$$p_2 + p_3 = p_1, \quad p_4 + p_5 = p_2, \quad p_6 + p_7 = p_3, \quad p_8 + p_9 = p_4.$$

5. Prove that $p_4 = 1-3 \lg 2 = 0,096...$

As you can see, powers of two begin with the number 4 more than three times less often than with the number 1 (Fig. 2).

Fig. 2.

General task

What is the probability that an arbitrary power of a given natural number $l$ begins (in decimal notation) with the digit $q$?

Let the number $l^n$ begin in decimal notation with the digit $q$, i.e.

$$q \cdot 10^m \leq l^n < (q+1) \cdot 10^m,$$

where $m$ is some natural number. Dividing these inequalities by $q \cdot 10^m$ and continuing to rhyme in base 10, we get:

$$0 \leq (n \lg l - \lg q) - m < \lg \frac{q+1}{q}.$$ (2)

Since the number on the right is less than one ($\frac{q+1}{q} = 1 + \frac{1}{q} \leq 2 < 10$), inequality (2) means that the fractional part of the number $n \lg l - \lg q$ is less than $\lg \frac{q+1}{q}$ (remember that the fractional part)

*) The existence of the numbers $p_q$ follows from what follows.

⟦folio 4⟧

the number $x$ is the difference between the number $x$ and its integer part: $\{x\} = x - [x]$, and the integer part $x$ is the largest integer that does not exceed $x$). Conversely, if the fractional part of the number $n \lg l - \lg q$ is less than $\lg \frac{q+1}{q}$, that is, if for some natural number $m$ inequalities (2) are satisfied, then $l^n$ begins in decimal notation with the number $q$. Thus, the posed problem is equivalent to the following: what is the probability that for an arbitrary natural number $n$

$$\{n \lg l - \lg q\} < \lg \frac{q+1}{q}$$

Will help us solve this last problem

Fractional parts theorem $x$. Let $\alpha, \beta$ be real numbers, moreover, the number $\alpha$ is irrational, and $I$ is some interval of length $h$ contained in the interval [0, 1]. Distance to infinite sequence $\alpha + \beta, 2\alpha + \beta, \dots, n\alpha + \beta, \dots$. The probability that any given number in this sequence has a fractional part belonging to the interval $I$ is equal to $h$.

We will give the proof of this theorem at the end of the article, but now we will show how it applies to solving our problem.

First of all, note that if $l$ is a power of ten, then all powers of $l$ begin with the digit $1$, i.e. in this case the problem is trivial.

If $l$ is not a power of ten, then the number $\alpha = \lg l$ is the difference. By the fractional parts theorem, the probability that an arbitrary number from the sequence $n \lg l - \lg q$ ($n = 1, 2, \dots$) has a fractional part belonging to the interval $$\left[0, \lg \frac{q+1}{q}\right],$$ is equal to $$\lg \frac{q+1}{q}.$$ This gives a solution to the problem considered above: the probability that an arbitrary global number $l$ (which is not a power of ten) begins with the digit $q$, equal to $$\lg \frac{q+1}{q}.$$

Note that this probability is independent of $l!$. For example, powers of two and powers of three equally often (namely, with probability lg 2) begin with the number 1.

3 adachs and

6. Prove that if the natural number $l$ is not a power of ten, then the number $\lg l$ is playable.

7. Calculate the probabilities $p_2, \dots, p_9$ given in Problem 4. Give a new proof of the equalities contained there.

8. What is the probability that an arbitrary power of two begins with the digit 1000 (Fig. 3)?

Fig. 3.

9. What is the probability that an arbitrary power of $l$ (which is not a power of ten) begins with the digit combination $q_1 q_2 \dots q_r$ (where $q_1 \neq 0$)? Deduce from this that powers of the number $l$ can begin with either a combination of digits $q_1 q_2 \dots q_r$ ($q_1 \neq 0$).

10. Prove the following statements:

a) The probability that an arbitrary power of the number $l$, which is not a power of ten, has a second digit of 0 is equal to

$$p_0^{(2)} = \lg(11 \cdot 21 \cdot 31 \cdot \dots \cdot 91) - \lg(9!) - 9.$$

Hint: $p_0^{(2)}$ is the sum of the probabilities that an arbitrary power of $l$ starts with the combinations 10, 20, ..., 90.

6) The probability that for an arbitrary power of $l$ that is not a power of ten, the $k$th (from the left) digit is $q$ (where $k > 1$, $q = 0, 1, \dots, 9$) is:

$$p_k^{(2)} = \sum_{i=10}^{k-1} \lg \left(1 + \frac{1}{q+10i}\right).$$

11*. Using the result of Problem 10, 6), prove that $\lim_{k \to \infty} p_k^{(2)} = 1/10$. Thus, for a sufficiently large $k$, each of the probabilities $p_k^{(2)}, p_1^{(2)}, \dots, p_9^{(2)}$ as angle-small differs from 1/10.

⟦folio 6⟧

term of the second progression, that the model of their difference is less than 0.000001?

16. We call the forest of joy the union of all circles of radius $\varepsilon$, the centers of which are points with integer coordinates. Prove that if a straight line forms an angle $\varphi$ with the x-axis, the tangent of which is irrational, then it necessarily intersects the forest (no matter how small $\varepsilon$; Fig. 5).

Proof of the theorem

Let us now move on to the proof of the theorem on fractional parts.

Let's take an arbitrary natural number $r$. Points $\frac{1}{r}, \frac{2}{r}, \dots, \frac{r-1}{r}$ split segment $[0, 1]$ into $r$ segments of length $\frac{1}{r}$. Let's call these segments "cells", and call the fractional parts of the numbers $\alpha, 2\alpha, \dots, (r+1)\alpha$ "hares"*). Since there are $r$ “cells” and $r+1$ “hares”, then there are two “hares” that fall into one cell, i.e. there are natural $p'$ and $p''$ ($p' > p''$) such that the fractional parts of the numbers $p' \alpha$ and $p'' \alpha$ differ by less than $\frac{1}{r}$. This means $|(p' \alpha - p'' \alpha) - m| < \frac{1}{r}$ for some integer $m$. By putting $p = p' - p''$, we can write: $|p \alpha - m| = \varepsilon$, where $\varepsilon < \frac{1}{r}$. Note that $\varepsilon \neq 0$, since $\alpha$ is irrational. Let us denote by $s$ the smallest natural number greater than $\frac{1}{\varepsilon}$, i.e. $s - 1 \leqslant \frac{1}{\varepsilon} < s$.

Consider $s$ successive terms of an arithmetic progression with difference $p \alpha$:

$$\gamma + p \alpha, \gamma + 2p \alpha, \dots, \gamma + sp \alpha,$$

(3) where $\gamma$ is some real number. Let us denote the fractional parts of numbers (3) by $x_1, x_2, \dots, x_s$. By virtue of the equality $|p \alpha - m| = \varepsilon$, the numbers $x_1, x_2, \dots, x_s$ are spaced $\varepsilon$ (Fig. 6) from each other. Due to inequalities $\frac{1}{s} < \varepsilon \leqslant \frac{1}{s-1}$, the distance between points $x_1$

*) This terminology is related to the Dirichlet principle («Kvant», 1977, No. 2, p. 17). The fractional parts theorem can be called “the Dirichlet principle for an infinite number of hares.”

Fig. 6.

and $x_s$ is figure 6, 6 less than $\varepsilon$. From the above it follows that the number of points $x_1, x_2, \dots, x_s$ falling on the segment $l$ of length $h$ is contained between the number $\frac{h}{\varepsilon} - 1$ and $\frac{h}{\varepsilon} + 2$, i.e. between $sh-2$ and $sh+2$ (note that $h < 1$).

Let us now take $ps$ successive terms $b_1, b_2, \dots, b_{ps}$ of some arithmetic progression with difference $\alpha$ (i.e. $b_{i+1} = b_i + \alpha$). Let us arrange them in the form of a table; it represents a progression of the form (3). Since the number of lines is $p$, then the number of those terms of the progression $b_1, b_2, \dots, b_{ps}$ under consideration, the fractional parts of which fall in the interval $l$, is contained between the number $p (sh-2)$ and $p (sh+2)$.

Finally, let $n$ be an arbitrary natural number greater than $rps$. Dividing $n$ by $ps$ with the remainder, we get $n = lps + q$, where $l \geqslant r$, $0 \leqslant q < ps$. Consequently, from the number $\alpha + \beta, 2\alpha + \beta, \dots, n\alpha + \beta$ we can take $l$ times $ps$ successive terms of the arithmetic progression with a difference of $\alpha$,
