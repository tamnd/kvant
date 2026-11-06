---
id: 1990-10-zatakavay-nekotoryie-poleznyie-pokazatelnyie-i-logarifmicheskie-sootnosheniya-0777268f
issue: kvant_1990_10
year: 1990
number: "10"
title: Some Useful Exponential and Logarithmic Relationships
authors:
  - Затакавай В. В.
rubric: shkola-v-kvante
page_first: 44
page_last: 45
page_labels: 42-43
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5f8cac05de214ff08e7547b2ccaa93e5838aaca2485b47b04823bcd8258be78c
prompt_sha256: draft-1
translated_from: content/ru/1990/10/articles/14_zatakavay-nekotoryie-poleznyie-pokazatelnyie-i-logarifmicheskie-sootnosheniya-0777268f.md
source_content_sha256: 70fff0bf14e0b8a754f79cd2aea384b33b5b90411433e35bf3e078b624b10722
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 42⟧

---
running_head:
folio:
---

$x^{\log_2 5} = (5^{\log_5 x})^{\log_2 5} = (5^{\frac{\log_2 x}{\log_2 5}})^{\log_2 5} = 5^{\log_2 x}$, and the equation takes the form
$5^{\log_2 x} + 2 \cdot 5^{\log_2 x} = 15$.

From here
$5^{\log_2 x} = 5, \log_2 x = 1, x = 2$.

Answer: 2.

By solving this equation, we actually derived the formula
$a^{\log_2 b} = b^{\log_2 a}$. (1)

It is easy to verify the validity of formula (1) in general form. Let us triangulate the right and left sides of (1) to the base $c$. We get $\log_c (a^{\log_2 b}) = \log_c (b^{\log_2 a})$, or $\log_c b \times \log_c a = \log_c a \cdot \log_c b$.

Obviously, this also holds true for all admissible values ​​of $a, b, c$.

Here is another useful formula left behind the pages of a school textbook:
$a^{\sqrt{\log_a b}} = b^{\sqrt{\log_b a}}$. (2)

The proof of this formula is similar to the proof of the previous one: you need to polygonize both sides of formula (2) to the base $a$:
$\log_a (a^{\sqrt{\log_a b}}) = \log_a (b^{\sqrt{\log_b a}})$,

or
$\sqrt{\log_a b} = \sqrt{\log_b a} \cdot \log_a b$.

Moving to the base $a$, we get $\sqrt{\log_a b} = \sqrt{\log_b a}$.

Example 2.
$2^{\sqrt{\log_2 x}} + x^{\sqrt{\log_2 x}} = 4$.

According to formula (2)
$x^{\sqrt{\log_2 x}} = 2^{\sqrt{\log_2 x}}$, so the equation becomes
$2^{\sqrt{\log_2 x}} + 2^{\sqrt{\log_2 x}} = 4; 2^{\sqrt{\log_2 x}} = 2;$
$\log_2 x = 1; x = 2$.

Answer: 2.

Example 3.
$\log_3 x (42x^2 - 13x + 1) > 0$.

Solving this inequality from a “school point of view” is labor-intensive. It is necessary to consider two cases

⟦folio 43⟧

---
running_head:
folio:
---

tea: when $3x > 1$ and when $0 < 3x < 1$.
Both cases lead to cumbersome systems of inequalities.
We claim that if $\log_a b > 0$, then $(a-1) \cdot (b-1) > 0$, i.e. $(a-1)$ and $(b-1)$ are of the same sign.
Indeed, if $\log_a b > 0$, then $\log_a b > \log_a 1$.
For $a > 1$ we have $b > 1$, the statement is true.
For $0 < a < 1$ we obtain that $b < 1$, otherwise the statement is again true, since $(a-1) < 0$ and $(b-1) < 0$.
Similarly, you can prove that if $\log_a b < 0$ then $(a-1) \cdot (b-1) < 0$ (do it yourself).
Let's apply our statement to example 3. So, we have:
$$(42x^2 - 13x)(3x - 1) > 0.$$
This inequality is easily solved using the method of integrals. In this case, of course, it is necessary to consider the correspondences that limit the domain of definition of the logarithmic function:
$3x > 0; \quad 3x \neq 1; \quad 42x^2 - 13x + 1 > 0.$
Answer: $\left(0; \frac{1}{7}\right) \cup \left(\frac{1}{6}; \frac{13}{42}\right) \cup \left(\frac{1}{3}; +\infty\right)$.
The considered technique allows us to solve more complex inequalities. Example 4.
$\log_{2-x}(x+2) \cdot \log_{x+3}(3-x) \leq 0.$
Applying the proven statement, we get
$(x+1)(1-x)(2-x)(x+2) \leq 0.$
Taking into account the domain of definition of the left side of the inequality: $(-2; 1) \cup (1; 2)$, we obtain
Answer: $(-2; -1] \cup (1; 2)$.
In conclusion, we offer several examples for independent solutions.
1. $5^{\lg x} + x^{\lg 5} = 50.$
2. $25^{\lg x} = 5 + 4 \cdot x^{\lg 5}$.
3. $x^{\log_2 9} = x^2 \cdot 3^{\log_2 x} - x^{\log_2 3}$.
4. $10^{\sqrt{\lg x}} + x^{\sqrt{\log_2 x}} = 0,2.$
5. $3^{-\sqrt{\log_1 x}} + x^{\sqrt{\log_1 x}} = 4,5^{-1}$.
6. $\log_2 x^2(x^2 + x - 1) < 0.$
7. $\log_2 x(5x - 1) \cdot \log_3 x(7x - 1) > 0.$
8. $\log_2 x(10x + 3) \cdot \log_10 x(3x + 10) \geq 0.$
9. $\log_2 x\left(6x + \frac{1}{7}\right) \cdot \log_5 x\left(3x + \frac{4}{7}\right) \leq 0.$

Competition "Mathematics 6-8"
The magazine «Kvant» together with the Bulgarian youth magazine “Mathematika” continues a competition to solve mathematical problems for students in grades 6-8. The competition consists of 27 problems (no 3 in each issue) and will end in May next year. The winners will be awarded prizes from the journals «Kvant» and Mathematika. Unfortunately, in the conditions of the problem from the previous issue (see p. 48), existing inaccuracies were made. The editors bring their findings to readers and repeat the terms of these tasks. Send solutions to all problems in this issue no later than December 15, 1990 to the address: 103006, Moscow K-6, st. Gorky, 32/1, «Kvant» (marked “Competition “Mathematics 6-8”}). Don't forget to include your last name, first name, school and class.
