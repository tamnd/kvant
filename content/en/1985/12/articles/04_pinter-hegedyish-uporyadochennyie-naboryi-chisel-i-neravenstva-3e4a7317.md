---
id: 1985-12-pinter-hegedyish-uporyadochennyie-naboryi-chisel-i-neravenstva-3e4a7317
issue: kvant_1985_12
year: 1985
number: "12"
title: Ordered sets of numbers and inequalities
authors:
  - Пинтер Л.
  - Хегедыш Й.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 16
page_last: 17
page_labels: 14-15
tag: MCIF
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7e1bfd895f82bedaa121ed97c83ab465a3d75dfd754c7f02f482c2cbf72aa1ac
prompt_sha256: draft-1
translated_from: content/ru/1985/12/articles/04_pinter-hegedyish-uporyadochennyie-naboryi-chisel-i-neravenstva-3e4a7317.md
source_content_sha256: 8cd9e2e40a3bb466668d4baddc43f09e3485c43ac2595a20f5d86179497baede
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 14⟧

Ordered sets of numbers and inequalities

L. PINTER, I. HEGEDISH

Kolya's parents keep paper money in envelopes. One day they took out three envelopes and placed them in front of him. One of the envelopes contained rubles, another contained three rubles, and the third contained fives. The parents asked Kolya to pull out two pieces of paper from one of the envelopes, three from another, and four pieces of paper from the remaining envelope.

How should Kolya choose envelopes to get the most possible amount, and how to get the most possible amount possible? To find the accumulated amount when selecting envelopes derivatively, you need to put the numbers 2, 3, 4 in the appropriate order in Table 1 in the bottom line along with question marks, then take the product of the numbers in the columns and add them.

Table 1

1? 3? 5?

Table 1

If Kolya wants to collect the highest possible amount, then he must take out four pieces of paper from the envelope with fives, three pieces of paper from the envelope with threes and two pieces of paper from the envelope with rubles:

$$5 \cdot 4 + 3 \cdot 3 + 1 \cdot 2 = 31.$$

If Kolya wants to collect the most possible amount, then he must take out the most possible number of pieces of paper, that is, two from an envelope with fives, three from an envelope with three rubles and four from an envelope with rubles, that is

$$5 \cdot 2 + 3 \cdot 3 + 1 \cdot 4 = 23.$$

Ordered triples

In general, this problem can be formulated as follows. Let the given triples of positive numbers

$$a_1, a_2, a_3,$$

$$b_1, b_2, b_3.$$

Let's consider the amount

$$S = a_1 b_i + a_2 b_j + a_3 b_k,$$

where $i, j, k$ are the numbers 1, 2, 3, written in what order. How to choose this order so that the sum $S$ turns out to be the most possible (respectively, the most possible) of the possible ones?

It is clear that if the most of the numbers $a$ is multiplied by the most of the numbers $b$, the average of the numbers $a$ by the average of the numbers $b$ and finally the name of the numbers $a$ the name of the numbers $b$ and add these products, then the maximum possible value $S$ will be obtained (if the average of the numbers $a$ or the average of the numbers $b$ are equal, then this maximum value $S$ is not obtained in the only way). If the most of the numbers $a$ is multiplied by the most of the numbers $b$, the average by the average, etc., then we get the most possible value $S$.

Using this method, you can simply solve problem M762 (see «Kvant», 1982, No. 9)*.

Prove that for any positive numbers $a, b, c$ the following inequalities are true:

$$a + b + c \leq \frac{a^2 + b^2}{2c} +$$

$$+ \frac{b^2 + c^2}{2a} + \frac{c^2 + a^2}{2b} \leq \frac{a^3}{bc} + \frac{b^3}{ca} + \frac{c^3}{ab}. \quad (1)$$

Let us first prove the first inequality. Let's write down two triples of numbers

$$a^2, b^2, c^2,$$

$$\frac{1}{a}, \frac{1}{b}, \frac{1}{c}.$$

Since the numbers $a, b, c$ are positive, the most of the numbers of the first triple is located above the most of the numbers of the second triple, the most of the numbers of the first triple is located above the most of the numbers

⟦folio 15⟧

second three. Therefore, for these triples the sum

$$a^2 \cdot \frac{1}{a} + b^2 \cdot \frac{1}{b} + c^2 \cdot \frac{1}{c}$$

is minimal, and therefore

$$a^2 \frac{1}{a} + b^2 \frac{1}{b} + c^2 \frac{1}{c} \leq a^2 \frac{1}{b} + b^2 \frac{1}{c} + c^2 \frac{1}{a},$$

(2)

$$a^2 \frac{1}{a} + b^2 \frac{1}{b} + c^2 \frac{1}{c} \leq a^2 \frac{1}{c} + b^2 \frac{1}{a} + c^2 \frac{1}{b}.$$

(3)

Adding inequalities (2) and (3), we obtain:

$$2(a+b+c) \leq a^2 \frac{1}{b} + b^2 \frac{1}{c} + c^2 \frac{1}{a} + a^2 \frac{1}{c} + b^2 \frac{1}{a} + c^2 \frac{1}{b} = \frac{a^2+b^2}{c} + \frac{b^2+c^2}{a} + \frac{c^2+a^2}{b}.$$

To obtain the second of inequalities (1), consider triples of numbers

$$a^3, b^3, c^3,$$

$$\frac{a}{abc}, \frac{b}{abc}, \frac{c}{abc}.$$

Under the most (resp. most) of the numbers of the first three is written the most (smallest) number of the second three. That's why

$$a^3 \frac{a}{abc} + b^3 \frac{b}{abc} + c^3 \frac{c}{abc} \geq a^3 \frac{b}{abc} + b^3 \frac{c}{abc} + c^3 \frac{a}{abc} + b^3 \frac{c}{abc} + c^3 \frac{a}{abc} + c^3 \frac{b}{abc} = \frac{a^2}{c} + \frac{b^2}{a} + \frac{c^2}{b},$$

(4)

$$a^3 \frac{a}{abc} + b^3 \frac{b}{abc} + c^3 \frac{c}{abc} \geq a^3 \frac{c}{abc} + b^3 \frac{a}{abc} + c^3 \frac{b}{abc} + c^3 \frac{a}{abc} + c^3 \frac{b}{abc} = \frac{a^2}{c} + \frac{b^2}{a} + \frac{c^2}{b},$$

(5)

Adding inequalities (4) and (5), we obtain

$$2\left(\frac{a^3}{bc} + \frac{b^3}{ca} + \frac{c^3}{ab}\right) \geq \frac{a^2}{c} + \frac{b^2}{a} + \frac{c^2}{b} + \frac{b^2}{c} + \frac{c^2}{a},$$

$$+ \frac{c^2}{a} = \frac{a^2+b^2}{c} + \frac{b^2+c^2}{a} + \frac{c^2+a^2}{b},$$

which is what was required.

Exercises
Prove the inequalities:
1. $a^4 + b^4 \geq a^3 b + ab^3$.
2. $a^3 b + b^3 c + c^3 a \geq a^2 bc + b^2 ca + c^2 ab$.
3. $\frac{a^3 b}{c} + \frac{a^3 c}{b} + \frac{b^3 a}{c} + \frac{c^3 b}{a} \geq 6abc$ (here $a > 0, b > 0, c > 0$).
4. If $a_1 \geq a_2 \geq a_3 \geq a_4, b_1 \geq b_2 \geq b_3$, then $3(a_1 b_1 + a_2 b_2 + a_3 b_3) \geq (a_1 + a_2 + a_3)(b_1 + b_2 + b_3)$.
5. If $a > 0, b > 0, c > 0$, then

$$\frac{a}{b+c} + \frac{b}{a+c} + \frac{c}{a+b} \geq \frac{3}{2}.$$

Some generalizations

Let now be given a set of $n$ numbers

$$a_1 \geq a_2 \geq a_3 \geq ... \geq a_n,$$

$$b_1 \geq b_2 \geq b_3 \geq ... \geq b_n.$$

Let us consider all possible sums of the form $i$ $\sigma = a_1 b_1 + a_2 b_2 + ... + a_n b_n$, where $i_1, i_2, ..., i_n$ is some permutation of the numbers 1, 2, ..., $n$.

The number of such sums is finite, and therefore among them there are the most $S$ and the most $s$. It is not difficult to report that $S = a_1 b_1 + a_2 b_2 + ... + a_n b_n$ and $s = a_1 b_n + a_2 b_n - 1 + ... + a_n b_1$.

Let's prove it. Let us first note that for any four numbers $a, b, c, d$ such that $a \geq b$ and $c \geq d$, the inequality holds

$$ac + bd \geq ad + bc,$$

(*) which is equal to the obvious inequality

$$(a - b)(c - d) \geq 0.$$

After this, replacing our statement is proven without difficulty. In fact, if in some sum $\sigma$ there are the following $a_e b_q$ and $a_k b_p$, for which $e < k, q > p$, that is, $b_p \geq b_q$, then, by rearranging the numbers $b_p$ and $b_q$, we obtain a no less sum $\sigma'$ with the following $a_e b_p$ and $a_k b_q$.

Consistently carrying out such permutations, we arrive at the sum $S$, therefore $S \geq \sigma$.

Similarly, if $b_q \geq b_p$, then, swapping these numbers, we obtain a sum not greater than $\sigma$.

Since as a result of several permutations we can arrive at the sum $s$, then $\sigma \geq s$.

So, for any sum $\sigma$

$$s \leq \sigma \leq S,$$

(B)

Moreover, equality (B) is possible only when one of the sets $a_1, ..., a_n, \text{ либо } b_1, ..., b_n$ contains equal numbers.

To summarize, we can formulate a general method for proving the inequality: if the sets of numbers $a_1, a_2, ..., a_n$ and $b_1, b_2, ..., b_n$ are equally ordered (that is, from $a_k \geq a_l$ it follows that $b_k \geq b_l$), then $a_1 b_1 + a_2 b_2 + ... + ... + a_n b_n \geq a_1 b_1 + a_2 b_2 + ... + ... + a_n b_n$, (here $i_1, i_2, ..., i_n$ is an arbitrary permutation of the numbers 1, 2, ..., $n$).
