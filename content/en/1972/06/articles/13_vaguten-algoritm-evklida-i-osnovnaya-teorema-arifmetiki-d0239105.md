---
id: 1972-6-vaguten-algoritm-evklida-i-osnovnaya-teorema-arifmetiki-d0239105
issue: kvant_1972_6
year: 1972
number: "6"
title: Euclid's algorithm and the fundamental theorem of arithmetic
authors:
  - Вагутен В. Н.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 32
page_last: 36
page_labels: 30, 32, 34
tag: KIHS
lang: en
source: kvant_digital
extraction: vision
content_sha256: 392329aece28059620614a49c76ae1725cad928902bdb6c93245702aacf902d5
prompt_sha256: draft-1
translated_from: content/ru/1972/06/articles/13_vaguten-algoritm-evklida-i-osnovnaya-teorema-arifmetiki-d0239105.md
source_content_sha256: 9c36138ddc815187212d04d736cb569cef0b645b5099630d46cca35e523d57bf
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

V.N. VAGUTEN
Euclise's algorithm and the fundamental theorem of arithmetic

This article was written based on materials from an experimental assignment for grades 8-9 at the All-Union Correspondence Mathematical School of the USSR Academy of Pedagogical Sciences at Moscow State University named after M.V. Lomonosov.

Everyone knows that any positive integer can be factorized into a product of prime factors; so for example,

$$400 = 2^4 \cdot 5^2, \quad 1001 = 7 \cdot 11 \cdot 13, \quad 290981 = 43 \cdot 67 \cdot 101.$$

Why is this decomposition the only one? A simpler fact: if the product mn is divisible by 43, then at least one of the numbers m and n must be divisible by 43. How to prove this?

These facts are considered obvious. However, it is not so easy to prove them. We will do this at the end of the article, and we will start with the simplest statements related to the divisibility of integers, and we will talk about how to find the most common divisor of two numbers without decomposing them into prime factors.

Throughout, we use Latin letters (a, b, c, d, etc.) to denote integers.

1. Dilimity of sum, difference and product

We say that an integer a is divisible by an integer b if there is an integer k such that a = kb. In this case, the number b is called the divisor of the number a.

Let us immediately derive two simple statements:

1°. If numbers a and b are divisible by c, then u their sum a + b, u their difference a - b is divided by c;
2°. If a is divisible by c and b is divisible by d, then their product ab is divisible by cd.

Let's prove 1°. Since a is divisible by c, then a = kc, where k is some integer. Similarly, b = mc, where m is an integer. Therefore, a + b = (k + m)c, a - b = (k - m)c, which means that each of the numbers a + b and a - b is divisible by c.

Let's prove 2°. Let a = kc, b = md. Then ab = (km)cd, which implies Statement 2°.

Problem 1. Prove that if a is divisible by b, a b is divisible by c, then a is divisible by c.

Task 2. Which of the following statements are true and which are false:

a) if one term is divisible by 6 and the other is not divisible by 6, then their sum is not divisible by 6;
b) if the sum of two terms is not divisible by 6, then at least one of them is not divisible by 6;
g) if the sum of two terms is not divisible by 6, then each term is not divisible by 6;

⟦folio 32⟧

4. Euclid's algorithm

In order to find the gcd of two numbers, you can, of course, act like this: write down all the divisors of each of the numbers, choose the common divisors, and then take the most of them. You can do it differently without separately finding the divisors of each of the numbers.

Let us prove the following important lemma.

Lemma 1. Let $a = bq + r$, $m=d a$ GCD $(a, b) = \text{НОД}(b, r)$.

To this end, we will show that the pair of numbers $(a, b)$ has exactly the same set of common divisors as the pair of numbers $(b, r)$. From here, of course, it will follow that the GCD for these pairs is the same. So, let us prove that every common divisor of the numbers $a$ and $b$ is also a divisor of the number $r$, and vice versa, that every common divisor of the numbers $b$ and $r$ is a divisor of the number $a$.

Let us first prove the first statement. Let $a$ and $b$ be divisible by $k$. Then $bq$ is divisible by $k$ (see 2° from point 1) and $r = a - bq$ is divisible by $k$ (see 1° from point 1).

Let's move on to the second statement. If $b$ and $r$ are divisible by $m$, then $bq$ is divisible by $m$ and $a = bq + r$ is divisible by $m$ (here we again used statements 1° and 2° from point 1).

The proven lemma allows you to easily and quickly find the gcd of two numbers. Let's see how it's done.

Example. Let's find what GCD is equal to (6069, 663).

Solution. Divide 6069 by 663 with a remainder:

$$6069 = 663 \cdot 9 + 102.$$

From the lemma it follows that GCD (6069, 663) = GCD (663, 102).

We are looking for gcd (663, 102). To do this, divide 663 by 102:

$$663 = 102 \cdot 6 + 51.$$

Again, applying the lemma, we get gcd (663, 102) = gcd (102, 51). But 102 is divisible by 51 without a remainder:

$$102 = 51 \cdot 2,$$

poset GCD (102, 51) = 51, therefore,

$$51 = \text{НОД} (102, 51) = \text{НОД} (663, 102) = \text{НОД} (6069, 663).$$

Answer. GCD (6069, 663) = 51.

The method of finding the most common divisor, based on the sequential application of Lemma 1, has a special name - the Euclidean algorithm.

Problem 13. Find the most common divisor of the numbers:

a) 987 654 321 and 123 456 789,
b) 7,777,777,777 and 777,777.

Problem 14. From a straight line 324 $cm \times 141$ $cm$ several squares are cut off from side 141 $cm$ until there remains a straight line with one of the sides

Fig. 3.

less than 141 $cm$. From the resulting straight line, squares are again cut off, the sides of which are equal to its smaller side, as long as this is possible, and so on (Fig. 3).

What squares will the straight liner be cut into? (Indicate their sizes and quantity).

So, Euclid's algorithm is a simple method of finding the most common divisor of two numbers. If we have two numbers $a$ and $b$, and $a > b > 0$, then first we divide $a$ by $b$ and get the remainder $r_1$, which is less than $b$. We then divide the number $b$ by $r_1$ and find the remainder $r_2$, which is less than $r_1$. Next, we divide the number $r_1$ by the number $r_2$, and we get the remainder $r_3$, less than $r_2$, and so on until some remainder $r_{n-1}$ is divided by the remainder $r_n$ completely, without a remainder (that is, $r_{n+1} = 0$).

It is clear that this process will definitely end, since each remainder is less than the previous one, and

⟦folio 34⟧

The solution $x = -6, y = 55$ is suitable for both equations.

One more note. We have given a method that allows you to find only one solution to such an equation. In fact, if there is one solution, there are infinitely many of them.

For example, numbers

$$x = -6 + 13t, y = 55 - 119t$$

($t$ is any integer) are also solutions to both of our equations. In fact,

$$119 (-6 + 13t) + 13 (55 - 119t) = 1$$
and of course
$$51 \cdot 119 (-6 + 13t) + 51 \cdot 13 (55 - 119t) = 51,$$
that is
$$6069 (-6 + 13t) + 663 (55 - 119t) = 51.$$

Formulas (*) give all solutions to these equations in integers. Let's prove it. Let $(x, y)$ be some solution:

$$119x + 13y = 1.$$

Let us subtract from this equation term by term the equality we already know

$$119 \cdot (-6) + 13 \cdot 55 = 1.$$

We get

$$119 (x + 6) + 13 (y - 55) = 0$$
or

$$119 (x + 6) = 13 (55 - y).$$

Since the left side of the last equality is divisible by 13, and the number 119 and 13 are mutually spilled, then the number $x + 6$ must be divisible by 13: $x + 6 = 13t$, where $t$ is some integer. Then $y = 55 - 119t$. Thus, we essentially found out how to find the solution to any linear equation $ax + by = c$ in integers. In general the result is:

In order for the equation $ax + by = c$ to have a solution in integers $(x, y)$, it is necessary and sufficient that $c$ is divisible by gcd $(a, b) = d$. If this condition is met $u (x_0, y_0)$ is one of the solutions to this equation, then all its solutions are given by the formulas

$$x = x_0 + b_1t, y = y_0 - a_1t,$$
$$a_1 = \frac{a}{d}, b_1 = \frac{b}{d}.$$

Task 16. Find integers $x$ and $y$ such that $85x + 204y = 17$.

Task 17. Do the following equations have solutions in integers:

a) $105x + 56y = 42$;
b) $104x + 65y = 43$?

Task 18. a) Is it possible to make a battery with a voltage of 220 $\theta$ by connecting in series elements of two types: voltage $6 \theta$ and $16 \theta$ - and if so, how many of both should be taken?

b) The same question if the voltage of the elements $6 \theta$ and $15 \theta$.

Task 19. Is it possible to mix 45 rubles into ruble, three-ruble and five-ruble bills so as to get only 20 bills?

6. Fundamental Theorem of Arithmetic

To prove the main theorem, we will take one more step - we will prove the lemma.

Lemma 3. If the product ab is divisible by c, and the numbers b and c are coprime, then a is divisible by c.

Indeed, since the integers $x$ and $y$, that $1 = bx + cy$. Multiplying both sides of the equality by $a$, we obtain that $a = abx + acy$. Since ab is divisible by $c$, then $abx$ and, of course, acy are divisible by $c$, which means their sum $a$ is also divisible by $c$.

Lemma 3 is very often used when solving a problem, and sometimes quite “imperceptibly”. For example, we relied on it in the previous paragraph when deriving formulas giving all solutions to the equation $119x + 13y = 1$ (there we saw the corresponding form in italics).

Task 20. Prove that if the number $a$ is divisible by coprime numbers $b$ and $c$, then $a$ is divisible by $bc$.

Task 21. Which of the following statements are true:

a) if $ab$ is divisible by 15, then at least one of the components is divisible by 15;
b) if $ab$ is divisible by 17, at least one of the components is divisible by 17;
b) if $a$ is divisible by 6 and $b$ is divisible by 10, then $ab$ is divisible by 15;
g) if $ab$ is divisible by 60 and $b$ is coprime with 10, then $a$ is divisible by 20.

Recall now that a natural number $p$ is called prime if it has equal division $p$ and 1.
