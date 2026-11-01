---
id: 1987-4-koprinski-formulyi-vieta-a502e653
issue: kvant_1987_4
year: 1987
number: "4"
title: Vieta formulas
authors:
  - Копрински С. Ц.
rubric: shkola-v-kvante
page_first: 43
page_last: 43
tag: "2753"
lang: en
source: kvant_digital
extraction: vision
content_sha256: aa7ac6c2bca4978101a79080932ff443f42f354950abc17e6ddbcc48c7f15218
prompt_sha256: draft-1
translated_from: content/ru/1987/04/articles/16_koprinski-formulyi-vieta-a502e653.md
source_content_sha256: 562a2714e4187c3fcb23c90f2648f9d688ed5a171760be9acd4e4b7ef4394971
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio none⟧

Since the AFC segment lies inside the rectangle, we get the integer inequalities:
$$0 < S_{AFC} < S_{ABCD},$$
$$0 < \frac{1}{2} x - \frac{1}{2} \sin x < \frac{x^3}{2},$$
$$0 < 1 - \frac{\sin x}{x} < x^2$$
(in the interval 0 < x < $\frac{\pi}{2}$).

Let us now note that the function $\frac{\sin x}{x}$ is even, therefore inequality (*) is also valid in the interval $-\frac{\pi}{2} < x < 0$, i.e. it is valid for all $x$ satisfying the condition $0 < |x| < \frac{\pi}{2}$.

Since $x^2 \rightarrow 0$ for $x \rightarrow 0$, then for any $\varepsilon > 0$ one can specify a neighborhood such that for all $x$ from this neighborhood, $x \neq 0$ will satisfy the inequality $x^2 < \varepsilon$. Taking into account (*), we obtain that for all $x$ from this neighborhood, $x \neq 0$, we have
$$1 - \frac{\sin x}{x} = \left| 1 - \frac{\sin x}{x} \right| < \varepsilon.$$

This means that $\lim_{x \rightarrow 0} \frac{\sin x}{x} = 1$ – our theorem is proven.

G. A. Sorokin

Vieta formulas

In the school algebra course (see “Algebra 7”, paragraph 23), Vieta’s theorem is proven for the given quadratic equations. However, a similar theorem is valid for cubic equations, and for equations of four degrees, and in general for arbitrary algebraic equations of degree $n$, and the leading coefficient (at $x^n$) is not necessarily equal to one.

For $n=1$ we obtain the linear equation $ax+b=0$ and if $x_1$ is its root, then $ax_1+b=0$, whence
$$x_1 = -\frac{b}{a}.$$

Let there be a quadratic equation $ax^2+bx+c=0$ ($a \neq 0$), and let $x_1$ be its root. Then
$$ax_1^2+bx_1+c=0.$$

Subtracting the identity $ax_1^2+bx_1+c=0$ from the equation $ax^2+bx+c=0$, we obtain
$$a(x-x_1)^2+b(x-x_1)=0,$$
where
$$(x-x_1)(ax+ax_1+b)=0.$$

Since $x_1$ is the root of the equation $x-x_1=0$, then the second root of the quadratic equation $x_2$ satisfies the equation
$$ax_2+ax_1+b=0.$$

Means,
$$x_1+x_2 = -\frac{b}{a}.$$

This is Vieta's first formula for a quadratic equation. Next,
$$x_1^2 + \frac{b}{a}x_1 + \frac{c}{a} = 0,$$
or
$$x_1^2 - (x_1+x_2)x_1 + \frac{c}{a} = 0,$$
where we get the second Vieta formula
$$x_1x_2 = \frac{c}{a}.$$

Note that when deriving both Vieta formulas, we did not come across any formulas for the roots of the quadratic equation. (By the way, they can be easily found from Vieta’s formulas.)

Using Vieta's formulas, we can prove a useful theorem: if $x_1$ and $x_2$ are the roots of the quadratic trinomial $f(x)=ax^2+bx+c$, then $f(x) = a(x-x_1)(x-x_2)$. In fact,
$$f(x) = ax^2+bx+c = a(x^2 - \left(-\frac{b}{a}\right)x + +\frac{c}{a}) = a(x^2 - (x_1+x_2)x + x_1x_2) = a((x^2-x_1x) - (x_2x-x_1x_2)) = a(x-x_1)(x-x_2).$$

For the roots of a cubic equation, Vieta's formulas are derived in exactly the same way, but in order for readers to better understand the technical techniques, we will go through the entire sequence of steps again.

For the general case of an algebraic equation of degree $n$, readers familiar with the method of complete mathematical induction will be able to derive Vieta's formulas on their own. Here we will only write out these formulas.

Let this equation
$$a_0x^n + a_1x^{n-1} + a_2x^{n-2} + \dots + a_nx^n = 0.$$
