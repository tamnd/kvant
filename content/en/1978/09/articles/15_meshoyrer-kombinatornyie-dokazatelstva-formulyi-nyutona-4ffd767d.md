---
id: 1978-9-meshoyrer-kombinatornyie-dokazatelstva-formulyi-nyutona-4ffd767d
issue: kvant_1978_9
year: 1978
number: "9"
title: Combinatorial proofs of Newton's formula
authors:
  - Мешойрер Р.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 47
page_last: 48
page_labels: 45-46
tag: FIUF
lang: en
source: kvant_digital
extraction: vision
content_sha256: 154b343379e8e79b86fccb20e55efcf0b0892f9f26915bcbf75602811edf4e89
prompt_sha256: draft-1
translated_from: content/ru/1978/09/articles/15_meshoyrer-kombinatornyie-dokazatelstva-formulyi-nyutona-4ffd767d.md
source_content_sha256: 1ab3ffc507f7977df62f4f554592ed66771aeb8874252833b2c0c5d44daed15f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 45⟧

The holidays are here, school days have begun. In our section of the magazine there is also a new academic year, already the third in a row. Over the past two years, the articles in this section have addressed the most difficult and important issues directly related to the school curriculum. We would like to draw your attention to already published articles - it is useful to refer to them as you study school textbooks:

Algebra and the beginnings of analysis

“How the concept of function arose and developed” (1977, No. 7),
"Even and Checked Functions" (1977, No. 4),
"Periodic Functions" (1976, No. 12),
"Caution: maximum!" (1976, no. 10),
“The geometric meaning of arbitrary” (1977, no. 2),
“What does a parabola look like?” (1978, no. 3),
"A Combinatorial Proof of Newton's Formula" (1978, No. 8),
“Addition of harmonic oscillations” (1976, No. 11),
"Area and Integral" (1977, No. 5),
"Derivative of the Exponential Function" (1977, No. 12),
“Analysis helps algebra” (1978, No. 6),
“Questions on algebra and analysis” (1978, No. 2),
“17 Problems in Analysis” (1977, No. 1),

Geometry

"The Mastery of Symmetry" (1976, No. 9),
“Composition of two axis symmetries” (1978, No. 2),
"Homotheties and Remarkable Points in a Triangle" (1977, no. 10),
“Shchest 驹 proofs of the theorem on medians” (1978, No. 4),
"Distance from a Point to a Plane" (1977, No. 3),
"What do you mean 'more'?" (1977, no. 11),
"In Search of a Determination of Surface Area" (1978, No. 5),

***

“Repetition Problems” (1977, No. 9),
"Questions for Graduates" (1978, No. 7).

This school year we will be focusing more on the application of analysis to solving mathematical and practical problems. It is expected to show in more depth the applications of arbitrary, to fully illuminate the issues of determining the length of a circle and the area of ​​an artificial surface, and to analyze the method of constructing sections of polyhedra.

R. Meschoir

Combinatorial proofs of Newton's formula

The school year has begun. Ninth grade students will soon become familiar with concepts such as induction, combinatorics, and Newton's biome. The original proof of Newton’s formula was sent to the editor by last year’s ninth-grader, student of Moscow School No. 444, Roman Meschoir. We have added two more (more famous) combinatorial proofs to his paper.

In the textbook “Algebra and the beginnings of analysis 9”, paragraph 9 provides the derivation of Newton’s formula.

$$a + b)^n = a^n + C_n^1 a^{n-1} b + \ldots + C_n^k a^{n-k} b^k + \ldots + b^n,$$

based on the method of mathematical induction. Here we present a combinatorial proof of this formula (though only for natural a and b).

Consider the following problem: in how many ways can we color n

⟦folio 46⟧

yatsik, if there are a cancellations of red paint and b cancellations of blue.

On the one hand, there are $(a + b)^n$ such methods: the first box can be painted in any of $a + b$ shades, the second (regardless of the first!) - also in any of $a + b$ shades, which means that for the first two boxes there are $(a + b)(a + b) = (a + b)^2$ possible colorings, etc.

On the other hand, the number of colorings is equal to the right side of equality (1). Let's show this by calculating this number differently. First, let's find the number of colorings for which all $n$ boxes are red (there are very/no of them - $a^n$); then we will find the number of colorings for which exactly one box is blue (there are $nba^{n-1}$), or there are $n$ ways to choose the box that we will paint blue red, there are $b$ shades for it, and $a^{n-1}$ colorings for the remaining $n-1$ boxes); ...; Next, we will find the number of colorings for which all $n$ boxes are blue (there are $C_n^k b^k a^{n-k}$ of them, or there are $C_n^k$ ways to choose from $n$ boxes $k$ boxes that we will paint blue red *), for these $k$ boxes there are $b^k$ colorings, for the remaining $n-k$ boxes exist $a^{n-k}$ coloring pages); ...; finally, we find the number of colorings for which all $n$ boxes are blue (there are $b^n$ of them). Thus, the total number of colorings is equal to

$$a^n + nba^{n-1} + \dots + C_n^k b^k a^{n-k} + \dots + b^n,$$

and this sum coincides with the right side of formula (1), which is thereby proven.

If you understand this proof well, then you will be able to prove a generalization of Newton's formula to the case of $m$ (natural) terms:

$$(a_1 + a_2 + \dots + a_m)^n = a_1^n + \dots + N_{k_1 k_2 \dots k_m}^n a_{k_1}^k a_{k_2}^k \dots a_m^k m + \dots + a_m^n,$$

(*) “Algebra and principles of analysis 9”, paragraph 6.
