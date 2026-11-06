---
id: 1990-12-bendukidze-nachinaem-s-neravenstva-evklida-35625d2f
issue: kvant_1990_12
year: 1990
number: "12"
title: Let's start with Euclid's inequality...
authors:
  - Бендукидзе А. Д.
rubric: shkola-v-kvante
page_first: 36
page_last: 37
page_labels: 34-35
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3d22fe3d53608867459e47b4c8d039ceccfef090724d11bcf23094d589dd2463
prompt_sha256: draft-1
translated_from: content/ru/1990/12/articles/11_bendukidze-nachinaem-s-neravenstva-evklida-35625d2f.md
source_content_sha256: d4cd6abcdfeebd6eb78bfb855e052534ec86269d1b75c8f27cec615683055a16
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 34⟧

---
running_head:
folio:
---

Mathematics 9-11
The published article is intended for children
Nyatiklassiki.

Let's get started
with inequality
Euclid...

Twenty-fifth statement of the fifth
kigi of the famous "Principles" of Euclid *) says: if four quantities
are proportional, then the most
the smallest is greater than the remaining two
(i.e. the sum of the most and least
necks is greater than the sum of the remaining two).
For the modern reader this is a statement
the situation will not seem particularly difficult
nom, but it contains pre-
*) Euclid - the great mathematician of ancient Greece,
who lived in the 3rd century BC. His main role is
Bota - the six-volume work "Principles" - had an impact
significant influence on the development of all mathematics.

sending many results
arithmetic and analysis. So, from his point of view
power can easily prove one in-
terse theorem on progressions, from
which implies the well-known inequality
art of Jacob Bernoulli*). But we're talking about
this is ahead.

So let's look at the inequality
Euclid. It should be said that ενkli-
The proof of this inequality is purely geometric. However,
this is not surprising - after all, the author
“Nachal” talks to its readers exclusively in geometric language! Not only geometric, but also purely arithmetic statements (hereinafter, the statement about the infinity of the set of prime numbers - the 20th statement of Book IX) are proven geometrically in the Elements.

However, the ideas underlying the evidence for these statements

*) Jacob Bernoulli - the founder of omens
family of Swiss mathematicians who lived in the second
half of the 17th century.

⟦folio 35⟧

---
running_head:
folio:
---

types, are presented by Euclid of the present clearly, and it is not difficult to “translate” them from geometric to arithmetic or algebraic language.

We must prove that if $a, b, c, d$ are positive numbers $u$

$$\frac{a}{b} = \frac{c}{d},$$

then the sum of the largest and smallest of these numbers is greater than the sum of the other two.

Indeed, without loss of generality, we can assume that the largest is $a$. From this proportion

$$d = b \frac{c}{a} = c \frac{b}{a},$$

and since both fractions $c/a$ and $b/a$ are less than one, then $d < b, d < c$. Therefore, $d$ is the smallest number, and therefore we need to prove the inequality

$$a + d > b + c.$$

We have

$$\frac{a}{b} = \frac{c}{d} \Leftrightarrow \frac{a}{b} - 1 = \frac{c}{d} - 1 \Leftrightarrow$$

$$\Leftrightarrow \frac{a - b}{b} = \frac{c - d}{d} \Leftrightarrow \frac{a - b}{c - d} = \frac{b}{d} \Leftrightarrow a - b =$$

$$= \frac{b}{d}(c - d).$$

Since $c - d > 0$ and $b/d > 1$, then

$$a - b > c - d,$$

or, which is the same thing, $a + d > b + c$. And this is what we wanted to prove.

Now we formulate and prove Bernoulli’s theorem on progressions.

Theorem. If $(a_n)$ is an arithmetic progression and $(b_n)$ is a geometric progression with a positive number $u$ $a_1 = b_1, a_2 = b_2, a_1 \neq a_2$, then the terms of the geometric progression starting with the third are greater than the corresponding terms of the arithmetic progression.

Proof. Let $m > 2$. We have

$$\frac{b_m}{b_{m-1}} = \frac{b_2}{b_1}.$$

If $(b_n)$ is an increasing progression, then of the four numbers written down, the largest will be $b_m$, and the smallest will be $b_1$. If the progression $(b_n)$ kills, then, on the contrary, $b_m$ is the smallest, and $b_1$ is the largest of these numbers. Thus, in both the first and second cases, according to Euclid’s inequality,

$$b_m + b_1 > b_{m-1} + b_2.$$

Recall that $b_1 = a_1, b_2 = a_2$, and denoting the difference of the progression $(a_n)$ by $d$, we obtain the inequality

$$b_m > b_{m-1} + d,$$

valid for any natural $m > 2$.

Giving $m$ the values ​​3, 4, 5, ..., $n$ successively, we see that

$$b_3 > b_2 + d,$$

$$b_4 > b_3 + d,$$

$$b_n > b_{n-1} + d.$$

Adding the inequalities, we get

$$b_n > b_2 + (n - 2)d = a_2 + (n - 2)d = a_1 + (n - 1)d = a_n.$$

So, for any $n > 2$

$$b_n > a_n,$$

which is what was required.

Corollary (Bernoulli's inequality). If $h > -1, h \neq 0$, then for any natural $n > 1$

$$(1 + h)^n > 1 + nh.$$

Indeed, consider two sequences

$$1, 1 + h, (1 + h)^2, ..., (1 + h)^n, ...,$$

$$1, 1 + h, 1 + 2h, ..., 1 + nh, ...$$

The first of them is an arithmetic progression, the second is a geometric progression, and they satisfy the conditions of Bernoulli's theorem. Pozotomu

$$(1 + h)^n > 1 + nh (n = 2, 3, 4, ...),$$

which is what needed to be proven.

Note that for $h > 0$ this inequality follows from the formula for the Newtonian biome, but for $-1 < h < 0$ it is not entirely obvious even to those familiar with the Newtonian biome.

A. Vendukidze
