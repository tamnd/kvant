---
id: 1970-9-bendukidze-sulakvelidze-vyichislenie-summ-26b17740
issue: kvant_1970_9
year: 1970
number: "9"
title: Calculating amounts
authors:
  - Бендукидзе А. Д.
  - Сулаквелидзе А. К.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 39
page_last: 41
page_labels: 37-39
tag: 77RH
lang: en
source: kvant_digital
extraction: vision
content_sha256: d09a29173efa15d8c0fe905eb294324d0d5a3e3e9476e1777e6f6c63f5e3820e
prompt_sha256: draft-1
translated_from: content/ru/1970/09/articles/07_bendukidze-sulakvelidze-vyichislenie-summ-26b17740.md
source_content_sha256: 73646112a227d2669d3ffd84430f964c665cd991ebf70b40ebe04d5deec31260
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 37⟧

CALCULATING SUM

Calculating sums is one of the most important and interesting questions in mathematics. There are various methods for calculating sums. The article talks about two of them.

1. In mathematics and its numerous applications, a special sign is used to abbreviate the sum. This is Σ - the letter of the Greek alphabet "sigma". Writing a sum using the Σ sign is often very convenient. Let's get to know this sign.

Let a sum of the form be given
$$a_1 + a_2 + \dots + a_n.$$
All terms of this sum are designated by one letter, to distinguish the use of subscripts. This amount can be abbreviated as follows:

$$\sum_{k=1}^{n} a_k.$$
It reads: “sigma $a_k$, $k$ varies from 1 to $n$.” For such a notation, we take a “typical” summand of the sum, in our case $a_k^*$, write the sign Σ in front of it and indicate the limits of change $k$. For example, record

$$\sum_{k=1}^{10} k$$
means the amount
$$1 + 2 + 3 + 4 + 5 + 6 + 7 + 8 + 9 + 10,$$
*) $a_k$ is called the common term of the sum.

and the recording
$$\sum_{k=1}^{n} \frac{1}{k(k+1)}$$

- amount
$$\frac{1}{1 \cdot 2} + \frac{1}{2 \cdot 3} + \dots + \frac{1}{(n-1)n} + \frac{1}{n(n+1)}$$.

It is easy to check the following properties of the sign Σ:
$$\sum_{k=1}^{n} 1 = n, \quad \sum_{k=1}^{n} ca_k = c \sum_{k=1}^{n} a_k,$$
$$\sum_{k=1}^{n} (a_k + b_k) = \sum_{k=1}^{n} a_k + \sum_{k=1}^{n} b_k.$$

Let's check, for example, the second property.

By definition
$$\sum_{k=1}^{n} ca_k = ca_1 + ca_2 + \dots + ca_n,$$

Therefore, according to the well-known property of sums, we have:
$$\sum_{k=1}^{n} ca_k = c(a_1 + a_2 + \dots + a_n).$$

But the expression in brackets is nothing more than
$$\sum_{k=1}^{n} a_k$$
and therefore
$$\sum_{k=1}^{n} ca_k = c \sum_{k=1}^{n} a_k.$$

⟦folio 38⟧

The remaining two properties are checked in a similar way.

2. Let's consider the question of calculating a sum of the form

$$\sum_{k=1}^{n} f(k) = f(1) + f(2) + \dots + f(n),$$

where $f$ is a known function of an integer argument defined on the segment $[1, n]$ of the natural series.

This sum is easy to calculate if we successfully solve the function $F$ defined on the segment $[1, n+1]$ of the natural series, which for all $k, 1 \leq k \leq n$, the equality is true

$$f(k) = F(k+1) - F(k).$$

In fact, putting $k = 1, 2, \dots, n-1, n$ in this equality successively, we obtain:

$$f(1) = F(2) - F(1),$$
$$f(2) = F(3) - F(2),$$
$$f(3) = F(4) - F(3),$$

$$f(n-1) = F(n) - F(n-1),$$
$$f(n) = F(n+1) - F(n).$$

Adding these equalities, we arrive at the following formula:

$$\sum_{k=1}^{n} f(k) = F(n+1) - F(1).$$

Thus, if the function $F$ is found, the sum (1) is calculated simply.

Let us illustrate formula (3) of geometric progression.

On figure 1 we need to find the sum (1), denoted simply by $\Sigma$, as the length of the vertical segment. Each term of the form $f(k)$ corresponds to the length of the red segment equal to the difference between the lengths of the green segments $F(k+1)$ and $F(k)$. Obviously, the sum of the lengths of all red segments is equal to the difference between the lengths of the first and last green segments.

Example 1. Calculate the sum

$$\frac{1}{1.2} + \frac{1}{2.3} + \frac{1}{3.4} + \dots + \frac{1}{n(n+1)},$$

that is

$$\sum_{k=1}^{n} \frac{1}{k(k+1)}.$$

Here

$$f(k) = \frac{1}{k(k+1)},$$

and, as is easy to check, it can be represented as the following difference:

$$f(k) = \frac{1}{k} - \frac{1}{k+1}.$$

Therefore, if we denote

$$F(k) = -\frac{1}{k},$$

then formula (2) will be satisfied for all natural $k$:

$$f(k) = F(k+1) - F(k).$$

Applying formula (3), we easily obtain

$$\sum_{k=1}^{n} \frac{1}{k(k+1)} = 1 - \frac{1}{n+1} = \frac{n}{n+1}.$$

Example 2. Find the sum of the terms of the following geometric progression:

$$q, q^2, q^3, \dots, q^n \quad (q \neq 1).$$

Here $f(k) = q^k$, and, using the equality $q^{k+1} - q^k = q^k(q-1)$, we can write

$$q^k = \frac{q^{k+1}}{q-1} - \frac{q^k}{q-1}.$$

From this we can see that we can put

$$F(k) = \frac{q^k}{q-1},$$

and therefore

$$\sum_{k=1}^{n} q^k = \frac{q^{n+1}}{q-1} - \frac{q}{q-1} = \frac{q^{n+1}-q}{q-1}.$$

We obtained the well-known formula.

⟦folio 39⟧

Example 3. Calculate the sum
$$\sum_{k=1}^{n} \sin kx (x \neq 2\pi n).$$
It is easy to check that
$$\sin kx = \frac{\cos(k-0,5)x - \cos(k+0,5)x}{2\sin 0,5x},$$
that is
$$\sin kx = F(k+1) - F(k),$$
Where
$$F(k) = -\frac{\cos(k-0,5)x}{2\sin 0,5x}.$$
Now, based on formula (3), after simple transformations we obtain
$$\sum_{k=1}^{n} \sin kx = \frac{\sin 0,5(n+1)x \sin 0,5nx}{2\sin 0,5x}.$$
The reader himself is convinced that formula (3) provides an effective way to calculate the sum (1). The main thing is to find the function $F$. Often, unfortunately, this is not an easy task, and sometimes even insurmountable.
3. Let now two finite sequences of numbers be given
$$u_1, u_2, \dots, u_n,$$
And
$$v_1, v_2, \dots, v_n$$
and you need to calculate the amount
$$\sum_{k=1}^{n} u_k v_k.$$
One transformation that is often useful here is one that was pointed out by the replaced Norwegian mathematician Abel. Let $V_k$ be the sum of the first $k$ terms of sequence (4), that is
$$V_k = \sum_{i=1}^{k} v_i = v_1 + v_2 + \dots + v_k.$$
It is clear that $v_1 = V_1$; if $k > 1$, then
$$v_h = V_h - V_{h-1}.$$

Because
$$\sum_{k=1}^{n} u_k v_k = u_1 v_1 + u_2 v_2 + \dots + u_n v_n = u_1 V_1 + u_2 (V_2 - V_1) + \dots + u_n (V_n - V_{n-1})$$
Opening the brackets and grouping the terms by two, we get
$$\sum_{k=1}^{n} u_k v_k = (u_1 - u_2) V_1 + (u_2 - u_3) V_2 + \dots + (u_{n-1} - u_n) V_{n-1} + u_n V_n$$
or finally:
$$\sum_{k=1}^{n} u_k v_k = u_n V_n - \sum_{k=1}^{n-1} (u_{k+1} - u_k) V_k.$$ (5)
A geometric interpretation of this method is given at figure 2. Each term of the form $u_k v_k$ corresponds to the area of ​​the rectangle (green). Terms of the form $(u_{k+1} - u_k) V_n$ correspond to the areas of the red rectangles. The expression $u_n V_n$ is the area of ​​the entire rectangle. After this, formula (5) becomes very visible.

Example 4. Calculate the sum
$$1^2 + 2^2 + \dots + n^2.$$
Let us denote the amount sought by $S$ and write it down using the sign $\Sigma$:
$$S = \sum_{k=1}^{n} k^2.$$
