---
id: 1972-1-smyishlyaev-primenenie-neravenstva-bunyakovskogo-koshi-k-resheniyu-nekotoryih-zadach-4eddf0cd
issue: kvant_1972_1
year: 1972
number: "1"
title: Application of the Bunyakovsky–Cauchy inequality to the solution of some problems
authors:
  - Смышляев В. К.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 35
page_last: 37
page_labels: 33-35
tag: JGDA
lang: en
source: kvant_digital
extraction: vision
content_sha256: 351433bc667c57f65120757c091392fb1392965e29b7610bbd88cf552e3ebb2e
prompt_sha256: draft-1
translated_from: content/ru/1972/01/articles/10_smyishlyaev-primenenie-neravenstva-bunyakovskogo-koshi-k-resheniyu-nekotoryih-zadach-4eddf0cd.md
source_content_sha256: 9b976d943064d630a31970e004510ea330f1ab265b10352048963699184178c8
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 33⟧

When solving many mathematical problems, the so-called Bunyakovsky-Cauchy inequality is used

$$\sum_{i=1}^{n} a_i b_i \leq \sqrt{\sum_{i=1}^{n} a_i^2} \cdot \sqrt{\sum_{i=1}^{n} b_i^2} \quad (a_i > 0, b_i > 0).$$

Let us first give a small but very simple proof of this inequality. Let $$\sqrt{\sum_{i=1}^{n} a_i^2} = A, \quad \sqrt{\sum_{i=1}^{n} b_i^2} = B.$$ Then we need to prove that

$$\frac{\sum_{i=1}^{n} a_i b_i}{AB} \leq 1.$$

Using the inequality $xy \leq \frac{1}{2}(x^2+y^2)$, we write the following integer:

$$\frac{\sum_{i=1}^{n} a_i b_i}{AB} = \sum_{i=1}^{n} \left(\frac{a_i}{A} \cdot \frac{b_i}{B}\right) \leq$$

$$\leq \sum_{i=1}^{n} \frac{1}{2} \left[ \left(\frac{a_i}{A}\right)^2 + \left(\frac{b_i}{B}\right)^2 \right] = \frac{1}{2} \left( \frac{1}{A^2} \sum_{i=1}^{n} a_i^2 + \frac{1}{B^2} \sum_{i=1}^{n} b_i^2 \right) = 1.$$

This implies inequality (*). As is known, equality in it is achieved when

$$\frac{a_1}{A} = \frac{b_1}{B}, \quad \frac{a_2}{A} = \frac{b_2}{B}, \dots, \quad \frac{a_n}{A} = \frac{b_n}{B},$$

that is, when

$$\frac{a_1}{b_1} = \frac{a_2}{b_2} = \dots = \frac{a_n}{b_n}.$$

Let us now show how inequality (*) is applied.

⟦folio 34⟧

1. Find the most value of a function
$$y = a \sin x + b \cos x$$
$$\left(a > 0, b > 0, 0 < x < \frac{\pi}{2}\right).$$

Solution. Due to inequality (*) we have
$$y = a \sin x + b \cos x \leqslant \sqrt{a^2 + b^2} \cdot \sqrt{\sin^2 x + \cos^2 x} = \sqrt{a^2 + b^2}.$$
The maximum is achieved under the condition
$$\frac{a}{b} = \frac{\sin x}{\cos x},$$ that is, when
$$tg x = \frac{a}{b}.$$

2. A variable type transformer must be designed so that its cross-shaped iron core fills as much of the internal cavity of the round winding as possible. What should be the cross-sectional dimensions of the core shown at figure if the radius of the coil is $R$?
Solution. Let $\Rightarrow AOB = \alpha$, then
$$\frac{1}{4} S = y^2 - (y - x)^2 = 2xy - x^2 = R^2 \left(2 \sin \alpha \cos \alpha - \sin^2 \alpha\right).$$
Hence $S = 2R^2 \left(2 \sin 2\alpha + \cos 2\alpha - 1\right)$. Let's use inequality (*):
$$S \leqslant 2R^2 \left(\sqrt{2^2 + 1^2} \cdot \sqrt{\sin^2 2\alpha + \cos^2 2\alpha} - 1\right) = 2R^2 \left(\sqrt{5} - 1\right).$$
Therefore, $S_{\max} = 2R^2 \left(\sqrt{5} - 1\right)$ is achieved at
$$\frac{\sin 2\alpha}{\cos 2\alpha} = \frac{2}{1},$$ from where $\alpha = \frac{1}{2}$ arctg 2.

3. Consider three pairs of real numbers $(a_1, b_1), (a_2, b_2), (a_3, b_3)$. Prove that there is a triangle with side $a = \sqrt{(a_2 - a_3)^2 + (b_2 - b_3)^2}, \quad b = \sqrt{(a_3 - a_1)^2 + (b_3 - b_1)^2}, \quad c = \sqrt{(a_1 - a_2)^2 + (b_1 - b_2)^2}$.
Solution. In order for $a, b$ and $c$ to be sides of a triangle, it is necessary that the inequalities $a + b > c, b + c > a, a + c > b$ be satisfied, each of which is equivalent to the Bunyakovsky-Cauchy inequality. Indeed, the correspondence $a + b \geqslant c$ is equivalent to the inequality $2ab \geqslant c^2 - a^2 - b^2$ or $2 \sqrt{(a_2 - a_3)^2 + (b_2 - b_3)^2} \cdot \sqrt{(a_3 - a_1)^2 + (b_3 - b_1)^2} \geqslant (a_1 - a_2)^2 + (b_1 - b_2)^2 - (a_2 - a_3)^2 - (b_2 - b_3)^2 - (a_3 - a_1)^2 - (b_3 - b_1)^2 = 2 \left[ (a_3 - a_1) (a_2 - a_3) + (b_3 - b_1) (b_2 - b_3) \right]$, reducing by 2 we obtain inequality (*). Equality is achieved only if the numbers $a_3 - a_1, b_3 - b_1$ are proportional to the numbers $a_2 - a_3, b_2 - b_3$; check that in this case the vertices of the triangle must lie on the same straight line.
It can be proved in a similar way that $a + c \geqslant b, b + c \geqslant a$. This means that a triangle with sides $a, b, c$ exists, although it can degenerate into a segment. You can construct this triangle geometrically - in the Cartesian coordinate system, its vertices must be placed at points with coordinates $(a_1, b_1), (a_2, b_2), (a_3, b_3)$.

⟦folio 35⟧

Exercises

1. Find the most value of a function
   a) $y = a \sin x + b \sin \left( \frac{\pi}{3} + x \right) + c \sin \left( \frac{\pi}{3} - x \right) \left( a > 0, b > 0, c > 0, 0 < x < \frac{\pi}{3} \right)$;
   b) $z = a \sin (x + y) + b \sin (x - y) + c \sqrt{\cos 2x \cdot \cos 2y}$
      $(a > 0, b > 0, c > 0, 0 < x < \frac{\pi}{4}, 0 < y < \frac{\pi}{4})$;
   c) $u = a \cos x + b \cos y + c \cos z + d \sqrt{2 \cos x \cos y \cos z}$, where $a, b, c, d$ are positive numbers, $x, y, z$ are the remaining angles of the triangle;
   d) $u = a \sin x + b \sin y + c \sin z + d \sin t + e \sqrt{2 \cos (x + y) \cdot \cos (y + z) \cdot \cos (z + x)}$, where $a, b, c, d, e$ are positive numbers, $x + y + z + t = 2\pi$;
   e) $y = \frac{(a_1 x_1 + a_2 x_2 + \cdots + a_n x_n)^2}{x_1^2 + x_2^2 + \cdots + x_n^2}$ $(a_i > 0, x_i > 0)$.

2. Find the most and most values ​​of the function $u = \sum_{i=1}^{n} x_i y_i$, if it is known that $\sum_{i=1}^{n} x_i^2 \leq a^2$, $\sum_{i=1}^{n} y_i^2 \leq b^2$ and $a$ and $b$ are positive numbers.

3. Prove inequality
   $$\sum_{i=1}^{n} \sqrt{x_i y_i} \leq \sqrt{\sum_{i=1}^{n} x_i} \sqrt{\sum_{i=1}^{n} y_i},$$
   where all $x_i$ and $y_i$ are positive numbers.

4. Prove inequality
   $$\left( \sum_{i=1}^{n} \sqrt{a_i b_i} \right)^2 \leq \sum_{i=1}^{n} a_i x_i \sum_{i=1}^{n} \frac{b_i}{x_i},$$
   where all $a_i, b_i, x_i$ are positive numbers.

5. Prove inequality
   $$\sum_{i=1}^{n} x_i y_i \sum_{i=1}^{n} \frac{x_i}{y_i} \geq \left( \sum_{i=1}^{n} x_i \right)^2,$$
   where all $x_i, y_i$ are positive numbers.

6. A ball of radius $R$ has a cylinder with the most complete surface. What are its radius and height?
7. Inside a triangle, a certain point is located such that the sum of the squares of the distances from it to the side of the triangle is the smallest. Express these distances in terms of the lengths of the sides of the triangle and find this point.
8*) The areas of the triangle’s faces are $S_1, S_2, S_3$ and $S_4$. Point $M$ lies inside the triangle at distances $h_1, h_2, h_3$, and $h_4$ (respectively) from the faces.
   a) At what position of the point $M$ the sum
      $$\frac{S_1}{h_1} + \frac{S_2}{h_2} + \frac{S_3}{h_3} + \frac{S_4}{h_4}$$

takes the most meaning?
6) Prove that any triangle has at least one point $M$ for which the sum (*) is minimal. Find how many such points there can be.

*) This problem was sent by our reader G. Hovhannitsan from Yerevan.
