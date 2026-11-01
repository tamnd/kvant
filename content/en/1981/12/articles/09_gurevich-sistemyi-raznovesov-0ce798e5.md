---
id: 1981-12-gurevich-sistemyi-raznovesov-0ce798e5
issue: kvant_1981_12
year: 1981
number: "12"
title: Weight systems
authors:
  - Гуревич Г. А.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 36
page_last: 37
page_labels: 34-35
tag: P9P3
lang: en
source: kvant_digital
extraction: vision
content_sha256: 778bb8da4f2731c47ab7c2ad2b38afdca45d22a9ca8152806a33b640a46e9c8e
prompt_sha256: draft-1
translated_from: content/ru/1981/12/articles/09_gurevich-sistemyi-raznovesov-0ce798e5.md
source_content_sha256: 274f86adf89fc9e8fb6c9c6f1dc47c38e9907a6329eadd5dc1dfe3d2c56747a8
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

G. Gurevich

Weight systems

Erdem's problem

A system of weights is a set of natural numbers from which it is impossible to extract two different sets with the same sum (for example, the numbers 1, 3, 7, 20 form a system of weights, but the numbers 1, 2, 3, 4, 5, 8 do not form: 2+3+4=8+1).

In 1956, the famous Hungarian mathematician P. Erdem formulated the following problem: Find the smallest natural number m(k) such that from the natural numbers not exceeding m(k), it is possible to select a system of weights of k numbers.

Another, in a certain sense, figurative Erdem problem is the task of finding the largest number of weights l(N) among numbers not exceeding a given natural number N.

Despite the great interest caused by the posed problems among specialists in number theory, coding theory and combinatorial analysis, they have not yet been completely solved. Only some estimates of the numbers m(k) and l(N) have been obtained, and the question of exactly these estimates remains open.

In problem M675 (“Quant”, 1981, No. 3) we invited our readers to obtain some estimates, related to Erdem’s problem, for specific k and N. Namely, we proposed to prove that from numbers less than 1000, it is possible to select a system of weights a) of 10 numbers; b) from 11 numbers; c) out of 14 numbers it is impossible to choose one of them; f) if the numbers form a system of weights, then the sum of their figurative values ​​will not exceed 5/2. And finally, we proposed e) from numbers less than 700, choose a system of weights consisting of 11 numbers.

Estimates from above

Some rough upper bounds for the number m(k) can be obtained from very simple considerations.

In fact, k numbers 1, 2, ..., 2^{k-1} form systems of weights for any natural number k.

Exercise 1. Prove it.

Therefore, estimateindo, m(k) ≤ 2^{k-1}. In particular, from the numbers 1, 2, ..., 1000, a system of weights is distinguished from 10 numbers 1, 2, ..., 2^9 = 512. This gives the solution to point a) problem M675.

It is easy to construct a system of weights from 11 numbers, no more than 1000.

In fact, k numbers 3, 3·2, 3·2^2, ..., 3·2^{k-1} also form systems of weights.

Sovv. Let's add two numbers 3·2^{k-1} - 1 and 3·2^{k-1} + 1 to them and prove that the resulting numbers also form systems of weights.

If any set of these numbers contains both added numbers (then the set of remaining numbers does not contain them), then its sum is not less than 3 2^k, and, therefore, greater than the sum of all other numbers.

If any set contains one added number, then any set that does not contain it will have a sum that, when divided by 3, gives a remainder different from the remainder when divided by 3 the sum of the original set.

For k=9 we obtain a system of weights 3, 6, 12, ..., 767, 768, 769 from 11 numbers (this gives the solution to point 6)).

So, m(11) ≤ 769. In general, we obtained the estimate m(k) ≤ 3 2^{k-2} + 1.

Score

Let us now try to estimate the number m(k) in size. Let a₁ < a₂ < ... < aₖ be a system of weights of k numbers (k>1).

It is obvious that ka_k - 1 ≥ a₁ + a₂ + ... + aₖ. Since any two sets of given numbers have different sums, and the total number of a set of k numbers is 2^k - 1, we obtain the inequality a₁ + a₂ + ... + aₖ ≥ 2^k - 1.

Exercise 2. Make sure of this.

Therefore ka_k ≥ 2^k, that is, a_k ≥ 2^k/k. In particular, for k=14 we obtain a₁₄ ≥ 2^14/14 > 1000. This gives the solution to point b).

So m(k) ≥ 2^k/k.

Now we can estimate the sum $\frac{1}{a_1} + ... + \frac{1}{a_k}$. Since any system of weights is itself a system of weights, the inequality a_i ≥ $\frac{2^i}{i}$ is valid for any i greater than 1. Hence

$$\frac{1}{a_1} + \frac{1}{a_2} + ... + \frac{1}{a_k} \leq 1 + \frac{2}{2^2} + \frac{3}{2^3} + ... + \frac{k}{2^k}.$$

Let us calculate the sum S(k) = $\frac{2}{2^2} + ... + \frac{k}{2^{k-1}}$ and therefore,

$$S(k) = 2S(k) - S(k) = 1 + \frac{1}{2^2} + \frac{1}{2^3} + ... + \frac{1}{2^{k-1}} - \frac{k}{2^k} = \frac{3}{2} - \frac{k+2}{2^k} < \frac{3}{2}.$$

Thus,

$$\frac{1}{a_1} + \frac{1}{a_2} + ... + \frac{1}{a_k} < \frac{5}{2},$$

— the statement of point d) has also been proven.

Relatively recently (1977), American mathematicians F. Hanson, J. Steele and F. Stepger proved a stronger inequality:

$$\frac{1}{a_1^2} + \frac{1}{a_2^2} + ... + \frac{1}{a_k^2} < \frac{2^s}{2^{s-1}}$$

for any s>0. In particular, when s=1

⟦folio 35⟧

Let's shine

$$\frac{1}{a_1} + \dots + \frac{1}{a_k} < 2.$$

Some observations

The numbers 1, 2, 4, ..., 512, as we have seen, form a system of 10 weights. Let's see if it is possible to use this system to obtain a system of weights of 11 numbers less than 1000.

Consider 11 numbers: 999-0, 999-1, ..., 999-512. Let us prove that this is a system of weights.

We will further call the diin of a set of cardinal numbers in this set.

First of all, it is clear that two sets of the same length have different sums (we subtract zero and numbers from 999; giving systems of weights).

Let us now prove that the longer set has a larger sum.

In fact, the sum of the six smallest numbers in the system: (999-512) + (999-256) + ... + (999-16) is greater than the sum of the five largest of these numbers: 999 + (999-1) + (999-2) + (999-4) + (999-8).

Now let $a_1, a_2, ..., a_m$ and $b_1, b_2, ..., b_l$ be two sets of our numbers, and $m > l$. If $m > 6$, then $a_1 + ... + a_m$ is a lot, more than $b_1 + ... + b_l$. If $m \leq 6$, then $a_1 + ... + a_m$ is not less than the sum $m$ of the smallest numbers of our system, which in turn is greater than the sum $l$ ($l < m$) of the largest numbers of the system (make sure of this!); the last amount, of course, is no less than $b_1 + ... + b_l$.

So, we have built another system of weights of 11 numbers less than 1000.

Let us analyze the proof.

First of all, we note that together with the number 999 we could take any number $a$ for which $a + (a-1) + (a-2) + (a-4) + (a-8) < (a-16) + ... + (a-512)$, that is, any $a > 512 + ... + 16 - 8 - 4 - 2 - 1 = 993$.

In addition, we took advantage of the fact that the sums of sets of the same length are different.

Let's try to summarize our observations. Take $k$ natural numbers $a_1 < a_2 < ... < a_k$ for which the sums of any two sets of the same length are different.

Now, if $k$ is even ($k = 2l$), choose the number $a$ so that the inequality $(a - a_{2l}) + ... + (a - a_l) > (a - a_{l-1}) + ... + (a - a_1) + a$ is satisfied, and if $k$ is odd ($k = 2l+1$), then the inequality $(a - a_{2l+1}) + ... + (a - a_{l+1}) > (a - a_{l-1}) + ... + (a - a_1) + a$.

The numbers $a, a - a_1, ..., a - a_k$ constructed in this way form a system of weights of length $k+1$. Exercise 3.

3. Prove this statement.

4. Prove that of two sets of the same length, consisting of different numbers of the constructed system, the set containing the lowest sum of numbers has the greater sum.

Improved weight system

Using the described method, we can build systems of weights of any length $k$.

Let us first construct a sequence of numbers $a_1 < a_2 < ... < a_n < ...$ satisfying the following relation:

$$a_1 = 0, a_2 = 1,$$

$$a_{2n+1} = (a_{n+1} + a_{n+2} + ... + a_{2n}) - (a_1 + a_2 + ... + a_{n-1}) + 1,$$

$$a_{2n+2} = (a_{n+1} + a_{n+2} + ... + a_{2n+1}) - (a_1 + a_2 + ... + a_n) + 1$$

at $n \geq 1$.

Let's write down the first identical terms of this sequence: 0, 1, 2, 4, 7, 13, 24, 46, 88, 172, 337.

Let's put $a = (a_{11} + a_{10} + ... + a_6) - (a_5 + a_4 + a_3 + a_2 + a_1) + 1 = 667$.

According to what was proven earlier, we obtain a system of weights of 11 numbers: 667, 667-1, 667-2, ..., 667-337. All these numbers are less than 700. This gives the solution to point e) of the problem in Exercise 5. Prove that $m(6) = 24$.

Conver-Guy system

Of all the systems of weights currently known, the system built by the American mathematicians Conver and Guy claims to be the “record holder”. In particular, for weights of 11 numbers, their largest number is 594.

The construction proposed by Conver and Guy is as follows (see table):

| $n$ | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $x_n$ | 0 | 1 | 2 | 3 | 3 | 3 | 4 | 4 | 4 | 4 | 5 | 5 | 5 |
| $y_n$ | 0 | 0 | 0 | 1 | 1 | 2 | 3 | 3 | 4 | 5 | 6 | 6 | 7 |
| $z_n$ | 0 | 1 | 2 | 4 | 7 | 13 | 24 | 44 | 81 | 161 | 309 | 594 | 1161 |

The first row of the table contains 0 and natural numbers; in the second line there is a sequence $(x_n)$ in which any number $k > 0$ occurs equal to $k$ times; in the third line - the sequence $(y_n)$, obtained by subtracting the second line from the numbers of the first line $(y_n = n - x_n)$. The sequence $(z_n)$ is given recurrently: $z_0 = 0$, $z_1 = 1$, $z_{n+1} = 2z_n - z_{n-1}$. (For example, to calculate $z_7$, you would take $z_6 = 24$, multiply it by 2, and subtract $z_3 = 4$ because $y_6 = 3$.) The sequence $(z_n)$ is written in the last row of the table. Exercise 6. Prove that $x_n = (\sqrt{2n})$, where $(x)$ denotes the integer closest to $x$.

Converya and Guya hypothesized that for any $n > 0$ the numbers $a_0 = z_n - z_0$, $a_1 = z_n - z_1$, ..., $a_{n-1} = z_n - z_{n-1}$ form systems of weights, and tested it for all $n \leq 40$. (With $n = 11$ the following system of weights is obtained: 594, 593, 592, 590, 587, 581, 570, 550, 510, 473, 285; as we see, the largest number here is 594.).

In 1974, the Indian mathematician H. Gupta proved the validity of the Conver-Guy conjecture and thereby obtained an estimate for the number $m(k)$: $m(k) \leq z_k$. More recently, the Soviet mathematician V.D. Yakovelev independently obtained another proof.

It was very interesting for each $n$ to find an example of a system of weights from $n$ numbers, in which the largest number would show that the procedure for obtaining the Conver-Guy system of weights is still not the best.
