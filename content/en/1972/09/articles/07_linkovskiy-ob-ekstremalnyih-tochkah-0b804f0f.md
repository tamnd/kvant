---
id: 1972-9-linkovskiy-ob-ekstremalnyih-tochkah-0b804f0f
issue: kvant_1972_9
year: 1972
number: "9"
title: About extreme points
authors:
  - Линковский Ж. Б.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 37
page_last: 37
page_labels: "35"
tag: Y98L
lang: en
source: kvant_digital
extraction: vision
content_sha256: 55a4beb281e818cb8057bade4285205613fe51f316dd423c46ac3ae475a2f129
prompt_sha256: draft-1
translated_from: content/ru/1972/09/articles/07_linkovskiy-ob-ekstremalnyih-tochkah-0b804f0f.md
source_content_sha256: 253d1dc7683051616e20e805c5ab97cc75f6e29c5ad734a68ceaea128eca3d7d
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 35⟧

About extreme lobes
Zh.B.Pinkovsky

An extreme point is a point at which some function reaches its greatest or greatest value. It is easy to prove that the point of intersection of the medians of a triangle has the following property: for it the sum of the squares of the distances to the vertices of the triangle is minimal. In this article we will present a completely elementary proof of a generalization of this fact.

Let there be $n$ points on the data plane. Let us introduce on the plane a Cartesian coordinate system with axes $Ox$, $Oy$ and denote these points as follows: $A_1(x_1, y_1)$, $A_2(x_2, y_2)$, ..., $A_n(x_n, y_n)$ (Fig. 1). Let's take any point $M(x, y)$ on the plane. The square of the distance from point $M$ to point $A_i$ is easy to find using the Pythagorean theorem (Fig. 2): $d_i^2 = (x - x_i)^2 + (y - y_i)^2$. The sum of squared distances from $M$ to points $A_1$, $A_2$, ..., $A_n$ looks like this:

$$D = d_1^2 + d_2^2 + \dots + d_n^2 = (x - x_1)^2 + (y - y_1)^2 + (x - x_2)^2 + (y - y_2)^2 + \dots + (x - x_n)^2 + (y - y_n)^2.$$

Let's open the brackets and represent $D$ as the sum of polynomials from $x$ and $y$:

$$D = nx^2 - 2x(x_1 + x_2 + \dots + x_n) + (x_1^2 + x_2^2 + \dots + x_n^2) + ny^2 - 2y(y_1 + y_2 + \dots + y_n) + (y_1^2 + y_2^2 + \dots + y_n^2).$$

The result was the sum of two polynomials, one depending only on $x$:

$$P(x) = nx^2 - 2x(x_1 + x_2 + \dots + x_n) + (x_1^2 + x_2^2 + \dots + x_n^2),$$

the second depends only on $y$:

$$Q(y) = ny^2 - 2y(y_1 + y_2 + \dots + y_n) + (y_1^2 + y_2^2 + \dots + y_n^2)$$

and $D = P(x) + Q(y)$. We note that $x$ and $y$ are independent, therefore $D$ reaches its maximum value for such $x$, for which $P(x)$ is the smallest, and for such $y$, for which $Q(y)$ is the smallest. But $P(x)$ and $Q(y)$ are second-order polynomials (with somewhat long coefficients). The graph of the function $P(x)$ will be a parabola (Fig. 3), the branches of which are directed upward ($n > 0$), the smallest value $u = P(x)$ is achieved at $x$, equal to the abscissa of the vertex of the parabola. From here it is easy to find the value of $x$ at which $P(x)$ is minimal: $x = \frac{x_1 + x_2 + \dots + x_n}{n}$.

The coordinate $y$ (from $Q(y)$) is found similarly: $y = \frac{y_1 + y_2 + \dots + y_n}{n}$.

We present the reader to solve the following problems.

1. Prove that the coordinates of the point of intersection of the medians of the triangle with the vertices $A_1(x_1, y_1), A_2(x_2, y_2), A_3(x_3, y_3)$ are as follows:

$$x = \frac{x_1 + x_2 + x_3}{3}, \quad y = \frac{y_1 + y_2 + y_3}{3}.$$

2. A Torricelli point is a point in a triangle whose sum of distances to the vertex of the triangle is minimal. Prove that from the Torricelli point the sides of the triangle are visible at angles $120^\circ$.
