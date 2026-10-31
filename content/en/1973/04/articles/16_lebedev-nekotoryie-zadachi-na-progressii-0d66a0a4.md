---
id: 1973-4-lebedev-nekotoryie-zadachi-na-progressii-0d66a0a4
issue: kvant_1973_4
year: 1973
number: "4"
title: Some progression tasks
authors:
  - Лебедев В. П.
rubric: raznoe
rubric_sub: Разное
page_first: 59
page_last: 60
page_labels: 57-58
tag: WG3W
lang: en
source: kvant_digital
extraction: vision
content_sha256: 364d62df420fa257ec9739a57d980c777ed629b3802ec2ea70a3ca3dfc1f61c8
prompt_sha256: draft-1
translated_from: content/ru/1973/04/articles/16_lebedev-nekotoryie-zadachi-na-progressii-0d66a0a4.md
source_content_sha256: 23cb089e1aaf4fd524767aabb3853601cdcb493c21bd2ccf8c7f7a417530112d
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 57⟧

Some progression tasks

V. P. Lebedev

This article presents characteristic theorems and analyzes problems on progression proposed for advanced university exams.

Two main properties of progression

I. In an arithmetic progression, each of its terms (except for the first and last), multiplied by two, is equal to the sum of a series of constants, that is
$$2a_k = a_{k-1} + a_{k+1}.$$
The converse statement is also true: if in a sequence of numbers each member (except the first and last), multiplied by two, is equal to the sum of a series of constants, then this sequence is an arithmetic progression.

Proof. By the definition of the arithmetic progression $a_k = a_{k-1} + d$ and $a_k = a_{k+1} - d$, adding these expressions we get $2a_k = a_{k-1} + a_{k+1}$. Conversely, let $2a_k = a_{k-1} + a_{k+1}$, then $a_{k+1} - a_k = a_k - a_{k-1}$.

Substituting $k = 2, 3, \dots$ into the last equality and denoting $a_2 - a_1$ by $d$, we obtain
$$d = a_2 - a_1 = a_3 - a_2 = \dots = a_{k+1} - a_k = \dots$$
By definition, this means that $a_1, a_2, \dots$ is an arithmetic progression.

II. In geometric progression, the square of any of its terms (except the first and last) is equal to the product of its neighboring terms, that is
$$b_k^2 = b_{k-1}b_{k+1}.$$

Conversely, if in a sequence of numbers the square of each of them (except for the first and last) is equal to the product of a series of constants, then this sequence is a geometric progression.

The proof of these statements is independent.

Task and their solutions

Task 1. Find an arithmetic progression in which the sum of the first n terms is equal to $n^2$.

Solution. Using the formula for the sum of terms of an arithmetic progression, we find that for any n the equality
$$S_n = \left[ \frac{2a_1 + d(n-1)}{2} \right]n = n^2.$$
From here
$$d = \frac{2(n-a_1)}{n-1}.$$
This expression will not depend on n only for $a_1 = 1$. This means that in the exclusive progression $a_1 = 1$, $d = 2$ and the progression has the form 1, 3, 5, 7,...

The same result can be obtained otherwise:
$$a_n = S_n - S_{n-1} = n^2 - (n-1)^2 = 2n - 1.$$
Task 2. Are the numbers 1, $\sqrt{3}$, 3 modum and part of the same arithmetic progression?

Solution. That these numbers form an arithmetic progression, with $1 = a_m$, $\sqrt{3} = a_n$ and $3 = a_p$. Then
$$1 = a_1 + (m-1)d,$$
$$\sqrt{3} = a_1 + (n-1)d,$$
$$3 = a_1 + (p-1)d.$$
From here
$$a_1 = 1 - (m-1)d = \sqrt{3} - (n-1)d = 3 - (p-1)d,$$
$$\sqrt{3} = 1 + (n-m)d,$$
$$3 = 1 + (p-m)d.$$

⟦folio 58⟧

Solving the last equalities for $d$, we obtain

$$\frac{n - m}{p - m} = \frac{\sqrt{3} - 1}{2},$$

which is impossible, since the number on the right side is rational and the number on the right is irrational.

Problem 3. Under what condition are the numbers $a$, $b$ and $c$ an integer of one arithmetic progression?

Solution. Let $\{a_i\}$ be the original progression, with $a = a_m$, $b = a_k$ and $c = a_p$. Then $a = a_1 + d(m - 1)$, $b = a_1 + d(k - 1)$ and $c = a_1 + d(p - 1)$. Let us exclude $a_1$ from these equalities:

$$a - b = d(m - k)$$
$$b - c = d(k - p).$$

Dividing these equalities term by term, we get

$$\frac{a - b}{b - c} = \frac{m - k}{k - p}.$$

Since the numbers $m$, $k$ and $p$ are integers, then $\frac{a - b}{b - c}$ must be a rational number.

It is easy to check that if $\frac{a - b}{b - c} = \frac{s}{t}$, where $s$ and $t$ are integers, then we can find an arithmetic progression with terms $a$, $b$, $c$ (proof!).

Problem 4. Prove that between each two consecutive terms of the geometric progression $c$ positive and integer we can leave $k$ numbers so that the entire sequence forms a geometric progression.

Solution. Let us denote the terms of the progression by $a$, $b$, $c$, ..., $n$, ... We determine the denominator of the original progression $q$ by its first term $a$ and the $(k + 2)$th $b$ ($k$ terms must be supplied):

$$b = aq^{k + 1},$$

whence $q = \sqrt[k + 1]{\frac{b}{a}}$. The sequence will look like

$$a, a \sqrt[k + 1]{\frac{b}{a}}, a \sqrt[k + 1]{\left(\frac{b}{a}\right)^2}, \dots, b.$$

Between the numbers $b$ and $c$ there are also $k$ terms so that a geometric progression is formed with the value $\sqrt[k + 1]{\frac{c}{b}}$ and so on.

According to the conditions of the task

$$\frac{b}{a} = \frac{c}{b},$$

This means that the entire sequence will form a geometric progression with the value $\sqrt[k + 1]{\frac{c}{b}}$ and so on.

Problem 5. Find the denominator of a geometric progression in which each term, starting from the second, is equal to the difference of two neighboring ones (next and previous).

Solution. Let the progression have the form $b_1, qb_1, q^2b_1, \dots$.

From equality

$$q^{n + 2}b_1 - q^n b_1 = q^{n + 1}b_1$$

we find

$$q^2 - q - 1 = 0,$$

where

$$q = \frac{1 \pm \sqrt{5}}{2}.$$

Problem 6. Find the conditions under which the squares of three consecutive terms of an arithmetic progression are direct consecutive terms of a geometric progression.

Solution. Let $a, a + d, a + 2d$ be three consecutive terms of an arithmetic progression. If the squares of these numbers form a geometric progression, then

$$(a + d)^4 = a^2 (a + 2d)^2,$$

where

$$(a + d)^2 = \pm a (a + 2d).$$

If $(a + d)^2 = a (a + 2d)$, then $d = 0$.

If $(a + d)^2 = -a (a + 2d)$, then $d = a (-2 \pm \sqrt{2})$.

So, either $d = 0$ or $d = a (-2 \pm \sqrt{2})$.
