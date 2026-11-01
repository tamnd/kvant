---
id: 1981-1-kurlyandchik-priblizhenie-k-ekstremumu-143f4a7f
issue: kvant_1981_1
year: 1981
number: "1"
title: Approaching an extremum
authors:
  - Курляндчик Л. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 23
page_last: 27
page_labels: 21, 22, 24, 25
tag: LMZA
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0ddb7a1085a60ae05498b0b15955101d16c024f4e6e69ace50dfa6a48c89ccaa
prompt_sha256: draft-1
translated_from: content/ru/1981/01/articles/07_kurlyandchik-priblizhenie-k-ekstremumu-143f4a7f.md
source_content_sha256: d454b2177b9cc0f3141cf06c88e10cde3ffaa9845d4f5f7deae8cf38992dc5dd
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 21⟧

L. Kurlyandik

Approaching an extremum

The concept of arbitrary, which you learn in school, provides a simple way to find the largest and smallest values ​​of a function $y=f(x)$ of a single variable $x$. However, in problems sometimes it is necessary to find the largest or smallest value of expressions, depending on several variables. The methods associated with the use of arbitrary are much more complicated here and are not studied in school, so elementary methods for solving such problems acquire greater value. One of these methods, proposed in 1884 by the German mathematician R. Sturm, is almost discussed in the article.

Let's start with two problems.

Problem 1. Which of the n-words inscribed in a given circle has the largest area?

Problem 2. The sum of n numbers is equal to 1. At what values ​​of these numbers does the sum of their squares take on the smallest possible value?

figure 1 and 2 show ABC flip-flops, with $|AB| > |BC|$. Let's see what happens to the area of ​​this triangle if, without changing the position of points A and C, we move point B along the arc AC so that the lengths of the sides AB and BC are close, that is, their difference decreases. Let the point $B'$ on the arc AC be such that $|AB'| = |CB|$. To match the lengths of sides AB and BC, you need to replace point B with any point of the other BB'. At the same time, the length of the height BH of triangle ABC will increase and, consequently, its area will increase.

This observation shows that an irregular n-pleaser is not a solution to Problem 1. Indeed, if $|AB|$ and $|BC|$ are unequal adjacent sides of this n-pleaser (Fig. 2), then by replacing vertex B with some point of other BB', we increase the area of ​​triangle ABC and obtain an inscribed n-pleaser of larger area.

Moving on to Problem 2, let's find out what happens to the sum of the squares of two numbers if we merge these numbers without changing their sum. Let $a, b$ be the given numbers, $a < b$, and let $0 < \varepsilon < b - a$. Then

$$(a + \varepsilon)^2 + (b - \varepsilon)^2 = a^2 + b^2 - 2\varepsilon(b - a - \varepsilon) < a^2 + b^2.$$

We see that the sum of squares has decreased. This observation shows that a set of n numbers (with sum 1), among which there are two unequal numbers, is not a solution to Problem 2. Indeed, by licking off unequal numbers, we, without changing the sum of all numbers, will reduce the sum of their squares.

⟦folio 22⟧

It may seem that problems 1 and 2 have solutions: the solution to problem 1 is a regular $n$-gon inscribed in a given circle, and the solution to problem 2 is the set of numbers $(1/n, 1/n, \dots, 1/n)$. In fact, so far it has only been proven that no $n$-gon other than a regular one is a solution to Problem 1, or one set of $n$-numbers other than $(1/n, 1/n, \dots, 1/n)$ is a solution to Problem 2. But another logical possibility remains unexplored: no $n$-gon is a solution to Problem 1, no set of $n$-numbers is a solution to Problem 2. Proving the existence of a mathematical object with a given property is often quite difficult. But the solution to any problem is simplified if the possibility of the answer is known, and this is exactly the case in problems 1 and 2.

Solution to problem 1.

Let us prove that the area of ​​any $n$-gon inscribed in a given circle is not greater than the area of ​​a regular $n$-gon inscribed in this circle. (This just means that a regular $n$-gon is a solution to Problem 1; in the previous argument we only established that an irregular $n$-gon is not a solution.)

Note that if we replace the vertex $B$ of an inscribed $n$-gon with the point $B'$ (Fig. 2), we obtain an inscribed $n$-gon of the same area, different from the original polygon in the order of the two adjacent sides. Having performed this operation as many times as necessary, we can swap places of any two sides of an inscribed $n$-gon without changing its area.

Let $P$ be a non-regular $n$-gon inscribed in a given circle. The smallest side of this $n$-gon subtends an arc whose corner vertex is smaller than $360^\circ/n$, and the longest side subtends an arc larger than $360^\circ/n$. Let us rearrange the sides of the $n$-gon so that the most and most sides are adjacent. On figure 3 these are sides $AB$ and $BC$. Let us plot on the arc $AC$ the arc $AB_1$, the corner vertex of which is equal to $360^\circ/n$. Replacing the vertex $B$ with the point $B_1$, we obtain an inscribed $n$-gon $P_1$, the area of ​​which is greater than the $n$-gon $P$.

Moreover, the polygon $P_1$ has at least one side subtending an arc of magnitude $360^\circ/n$, that is, equal to the side of a regular inscribed $n$-gon. If the polygon $P_1$ is not regular, then, having performed the described operation with it, we will arrive at an inscribed $n$-gon $P_2$ of a larger area, in which at least one more side is equal to the side of a regular inscribed $n$-gon. After a finite number of steps we arrive at an inscribed $n$-gon, and its area is thus greater than the area of ​​the $P$ polygon.

Solving problem 2.

Let the sum of the numbers $a_1, a_2, \dots, a_n$ be equal to 1. If not all these numbers are equal to each other, then the smallest of them is less than 1/n, and the largest is greater than 1/n. Let $a_1 < 1/n, a_2 > 1/n$. By replacing the number $a_1$ with 1/n, and the number $a_2$ with $a_1 + a_2 - 1/n$, we “bring closer” $a_1$ and $a_2$ without changing their sum and, therefore, reducing the sum of squares. Thus, we will get a new set of numbers with a sum of 1, and the sum of the squares of the numbers in this set is less than the sum of the squares of the numbers in the original set. Moreover, the new set contains at least one number equal to 1/n. If not all numbers in this set are equal to 1/n, then, having performed the described operation with it, we will arrive at a set with a sum of 1, but even less than a sum of squares, in which there is still at least one number equal to 1/n. After a finite number of steps we arrive at a set $(1/n, 1/n, \dots, 1/n)$ with a sum of squares less than in the original set. Thus, the set of numbers $(1/n, 1/n, \dots, 1/n)$ is a solution to Problem 2.

If for an arbitrary number $S$ among the sets $n$ of numbers $a_1, a_2, \dots, a_n$ with the sum $S$ we look for one in which the sum of the squares of the terms of the minimum, then the above reasoning would lead us to the set $(\frac{S}{n}, \frac{S}{n}, \dots, \frac{S}{n})$. Thus, for arbitrary numbers $a_1, a_2, \dots, a_n$ the following applies:

⟦folio 24⟧

Indeed, if not all given numbers are equal to each other, then the smallest of them is less than $A$, and the most is greater than $A$. Let's say $a_1 < A, a_2 > A$. By replacing $a_1$ with $A$, and $a_2$ with $a_1 + a_2 - A$, we will jinx them while preserving the sum of these numbers. In this case, the arithmetic mean $A$ will not change, but the geometric mean $\Gamma$ will increase (see workpiece I). If there are unequal numbers in the new set of numbers, then we will perform the same operation. Since each step increases the number of numbers equal to $A$, after a finite number of steps all numbers will become equal, and we will arrive at a set for which the arithmetic mean is equal to the geometric mean. Since at each step it is simply the geometric mean and the arithmetic mean has not changed, in the original set of numbers the arithmetic mean is greater than the geometric mean.

Exercise 1. Using workpiece I, find out which 25 natural terms $n_1, n_2, \dots, n_{25}$ should be divided into the number 1981 so that the product $n_1! n_2! \dots n_{25}$ is the smallest.

Exercise 2. Using workpiece II, prove the equality for the positive numbers $a_1, a_2, \dots, a_n$ and the natural number $k$

$$\frac{a_1^k + a_2^k + \dots + a_n^k}{n} \geq \left( \frac{a_1 + a_2 + \dots + a_n}{n} \right)^k.$$

Using Proposition III, we will now prove the equality that bears the name of the famous 18th-century scientist Christine Huygen: if $x_1, x_2, \dots, x_n$ are positive numbers, then

$$\left( 1 + x_1 \right) \left( 1 + x_2 \right) \dots \left( 1 + x_n \right) \geq \geq \left( 1 + \sqrt[n]{x_1 x_2 \dots x_n} \right)^n.$$

When positive numbers $a$ and $b$ merge with a fixed product, the sum $a + b$ decreases, which means the product $(1 + a)(1 + b)$, equal to $1 + ab + a + b$, also decreases.

Let's put $\Gamma = \sqrt[n]{x_1 x_2 \dots x_n}$. If the averages of numbers $x_1, x_2, \dots, x_n$ are unequal, then the least of them is less than $\Gamma$, and the most is greater than $\Gamma$. Replace $x_1$ with $\Gamma$, and $x_2$ with $\frac{x_1 x_2}{\Gamma}$. At the same time, $x_1$ and $x_2$ will preserve the product, and therefore

*) This problem was presented at the XII Weighty Mathematical Olympiad. In «Kvant», 1979, No. 7, its solution, different from that discussed in the article, is outlined.

⟦folio 25⟧

to be located inside the segment $[a; b]$. Eventually we will arrive at a situation where every one of the numbers $x_1, x_2, \dots, x_n$, except perhaps one, will be equal to $a$ or $b$.

The left side of the inequality can now be considered as a function of one variable defined on the interval $[a; b]$. Show that this function takes the largest value at one end of the segment $[a; b]$, and check that this value does not exceed the right side of the inequality.

Exercises

3. Which of the $n$-gons inscribed in a given semicircle (so that one of the sides coincides with the diameter) has the largest area?

4. Prove that the average of triangles of a given area has a congruent triangle with the smallest perimeter.

5. Find out how the product $(1 + \frac{1}{a}) (1 + \frac{1}{b})$ behaves when merging positive numbers $a$ and $b$.

Prove that if the sum of positive numbers $x_1, x_2, \dots, x_n$ is equal to 1, then

$$(1 + \frac{1}{x_1}) (1 + \frac{1}{x_2}) \dots (1 + \frac{1}{x_n}) \geq (n+1)^n.$$

6. Find out how the sum $(a + \frac{1}{a})^2 + (b + \frac{1}{b})^2$ behaves when the positive numbers $a$ and $b$ merge.

Prove that if the sum of positive numbers $x_1, x_2, \dots, x_n$ is equal to 1, then

$$(x_1 + \frac{1}{x_1})^2 + (x_2 + \frac{1}{x_2})^2 + \dots + (x_n + \frac{1}{x_n})^2 \geq \frac{(n^2+1)^2}{n}.$$

7. Investigate the behavior of the fraction $(1-a)(1-b)/ab$ when merging positive numbers less than 1 $a$ and $b$ whose sum is 1.

Prove that if the sum of positive numbers $x_1, x_2, \dots, x_n$ is equal to 1, then

$$(1-x_1)(1-x_2) \dots (1-x_n)/x_1x_2 \dots x_n \geq (n-1)^n.$$

8. Investigate the behavior of the sum $\frac{1}{1+a} + \frac{1}{1+b}$ for a fixed product of positive numbers $a$ and $b$.

Prove the inequalities:

a) if the numbers $x_1, x_2, \dots, x_n$ are greater than 1, then

$$\frac{1}{1+x_1} + \frac{1}{1+x_2} + \dots + \frac{1}{1+x_n} \geq \frac{n}{1+\sqrt[n]{x_1x_2 \dots x_n}}.$$

6) if positive numbers $x_1, x_2, \dots, x_n$ are less than 1, then

$$\frac{1}{1+x_1} + \frac{1}{1+x_2} + \dots + \frac{1}{1+x_n} \leq \frac{n}{1+\sqrt[n]{x_1x_2 \dots x_n}}.$$

9. The numbers $a, \beta, \gamma, \delta$ belong to the interval $]0; \frac{\pi}{2}[\, a+\beta+\gamma+\delta=\pi$. Prove that $tg\alpha+tg\beta+tg\gamma+tg\delta \geq 4$.

10. Positive numbers $a, \beta, \gamma, \delta$ are such that $a+\beta+\gamma+\delta=\pi$. Prove that $\sin\alpha\sin\beta\sin\gamma\sin\delta \leq \frac{1}{4}$.

11. a) $a, b, c, d$ are positive numbers. Prove the inequality

$$\sqrt{\frac{a^2+b^2+c^2+d^2}{4}} \geq \sqrt{\frac{abc+abd+acd+bcd}{4}}.$$

6) $x_1, x_2, \dots, x_n$ are positive numbers, $k$ are natural numbers, $k \geq 2$. Prove the inequality

$$\sqrt{\frac{x_1^k+x_2^k+\dots+x_n^k}{n}} \geq \sqrt{\frac{x_1x_2\dots x_n}{n}}.$$

12. Which $n$ numbers $x_1, x_2, \dots, x_n$ should stand between the positive numbers $a$ and $b$ ($a<b$) to make a fraction

$$\frac{(a+x_1)(x_1+x_2)(x_2+x_3)\dots(x_n+1+x_n)(x_n+b)}{x_1x_2\dots x_n}$$

took the smallest possible value?

13. The sum of several non-negative numbers is 3, and the sum of the squares of these numbers is greater than 1. Prove that from these numbers you can choose three numbers whose sum is greater than 1.
