---
id: 1990-9-shulikovskaya-neravenstvo-koshi-i-obemyi-8bc85430
issue: kvant_1990_9
year: 1990
number: "9"
title: Cauchy's inequality and volumes
authors:
  - Шуликовская В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 67
page_last: 68
page_labels: 65-66
lang: en
source: kvant_digital
extraction: vision
content_sha256: bfd91d6fe3866c533b54d7d5059bf5d9fb522a0cef3f9010c86947cea5584f18
prompt_sha256: draft-1
translated_from: content/ru/1990/09/articles/21_shulikovskaya-neravenstvo-koshi-i-obemyi-8bc85430.md
source_content_sha256: 6e71452fb6d0639b4b2feb45aa5017ee40e7790243b95bc312e7ad861929cbc5
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 65⟧

Cauchy inequality and volumes

V. SHULIKOVSKAYA

The article “Numerical Averages and Geometry,” published in this issue of the journal, provides several geometric proofs of the inequality $\frac{a+b}{2} \geq \sqrt{ab}(a>0, b>0)$.

The author of this note, an 11th grade student, provides another proof of this inequality, and then generalizes it to the case of space.

Let $a$ and $b$ be positive numbers, and (for definition) $a \geq b$.

Consider a rectangle with sides $a$ and $b$ (Fig. 1). Let us carry out the bissertis of the angle $A$. It is clear that the sum of the areas of equilateral right triangles $ABL$ and $AKD$ is not less than the area of ​​the rectangle $ABCD$. That's why

$$\frac{a^2+b^2}{2} \geq ab.$$

Let us rewrite the inequality by putting $a^2=x$, $b^2=y$. As a result we get

$$\frac{x+y}{2} \geq \sqrt{xy}.$$

Similar reasoning can be proven in three-dimensional space and prove the inequality

$$\frac{a^3+b^3+c^3}{3} \geq abc (0 < a \leq b \leq c),$$

from which, by replacing $a^3=x$, $b^3=y$, $c^3=z$, we obtain the substitution inequality

$$\frac{x+y+z}{3} \geq \sqrt[3]{xyz},$$

meaning that the arithmetic mean of three non-negative numbers is not less than their geometric mean. To prove (1), consider a rectangular parallelepid $ABCDA'B'C'D'$ with edges $BB'=a$, $AB=b$, $BC=c$ (Fig. 2). Let us draw the bissertis of the plane angles of the triangular angle of the parallelepid with the vertex $B$ and construct the quadrangular paramides $BRCQS$, $BAPTK$ and $BB'VZU$.

⟦folio 66⟧

---
running_head:
folio:
---

These primades cover these parallelepids and (if there are different ones among the numbers $a, b, c$) even “crawl out” beyond the boundaries of the parallelepid, so that the sum of the volumes of these paramides, i.e. $\frac{a^3}{3} + \frac{b^3}{3} + \frac{c^3}{3}$, is not less than the volume of the parallelepid. So, $\frac{a^3 + b^3 + c^3}{3} \geq abc$.

General Cauchy inequality
$$\frac{x_1 + x_2 + \ldots + x_n}{n} \geq \sqrt[n]{x_1 x_2 \ldots x_n},$$

where $x_i \geq 0$, can be proved using a similar construction in $n$-dimensional space.

We recommend that the reader familiar with the concept of $n$-dimensional space carry out the appropriate reasoning. To do this, we should consider a rectangular parallelepid with edges $a_1 \leq a_2 \leq \ldots \leq a_n$ and construct $n$-dimensional paramidas with volumes
$$\frac{a_1^n}{n}, \frac{a_2^n}{n}, \ldots, \frac{a_n^n}{n},$$
covering the parallelepid. As a result, we arrive at the inequality
$$\frac{a_1^n + \ldots + a_n^n}{n} \geq a_1 a_2 \ldots a_n,$$
from which inequality (2) can easily be obtained.
