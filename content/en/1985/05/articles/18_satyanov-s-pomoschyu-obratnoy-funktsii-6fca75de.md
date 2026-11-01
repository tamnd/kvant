---
id: 1985-5-satyanov-s-pomoschyu-obratnoy-funktsii-6fca75de
issue: kvant_1985_5
year: 1985
number: "5"
title: Using the inverse function
authors:
  - Сатьянов П. Г.
rubric: shkola-v-kvante
page_first: 36
page_last: 38
page_labels: 34-36
tag: VBS0
lang: en
source: kvant_digital
extraction: vision
content_sha256: 20a8b89747fa934009d1c1058d7a94f2e0a01a978f0d5376d25c1fd6e1298bcc
prompt_sha256: draft-1
translated_from: content/ru/1985/05/articles/18_satyanov-s-pomoschyu-obratnoy-funktsii-6fca75de.md
source_content_sha256: e6ee95742c568a747d9781af4ba53003806ccbfdd572ead446dbed2783f61c10
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

Math 10

Using the inverse function

At school, integrals are calculated using the Newton-Leibniz formula. How to calculate the integral in this way

$$I_1 = \int_0^1 \arcsin x \, dx,$$

you need to know the antiderivative for the function $\arcsin x$, but you don’t know it. How is life?

Let us turn to the geometric meaning of the integral: the integral is the area. Specifically, $I_1$ is the area of ​​the region surrounded by figure 1 in blue. Let us find this area as the difference between the area of ​​the corresponding rectangle and the area $\sigma_1$ of the “yellow area”. Since the graph of the function $\arcsin x$ is an “inverted” (obtained by symmetry around the line $y=x$) graph of the function $\sin x$, the area $\sigma_1$ is equal to the area under the sinusoid $x=\sin y$ in the region of change $y$ from 0 to $\frac{\pi}{2}$:

$$\sigma_1 = \int_0^{\frac{\pi}{2}} \sin y \, dy = -\cos y \Big|_0^{\frac{\pi}{2}} = 1.$$

Therefore, $I_1 = \frac{\pi}{2} - 1$.

Let us now calculate the integral

$$I_2 = \int_a^b \ln x \, dx \quad (1<a<b).$$

Let's look again at figure (Fig. 2). This time the "blue area" $I_2$ is equal to the area of ​​the "large rectangle" minus the area of ​​the "small rectangle" and the area $\sigma_2$ of the "yellow area". The graph of function $\ln x$ is an “inverted” graph of the inverse function $e^x$, therefore $\sigma_2$ is the area under the graph of function $x=e^y$ in the area of ​​change $y$ from $\ln a$ to $\ln b$:

$$\sigma_2 = \int_a^b e^y \, dy = e^y \Big|_a^b = b-a.$$

⟦folio 35⟧

Therefore, $I_2 = b \cdot \ln b - a \times \ln a - (b - a) = b \cdot \ln \frac{b}{e} - a \cdot \ln \frac{a}{e}$.

We have twice expressed the interraal of some function (arcsin $x$, ln $x$) in terms of the interraal of the inverse function ($\sin x, e^x$).

$$\ln x \text{ и } e^x - \text{ взимно-образные функции. Но arcsin } x \text{ и sin } x - \text{ не взимно-образные функции (sin } x - \text{ не обратная функция); взимно-образными являются arcsin } x \text{ и sin } x, \text{ рассматриваемый на отрезке } \left[ -\frac{\pi}{2}; \frac{\pi}{2} \right], \text{ или, как говоря математики, } cy\text{ значение функции sin } x \text{ на отрезок } \left[ -\frac{\pi}{2}; \frac{\pi}{2} \right].$$

Can't this be done in the general case? If, for example, the graph of the function $f$ has the same form as on figure 3, and the function $g$ is the inverse of $f$ on $[a; b]$, then from figure 3

$$\int_a^b f(x)dx = b \cdot f(b) - a \cdot f(a) - \int_a^b g(y)dy. \quad (1)$$

No, if the graph of the function $f$ has the same form as in Figures 4, a or 4, 6, then equality (1) cannot be obtained from figure. Is it still true? If true, how to prove it?

It is not clear how to prove equality (1) for an interval. Let's try to prove the corresponding statement for the first difference. Note in (1) $b$ to $x$:

$$\int_a^b f(t)dt =$$

$$= x \cdot f(x) - a \cdot f(a) - \int_a^b g(y)dy \quad (2)$$

(for simplicity, we also replaced the internalization variable $x$ with $t$; the internal values ​​are very independent of the designation of the internalization variable:

$$\int_a^b f(x)dx = \int_a^b f(t)dt = \int_a^b f(z)dz = \dots).$$

As is known, the function $\int_a^b f(t)dt$ is an antiderivative of the continuous function $f$ (“Algebra and Principles of Analysis 9-10”, Problem 1046). Therefore, if equality (2) is true, then the function

$$x \cdot f(x) - a \cdot f(a) - \int_a^b g(y)dy,$$

or, what is the same, differs from it by a function constant

$$\Phi(x) = x \cdot f(x) - \int_a^b g(y)dy, \quad (3)$$

will also be an antiderivative of $f$.

To check whether this is true, we need to differentiate the right-hand side of equality (3). We therefore require that the function $f$ be differentiable.

The function $\int_a^b g(y)dy$, included in the right-hand side of equality (3), is a composition of the function $z = f(x)$ and the function $\int_a^b g(y)dy$. Since

$$\left( \int_a^b g(y)dy \right)' = g(z), \quad (4)$$

according to the rules of composition differentiation

$$\left( \int_a^b g(y)dy \right)' = g(f(x)) \cdot f'(x).$$

Since the function $g$ is the inverse of $f$, $g(f(x)) = x$. Hence,

$$\left( \int_a^b g(y)dy \right)' = x \cdot f'(x).$$

Posetom

⟦folio 36⟧

Taking into account Theorem 1, using the Newton-Leibniz formula we obtain

$$\int_{a}^{b} f(x)dx = \Phi(x) \Big|_{a}^{b} =$$

$$= [x \cdot f(x) - \int_{a}^{x} g(y)dy] \Big|_{a}^{b} =$$

$$= b \cdot f(b) - \int_{a}^{b} g(y)dy -$$

$$- a \cdot f(a) + \int_{a}^{b} g(y)dy =$$

$$= b \cdot f(b) - a \cdot f(a) - \int_{a}^{b} g(y)dy,$$

Q.E.D.

For example, the function $y = \frac{1}{1+\sqrt{x}}$ is differentiable and invertible by ]0; +∞[ (Fig. 5). It is easy to calculate that its inverse will be the function $x = \left(\frac{1}{y} - 1\right)^2 (0 < y \leq 1)$. That's why

$$\int_{0}^{1} \frac{dx}{1+\sqrt{x}} = \frac{1}{2} - \int_{1}^{1/2} \left(\frac{1}{y} - 1\right)^2 dy =$$

$$= \frac{1}{2} + \int_{1/2}^{1} \left(\frac{1}{y} - 1\right)^2 dy =$$

$$= \frac{1}{2} + \int_{1/2}^{1} \left(\frac{1}{y^2} - \frac{2}{y} + 1\right)dy =$$

$$= \frac{1}{2} + \left(-\frac{1}{y} - 2 \ln y + y\right) \Big|_{1/2}^{1} = 2 \ln \frac{e}{2}.$$

The primary purpose of this article is to show how useful it can be to make a drawing and integrate similar geometric concepts (try to “open” formula (1) without a drawing!). To paraphrase the famous words of Caesar, this idea can be expressed as follows: “Drew, saw, proved!”

Exercises.
2. Find the antiderivative on [1; +∞[ for function $a) y = \sqrt{x^2 - 1} + x, 6) y = \sqrt{x^2 - 1}$.
3. Calculate a) $\int_{-1}^{0} \arcsin \sqrt{x} dx,$ b) $\int_{0}^{1} \sqrt{\frac{x}{x+1}} dx$.

P. G. SATYANOV
