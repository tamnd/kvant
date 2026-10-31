---
id: 1970-7-nikolaev-sluchay-s-metodom-matematicheskoy-induktsii-1d822952
issue: kvant_1970_7
year: 1970
number: "7"
title: The Case of the Method of Mathematical Induction
authors:
  - Николаев Е. Г.
rubric: osnovnye-stati
page_first: 39
page_last: 39
page_labels: "37"
tag: LCG3
lang: en
source: kvant_digital
extraction: vision
content_sha256: a40ca41435aecc3a07294a49dca473a04551152d47fa7f2fd410496d52fc57ee
prompt_sha256: draft-1
translated_from: content/ru/1970/07/articles/05_nikolaev-sluchay-s-metodom-matematicheskoy-induktsii-1d822952.md
source_content_sha256: 9e725fd59a4e5a787dc1a883eae219ea517aa4825279ca3be6ef00353b7b9790
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 37⟧

The Case of the Method of Mathematical Induction

One day, a teacher gave 10th grade students the following homework problem:

To prove, by attempting to use the method of mathematical induction, that for any natural number $n$ the inequality is true

$$P_n = \frac{1 \cdot 3 \cdot 5 \dots (2n-1)}{2 \cdot 4 \cdot 6 \dots 2n} < \frac{1}{\sqrt{n+1}}.$$

Kolya V. found the following solution at home;

a) For $n = 1$ the inequality is true, since

$$P_1 = \frac{1}{2} < \frac{1}{\sqrt{2}}.$$

6) Let us show that the validity of inequality $P_{n+1} < \frac{1}{\sqrt{n+2}}$ follows from condition $P_n < \frac{1}{\sqrt{n+1}}$. To do this it is enough to show that

$$\frac{P_{n+1}}{P_n} < \frac{\sqrt{n+1}}{\sqrt{n+2}},$$

or

$$\frac{2n+1}{2n+2} < \sqrt{\frac{n+1}{n+2}},$$

or

$$(2n+1)^2(n+2) < 4(n+1)^3.$$

or

$$4n^3 + 12n^2 + 9n + 2 < 4n^3 + 12n^2 + 12n + 4,$$

or

$$0 < 3n + 2,$$

which is obviously true. Thus, a fairly provable inequality follows from the principle of mathematical induction.

However, while telling this solution at school, Kolya forgot to put one in the denominator and began to prove a more “gross” inequality:

$$P_n < \frac{1}{\sqrt{n}}.$$

Here's what he got:

a) For $n = 1$ the inequality is true, since

$$P_1 = \frac{1}{2} < \frac{1}{1}.$$

6) Let us show that condition $P_n < \frac{1}{\sqrt{n}}$ implies $P_{n+1} < \frac{1}{\sqrt{n+1}}$. To do this it is enough to show that

$$\frac{P_{n+1}}{P_n} < \frac{\sqrt{n}}{\sqrt{n+1}},$$

or

$$\frac{2n+1}{2n+2} < \sqrt{\frac{n}{n+1}},$$

or

$$(2n+1)^2(n+2) < 4(n+1)^3n,$$

or

$$4n^3 + 12n^2 + 9n + 2 < 4n^3 + 12n^2 + 12n + 4,$$

or

$$0 < 3n + 2,$$

which is obviously true. Thus, a fairly provable inequality follows from the principle of mathematical induction.

For those who understand this issue, we propose to prove two inequalities:

1. $P_n < \frac{1}{\sqrt{3,1n}}$.

It is interesting that in this inequality the coefficient 3.1 cannot be replaced by 3.2. The largest coefficient at which it remains true is π (the ratio of the circumference to the diameter).

2. $\frac{1}{2^3} + \frac{1}{3^3} + \dots + \frac{1}{n^3} < \frac{1}{4}$.
