---
id: 1977-3-rozov-otvet-na-vopros-chitatelya-s-kirzhalova-o-reshenii-irratsionalnogo-uravneniya-305cc53b
issue: kvant_1977_3
year: 1977
number: "3"
title: '[Answer to a question from reader S. Kirzhalov about solving an irrational equation]'
authors:
  - Розов Н. Х.
rubric: raznoe
page_first: 58
page_last: 59
page_labels: 56-57
tag: H0M1
lang: en
source: kvant_digital
extraction: vision
content_sha256: 33a259d26c91a7dd7097b49f106a04f64d7cb9a3fa8f1757fd6008eb850c5052
prompt_sha256: draft-1
translated_from: content/ru/1977/03/articles/19_rozov-otvet-na-vopros-chitatelya-s-kirzhalova-o-reshenii-irratsionalnogo-uravneniya-305cc53b.md
source_content_sha256: de5302fa57fda7c02ca1f98b1d30e661f3138133afbf629ddfccd55a041ac217
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 56⟧

Ask - we answer

The editor received a letter from the city of Kharkov from Stepan Kirzhalov, a 9th grade student. This is what he writes.

“In the “Handbook of Elementary Mathematics” (Kyiv, 1973) I came across any way to solve an irrational equation
$$\sqrt[3]{8x+4} - \sqrt[3]{8x-4} = 2.$$ (*)

Whenever we take the parts of this equation into a cube, we get $(8x+4)$ -
$$-3\sqrt[3]{8x+4}\sqrt[3]{8x-4} \times (\sqrt[3]{8x+4} - \sqrt[3]{8x-4}) - (8x-4) = 8.$$

Considering that by condition the expression in square brackets must be equal to 2, we can write
$$-6\sqrt[3]{64x^2-16} = 0,$$
whence $x_1=1/2$, $x_2=-1/2$. I also tried to solve other equations
$$\sqrt[3]{2x-1} + \sqrt[3]{x-1} = 1,$$ (**)

but it turned out that of the two resulting values ​​$x_1=1$, $x_2=0$ only the first one satisfies the equation. What's the matter?

Since the response to Stepan Kirzhalov’s letter may be of interest to many other readers «Kvant», we are publishing this response on the pages of the magazine.

First of all, we remind readers that in mathematical literature the notation $\sqrt[3]{a}$ is used in two senses (see “Algebra 8”, M., “Prosveshchenie”, 1975, p. 95).

First, the symbol $\sqrt[3]{a}$ denotes a non-negative number whose cube is $a$; then this symbol defines for any $a$. In the book mentioned in S. Kirzhalov’s letter by G. P. Bevz, P. F. Filchakov, K. I. Shvetsov, F. P. Yaremchuk “Handbook on elementary mathematics for building a university” (Kyiv, “Naukova Dumka”, 1973, pp. 152-153) the sign $\sqrt[3]{a}$ is used in this sense, so that, for example, the expression $\sqrt[3]{8x-4}$ at $x=-1/2$ exists and is equal to -2.

The method of solving iration equations with radicals of the third degree, which the author of the letter writes about, is used quite often. It is also mentioned in the aforementioned “Reference Book”, however, unfortunately, it is not indicated there that when solving an equation in the maxim way, we can acquire extraneous roots, and therefore we always need to check.

It is not difficult to verify this. We are now carrying out the corresponding reasoning, especially since they are very respectable and show how the question of the equivalence of equations is specifically investigated and the reasons for its violation are clarified. Let us first present one algebraic approach:

$$a^3+b^3+c^3-3abc = \frac{1}{2}(a+b+c)[(a-b)^2+(b-c)^2+(c-a)^2];$$

To prove it, it is enough to open the brackets on the right side.

Consider the equation

$$\sqrt[3]{f(x)} + \sqrt[3]{g(x)} = \varphi(x)$$

and let's assume that $x_0$ is its root, so

⟦folio 57⟧

$$\sqrt[3]{f(x_0)} + \sqrt[3]{g(x_0)} - \varphi(x_0).$$

Raising both sides of the correct numerical equality (3) into a cube and continuing transformations, we obtain:

$$f(x_0) + 3\sqrt[3]{f(x_0)} \sqrt[3]{g(x_0)} \left[ \sqrt[3]{f(x_0)} + \sqrt[3]{g(x_0)} \right] + g(x_0) = \varphi^3(x_0).$$

If we again use the correct numerical equality (3), we obtain the equality

$$f(x_0) + 3\sqrt[3]{f(x_0)} \sqrt[3]{g(x_0)} \varphi(x_0) + g(x_0) = \varphi^3(x_0),$$

which shows that $x_0$ is the root of the equation

$$f(x) + 3\sqrt[3]{f(x)} \sqrt[3]{g(x)} \varphi(x) + g(x) = \varphi^3(x).$$

Thus, every root of equation (2) is a root of equation (5).

Let us now consider equation (5) and assume that $x_0$ is its root, so that numerical equality (4) holds. Applying identity (1) with

$$a = \sqrt[3]{f(x_0)}, b = \sqrt[3]{g(x_0)}, c = -\varphi(x_0),$$

we rewrite equality (4) in the form

$$\frac{1}{2} \left( \sqrt[3]{f(x_0)} + \sqrt[3]{g(x_0)} - \varphi(x_0) \right) \times \left| \left( \sqrt[3]{f(x_0)} - \sqrt[3]{g(x_0)} \right)^2 + \left( \sqrt[3]{f(x_0)} + \varphi(x_0) \right)^2 + \left( \sqrt[3]{g(x_0)} + \varphi(x_0) \right)^2 \right| = 0.$$

From equality (6) it is clear that the number $x_0$ either satisfies equality (3), that is, is the root of equation (2), or satisfies the equality

$$\sqrt[3]{f(x_0)} = \sqrt[3]{g(x_0)} = -\varphi(x_0),$$

that is, it is a solution to the system of equations

$$\begin{cases} f(x) = -\varphi^3(x), \\ g(x) = -\varphi^3(x). \end{cases}$$

Thus, equation (5) may have roots that are not roots of equation (2). It is easy to verify that the root $x_0$ of equation (5) is constructed for equation (2) if and only if the conditions

$$\begin{cases} \varphi(x_0) \neq 0, \\ f(x_0) = g(x_0) = -\varphi^3(x_0). \end{cases}$$

The value $x = 0$ found by the author of the letter satisfies these conditions and therefore will be a constructed root for equation (**).

In conclusion, we note once again that from the point of view of the new school curriculum, the value $x = -1/2$ is not the root of the equation (*), since in this case the value of the left side of the equation (*) is not defined.

H. Rozov
