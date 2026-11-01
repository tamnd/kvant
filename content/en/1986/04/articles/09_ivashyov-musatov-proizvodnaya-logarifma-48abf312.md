---
id: 1986-4-ivashyov-musatov-proizvodnaya-logarifma-48abf312
issue: kvant_1986_4
year: 1986
number: "4"
title: Derivative of logarithm
authors:
  - Ивашёв-Мусатов О. С.
rubric: shkola-v-kvante
page_first: 27
page_last: 27
page_labels: "25"
tag: IF1X
lang: en
source: kvant_digital
extraction: vision
content_sha256: f585265129fd05c22712fe0bce23f00eeeb7af9a462e55fed34f361a09f78f78
prompt_sha256: draft-1
translated_from: content/ru/1986/04/articles/09_ivashyov-musatov-proizvodnaya-logarifma-48abf312.md
source_content_sha256: 51dda46a3886ffe83db080d598dbc62de9c184d7f7ef1b9d50dfcc1e786728f1
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 25⟧

Math 10
This note is intended for tenth graders. It outlines some useful facts about the number e.

Derivative of logarithm

In the textbook “Algebra and the beginnings of analysis 9-10” on p. 208 a formula is derived for an arbitrary logarithmic function. This formula is obtained there using the theorem on an arbitrary inverse function and the formula for an arbitrary exponential function. In this note we will obtain a formula for an arbitrary logarithmic non-presidential function - finding the corresponding limit.

No we will first define
Number e

Consider the curved graph of the function y = $\frac{1}{x}$, the segment [1; t] axis Ox and straight lines x=1, x=t (Fig. 1). The area of ​​this curved gradient is a function of t—we denote it by S(t). This function on the interval [1; ∞] returns and is continuous.

The proof of the continuity of the function S(t) is implicitly contained in paragraph 59 of the textbook “Algebra and the beginnings of analysis 9-10”: it shows that the function S(t) is differentiable; every differentiable function is continuous. Otherwise, the continuity of S(t) can be deduced directly from the definition of a continuous function. Try this.

Since S(2)<1 (Fig. 2), and S(4)>1 (Fig. 3; $\frac{1}{2} + \frac{1}{3} + \frac{1}{4} > 1$), then between the numbers 2 and 4 there is a single number - it is denoted by the letter e, such that S(e)=1.

Us. 200 of the textbook “Algebra and the beginnings of analysis 9-10” the number e is defined differently. It can be proven that these two definitions are equivalent.

Since e>0 and different from 1, logarithms to base e can be defined. These logarithms are called natural and are denoted by ln, that is, ln a=log_e a. Since e>1,

function y=ln x on the interval ]0; ∞[ returns.

Two important inequalities

Let us now prove that for any natural number n the following inequality holds:

$$\left(1 + \frac{1}{n}\right)^n < e < \left(1 + \frac{1}{n}\right)^{n+1}. \quad (1)$$

It follows from inequality (1) that

$$\lim_{n \to \infty} \left(1 + \frac{1}{n}\right)^n = e$$

(this is how the number e is determined in university courses in mathematical analysis).

Indeed, let us take any number ε>0 and set N=[$\frac{e}{\epsilon}$]. Then for any natural number n>N the following inequality holds:

$$n > \frac{e}{\epsilon} \quad \text{и}$$

$$\left| \left(1 + \frac{1}{n}\right)^n - e \right| = e - \left(1 + \frac{1}{n}\right)^n < \left(1 + \frac{1}{n}\right)^{n+1} - \left(1 + \frac{1}{n}\right)^n = \left(1 + \frac{1}{n}\right)^n \left(1 + \frac{1}{n} - 1\right) < \frac{e}{n} < \epsilon.$$

Let us fix any natural number n, set q=1+$\frac{1}{n}$ and dis-

Fig. 1.

Fig. 2.

Fig. 3.
