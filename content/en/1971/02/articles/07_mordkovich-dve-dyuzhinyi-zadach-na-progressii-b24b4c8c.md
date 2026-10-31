---
id: 1971-2-mordkovich-dve-dyuzhinyi-zadach-na-progressii-b24b4c8c
issue: kvant_1971_2
year: 1971
number: "2"
title: Two dozen progression problems
authors:
  - Мордкович А. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 39
page_last: 43
page_labels: 37-41
tag: ZWRR
lang: en
source: kvant_digital
extraction: vision
content_sha256: 467fdd709ed09edb7ab37f017d43592c8e3ebfe985d0c8845fd5132402395496
prompt_sha256: draft-1
translated_from: content/ru/1971/02/articles/07_mordkovich-dve-dyuzhinyi-zadach-na-progressii-b24b4c8c.md
source_content_sha256: 149a3527e7b227745e668458f874933447a33a3945ff287d248e65fd922435f5
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 37⟧

TWO DOZENS
PROGRESSION TASKS

To successfully solve programming problems, you need to know the definitions of an arithmetic, geometric and infinitely decreasing geometric program, the formula of the promised term for each of these programs, the formula for the sum of $n$ terms of the program, as well as the definition and formula for the sum of the terms of an infinitely decreasing geometric program. In addition, very often in programming problems it is necessary to use the so-called characteristic properties of the program. The experience of entrance exams shows that if the situation with the formulas of the $n$-terms and the sum of the $n$-terms of the program is relatively good, then the same cannot be said about the characteristic properties. Therefore, first of all we will focus on these properties.

Characteristic properties of an arithmetic program

The sequence $a_1, a_2, \dots, a_n$, ... is an arithmetic program moeda and molko moeda when each of its members, except the first (and the last, in the case of a finite sequence), is equal to the arithmetic mean of its neighbors.

Proof. Given a sequence $a_1, a_2, \dots, a_n$, ... Let it be an arithmetic program. Let us prove that $a_{k+1} = \frac{a_k + a_{k+2}}{2}$ ($k = 1, 2, 3, \dots$).

Indeed, $a_{k+1} - a_k = a_{k+2} - a_{k+1}$, whence $a_{k+1} = \frac{a_k + a_{k+2}}{2}$.

Let now $a_{k+1} = \frac{a_k + a_{k+2}}{2}$. Then $a_{k+1} - a_k = a_{k+2} - a_{k+1}$, that is, the difference between the subsequent and previous members of the sequence is constant for a given sequence, and this means that $a_1, a_2, \dots, a_n$, ... is an arithmetic program.

Characteristic properties of a geometric program

The sequence $b_1, b_2, \dots, b_n$, ... is a geometric programma moeda and molko moeda, when each of its terms, except the first (and the last, in the case of a finite sequence), is equal to the product of its 相邻 (that is, $b_2^{k+1} = b_k \cdot b_{k+2}$).

Proof. Let the sequence $b_1, b_2, \dots, b_n$, ... be a geometric programma. Then $\frac{b_{k+1}}{b_k} = \frac{b_{k+2}}{b_{k+1}}$, whence $b_2^{k+1} = b_k \cdot b_{k+2}$, which is what needed to be proved.

Let, on the contrary, $b_2^{k+1} = b_k \cdot b_{k+2}$. Then $\frac{b_{k+1}}{b_k} = \frac{b_{k+2}}{b_{k+1}}$, that is, the ratio of the terms of the sequence to the previous constant for a given sequence, and this means that $b_1, b_2, \dots, b_n$, ... is a geometric program.

⟦folio 38⟧

In this article, the reader will find 24 problems, the solution of which uses all the properties of progressions. Half of the problems are given with solutions, the rest are left to the reader for independent work. Throughout the article the following notations are adopted (unless any reservations are made): $a_1, a_2, \dots, a_n, \dots$ - arithmetic progression, $d$ - difference progression; $b_1, b_2, \dots, b_n, \dots$ — geometric progression, $q$ — denominator of the progression; $S_n$ is the sum of $n$ terms of the progression; $n, k, m, p$ are natural numbers.

Arithmetic progression

Task 1. Prove that $\frac{1}{a_1 a_2} + \frac{1}{a_2 a_3} + \dots + \frac{1}{a_n a_{n+1}} = \frac{n}{a_1 a_{n+1}}$.

Solution. $\frac{1}{a_1 a_2} = \frac{d}{a_1 a_2 d} = \frac{1}{d} \frac{a_2 - a_1}{a_1 a_2} = \frac{1}{d} \left( \frac{1}{a_1} - \frac{1}{a_2} \right)$. Likewise

$$\frac{1}{a_2 a_3} = \frac{1}{d} \left( \frac{1}{a_2} - \frac{1}{a_3} \right), \dots, \frac{1}{a_n a_{n+1}} = \frac{1}{d} \left( \frac{1}{a_n} - \frac{1}{a_{n+1}} \right).$$

Pozny

$$\frac{1}{a_1 a_2} + \frac{1}{a_2 a_3} + \dots + \frac{1}{a_n a_{n+1}} = \frac{1}{d} \left( \frac{1}{a_1} - \frac{1}{a_2} \right) +$$

$$+ \frac{1}{d} \left( \frac{1}{a_2} - \frac{1}{a_3} \right) + \dots + \frac{1}{d} \left( \frac{1}{a_n} - \frac{1}{a_{n+1}} \right) = \frac{1}{d} \left( \frac{1}{a_1} - \frac{1}{a_{n+1}} \right) =$$

$$= \frac{1}{d} \frac{a_{n+1} - a_1}{a_1 a_{n+1}} = \frac{1}{d} \frac{a_1 + dn - a_1}{a_1 a_{n+1}} = \frac{n}{a_1 a_{n+1}}.$$

Task 2. The sequence $u_1, u_2, \dots, u_n, \dots$ has the property that the sum $S_n$ of its first $n$ terms is equal to $2n^2 + 3n$. Prove that this sequence is an arithmetic progression.

Solution. Using the characteristic property of an arithmetic progression, we conclude that it is enough for us to prove the following relations: $2u_{k+1} = u_k + u_{k+2}$, where $k=1, 2, 3, \dots$.

We notice that $u_{k+1} = S_{k+1} - S_k$. Indeed, $S_{k+1} - S_k = (u_1 + u_2 + \dots + u_k + u_{k+1}) - (u_1 + u_2 + \dots + u_k) = u_{k+1}$. Means,

$$u_{k+1} = [2(k+1)^2 + 3(k+1)] - (2k^2 + 3k) = 4k + 5.$$

Similarly, $u_k = S_k - S_{k-1}$ (in particular, we assume $S_0 = 0$), hence $u_k = (2k^2 + 3k) - [2(k-1)^2 + 3(k-1)] = 4k + 1$ and, finally, $u_{k+2} = S_{k+2} - S_{k+1} = 4k + 9$. Since for the numbers $u_k = 4k + 1$, $u_{k+1} = 4k + 5$, $u_{k+2} = 4k + 9$, respectively, $2u_{k+1} = u_k + u_{k+2}$ is satisfied, the proof that $u_1, u_2, \dots, u_n, \dots$ is an arithmetic progression is legitimate.

Task 3. Prove that the relation $\frac{S_n}{n} (m - p) + \frac{S_m}{m} (p - n) + \frac{S_p}{p} (n - m) = 0$ is true for an arithmetic progression.

Solution. Using the well-known formula $S_n = \frac{a_1 + a_n}{2} n$ for $S_n$ and similar formulas for $S_m$ and $S_p$, we reduce the left-hand side of the equality being proved to the form

$$\frac{a_1 + a_n}{2} (m - p) + \frac{a_1 + a_m}{2} (p - n) + \frac{a_1 + a_p}{2} (n - m).$$

⟦folio 39⟧

Applying the formula for the general term of the arithmetic progression $a_n = a_1 + d(n-1)$ to $a_n$ and doing the same for $a_m, a_p$, we get

$$\frac{1}{2} \left\{ [2a_1 + d(n-1)] (m-p) + [2a_1 + d(m-1)] (p-n) + [2a_1 + d(p-1)] (n-m) \right\}$$

and onwards

$$\frac{1}{2} \left\{ 2a_1 [(m-p) + (p-n) + (n-m)] + d [(n-1)(m-p) + (m-1)(p-n) + (p-1)(n-m)] \right\}.$$

Since the sums in both square brackets are equal to 0, then the entire expression is equal to 0, which is what we needed to prove.

Task 4. Find a three-digit number that is divisible by 45 and whose digits form an arithmetic progression.

Solution e. Let $x$ be the hundreds digit, $y$ the tens digit and $z$ the units digit of the desired number. Since by condition $x, y, z$ is an arithmetic progression, then

$$2y = x + z. \tag{1}$$

The required number has the form $100x + 10y + z$. Since by condition it is divisible by 45, then

$$100x + 10y + z = 45p. \tag{2}$$

So, the required number is determined by conditions (1) and (2).

For the units digit there are two possibilities: either $z=0$ or $z=5$ (this follows from the divisibility of the desired number by 5). Consider the case $z=0$. Then from (1) we get $x=2y$, and from (2) we get $100x + 10y = 45p$, or $20x + 2y = 9p$, $20x + x = 9p$ or $7x = 3p$. This means that $x$ is divisible by 3. Since, in addition, $x$ is an even number ($x=2y$), we conclude that for $x$ there is only one possibility: $x=6$. Then $y=3$, and the required number is 630.

Let us now consider the second case: $z=5$. In this case, conditions (1) and (2) take the corresponding form:

$$2y = x + 5; 100x + 10y + 5 = 45p.$$

The last equality is transformed to the form $20x + 2y + 1 = 9p$ and then, taking into account the equality $2y=x+5$, we obtain $21x+6=9p$, or $7x+2=3p$. The last equality is possible for $x=1, 4, 7$. But since $x+5$ is an even number ($x+5=2y$), there are only two possibilities left for $x$: $x=1, x=7$. In the first case $y=3$, in the second case $y=6$. The required number of the corresponding one in the first case is 135, in the second 765. So, the conditions of the problem are satisfied by three numbers: 135, 630, 765.

**Geometric progression**

Task 5. Calculate the sum $2 + 22 + 222 + \ldots + 222\ldots 2$

Solution e. $2 + 22 + 222 + \ldots + 222\ldots 2 = 2[1 + (1+10) + (1+10+10^2) + \ldots + (1+10+10^2 + \ldots + 10^{n-1})] = 2[S_1 + S_2 + S_3 + \ldots + S_n]$, where $S_k$ is the sum of $k$ terms of the geometric progression 1, 10, $10^2$, $10^3$, ... ($k=1, 2, \ldots, n$). Applying the formula $S_k = \frac{b_1(q^k - 1)}{q-1}$ for the sum of terms of a geometric progression, we obtain

⟦folio 40⟧

$$2(S_1 + S_2 + S_3 + \ldots + S_n) = 2\left(\frac{10 - 1}{9} + \frac{10^2 - 1}{9} + \ldots + \frac{10^n - 1}{9}\right) = \frac{2}{9}[10(1 + 10 + 10^2 + \ldots + 10^{n-1}) - n] = \frac{2}{9}\left[\frac{10(10^n - 1)}{9} - n\right] = \frac{2(10^{n+1} - 10 - 9n)}{81}.$$

Task 6. Prove that the sequence $u_1, u_2, u_3$, where
$$u_1 = 9, \quad u_2 = 3^{\frac{1}{2}} \text{tg} x, \quad u_3 = \left(\frac{1}{9}\right)^{\cos 2x},$$
is a geometric progression if and only if
$$x = \pi l, \quad x = \frac{\pi}{12} + \pi l, \quad x = \frac{5\pi}{12} + \pi l \quad (l = 0, \pm 1, \pm 2, \ldots).$$

Solution. Based on the characteristic property of the geometric progression, we conclude that the problem of the property for solving the equation
$$9^{\frac{1}{2}} \text{tg} x = 9\left(\frac{1}{9}\right)^{\cos 2x}$$

Let us perform successive transformations of this equation:
$$\frac{1}{2} \text{tg} x = 1 - \cos 2x,$$
$$\text{tg} x = 4 \sin^2 x, \quad \sin x (2 \sin 2x - 1) = 0 \quad (\cos x \neq 0).$$
Thus, one of two equations must be satisfied:
$$\sin x = 0, \quad \sin 2x = \frac{1}{2},$$

where
$$x = \pi l, \quad x = \frac{\pi}{12} + \pi l, \quad x = \frac{5\pi}{12} + \pi l.$$

The resulting series and only they satisfy equation (3). Consequently, for the obtained values ​​$x$ and only for them $u_1, u_2, u_3$ is a geometric progression.

Task 7. Can the numbers 10, 11, 12 be members of the same geometric progression?

Solution and e. Suppose that the given numbers are terms of a geometric progression with the first term $b_1$ and the denominator $q$. Then $10 = b_1 q^n, 11 = b_1 q^m, 12 = b_1 q^p$. From these relations we obtain
$$\frac{11}{10} = q^{m-n}, \quad \frac{12}{10} = q^{p-n}$$

and onwards
$$\left(\frac{11}{10}\right)^{p-n} = \left(\frac{12}{10}\right)^{m-n},$$
$$\frac{11^{p-n}}{12^{m-n}} = 10^{p-m}.$$

The last equality cannot hold for any pairwise distinct natural numbers $n, m, p$. This means that the numbers 10, 11, 12 cannot be members of the same geometric progression.

⟦folio 41⟧

Task 8. The sum of the terms of the infinite killing geometric progression is 9, and the sum of the squares of its terms is 40.5. Find the first term and signifier of the progression.

Solution. Using the formula $S = \frac{b_1}{1-q}$ for the sum of terms of an infinite killing geometric progression, we obtain $\frac{b_1}{1-q} = 9$.

Consider the sequence $b_1^2, b_2^2, \ldots, b_n^2, \ldots$. Note that this is an infinitely killing geometric progression with the first term $b_1^2$ and the value $q^2$. Then the sum of the terms of this progression is determined by the formula $\frac{b_1^2}{1-q^2}$ and is equal to 40.5.

As a result, the problem comes down to solving the system

$$\frac{b_1}{1-q} = 9, \quad \frac{b_1^2}{1-q^2} = 40,5.$$

From this system we obtain: $b_1 = 6, \quad q = \frac{1}{3}$.

Mixed progression problems

Task 9. Find even numbers if it is known that the first three of them form a geometric progression, the last three form an arithmetic progression, the sum of the extreme numbers is 21, the sum of the middle ones is 18.

Solution. Let $a, b, c, d$ be the original numbers; $a, b, c$ is a geometric progression, which means $b^2=ac$; $b, c, d$ is an arithmetic progression, so $2c=b+d$. As a result, we arrive at the following system of equations:

$$\begin{cases}
b^2=ac, \\
2c=b+d, \\
a+d=21, \\
b+c=18.
\end{cases}$$

Solving this system, we obtain $a=3, b=6, c=12, d=18$ or

$$a = \frac{75}{4}, \quad b = \frac{45}{4}, \quad c = \frac{27}{4}, \quad d = \frac{9}{4}.$$

Task 10. When the numbers form a geometric progression. If the second number is increased by 2, then the resulting numbers form an arithmetic progression. If you then increase the third number by 9, you will again get a geometric progression. Find these numbers.

Solution. We rewrite the conditions of the problem as follows:

$$b_1, b_2, b_3 \text{ — геометрическая прогрессия;}$$
$$b_1, b_2+2, b_3 \text{ — арифметическая прогрессия;}$$
$$b_1, b_2+2, b_3+9 \text{ — геометрическая прогрессия.}$$

Using the characteristic properties of progressions, we obtain

$$\begin{cases}
2(b_2+2) = b_1+b_3, \\
(b_2+2)^2 = b_1(b_3+9).
\end{cases}$$
