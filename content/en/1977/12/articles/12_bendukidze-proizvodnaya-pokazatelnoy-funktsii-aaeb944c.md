---
id: 1977-12-bendukidze-proizvodnaya-pokazatelnoy-funktsii-aaeb944c
issue: kvant_1977_12
year: 1977
number: "12"
title: Derivative of an exponential function
authors:
  - Бендукидзе А. Д.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 42
page_last: 44
page_labels: 40, 42
tag: GJO6
lang: en
source: kvant_digital
extraction: vision
content_sha256: c50c5a1e2925a6f062ce60d7ae8b07c1e8fd6872d8901ca8c48388ba63e34b9a
prompt_sha256: draft-1
translated_from: content/ru/1977/12/articles/12_bendukidze-proizvodnaya-pokazatelnoy-funktsii-aaeb944c.md
source_content_sha256: 439cc2392ec4e572bf16b8f6d6917efd686bc257371de1bb71112fd8d76ec073
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

A. Bendukidze

Derivative exponent of a function

“The graph of the function $\exp_{10}$ looks like a “smooth” curve. In the chapter, it appears that this graph at each point has a tangent, the slope of which is positive. Therefore, it is naturally assumed that the function $\exp_{10}$ has a positive product for any value of the argument. This hypothesis is correct, as is proven in more complete courses of analysis. We will accept without proof that the function $\exp_{10}$ has a positive product at point 0. In other words, let us assume that there is a limit

$$\lim_{\Delta x \to 0} \frac{10^0 + \Delta x - 10^0}{\Delta x} = \lim_{\Delta x \to 0} \frac{10^{\Delta x} - 1}{\Delta x} \cdot (1)$$

Everything further will follow from here relatively simply.

This is how paragraph 109 begins - “Derivative indicator of a function. Number $e$》textbook for 10th grade - “Algebra and the beginnings of analysis.” Further in this paragraph, the choice of a formula for the derivative of the function $\exp_{10}$ is given, as well as a more general formula for the derivative of the function $\exp_a$, where $a > 0, a \neq 1$.

All this, in fact, follows from the existence of limit (1) very simply.

But a curious student, and such are, of course, readers «Kvant», may have a question: “Still, how is the existence and positive of limit (1) proven?” Proof of this fact, as stated in the manual, can be found in the complete analysis courses. There a more general fact is proved, namely: for any positive $a \neq 1$ there is a limit

$$\lim_{h \to 0} \frac{a^h - 1}{h},$$

and it is positive if $a > 1$, and negative if $0 < a < 1$. But the fact is that the proof of this, as a rule, relies on a number of preliminary lemmas and theorems, which are not always easy to understand. It would be advisable to give an indefinite proof. Such proof is given below.

1. Let $a$ be an arbitrary number greater than ones. Consider the sequence $(x_n)$, the general term of which is given by the formula

$$x_n = n \left( \frac{1}{a^n} - 1 \right).$$

Let us show that $(x_n)$ is an addition sequence and its limit is positive.

Let's start with the question of convergence and check the conditions of Weierstrass's theorem. For any natural $n$

$$a^{-\frac{1}{n(n+1)}} - 1 > -1,$$

posnomu according to Bernoulli's inequality

$$a^{-\frac{1}{n}} = \left( 1 + \left( a^{-\frac{1}{n(n+1)}} - 1 \right) \right)^{n+1} > 1 + (n+1) \left( a^{-\frac{1}{n(n+1)}} - 1 \right).$$

Multiplying this inequality by $a^{\frac{1}{n}}$, we get

$$1 > a^{\frac{1}{n}} + (n+1) \left( a^{\frac{1}{n+1}} - a^{\frac{1}{n}} \right)$$

or, what is the same,

$$n a^{\frac{1}{n}} + 1 > (n+1) a^{\frac{1}{n+1}}.$$

It is very easy to give this inequality the following form:

$$n \left( a^{\frac{1}{n}} - 1 \right) > (n+1) \left( a^{\frac{1}{n+1}} - 1 \right).$$

⟦folio 42⟧

Therefore we have
$$\begin{cases}
n \left( \frac{1}{n+1} - 1 \right) < \frac{a^h - 1}{h} < \\
< (n+1) \left( \frac{1}{n} - 1 \right), \text{ если } h > 0, \\
\frac{n \left( \frac{1}{n+1} - 1 \right)}{a^{n+1}} < \frac{a^h - 1}{h} < \\
< (n+1) \left( \frac{1}{n} - 1 \right), \text{ если } h < 0.
\end{cases}$$

Let us introduce the following notation:
$$n \left( \frac{1}{n+1} - 1 \right) = u_n,$$
$$(n+1) \left( \frac{1}{n} - 1 \right) = v_n,$$
$$\frac{u_n}{a^{n+1}} = u'_n, \quad \frac{v_n}{a^{n+1}} = v'_n.$$

Then the resulting inequalities will take the following form:
$$\begin{cases}
u_n < \frac{a^h - 1}{h} < v_n, \text{ если } h > 0, \\
u'_n < \frac{a^h - 1}{h} < v'_n, \text{ если } h < 0,
\end{cases}$$

and for any $h$, modulo $1/n$,

$$u'_n < \frac{a^h - 1}{h} < v_n.$$ (5)

Let now $n \rightarrow +\infty$. Then
$$\lim_{n \rightarrow +\infty} u_n = \lim_{n \rightarrow +\infty} v_n = \lim_{n \rightarrow +\infty} u'_n =$$
$$= \lim_{n \rightarrow +\infty} v'_n = \varphi(a).$$

In fact, since
$$u_n = (n+1) \left( \frac{1}{n+1} - 1 \right) - \left( a^{n+1} - 1 \right) = x_{n+1} - \left( a^{n+1} - 1 \right),$$
$$v_n = n \left( a^{n+1} - 1 \right) + \left( a^{n+1} - 1 \right) = x_n + \left( a^{n+1} - 1 \right),$$

then according to equalities (3) and (4)
$$\lim_{n \rightarrow +\infty} u_n = \lim_{n \rightarrow +\infty} x_{n+1} - \lim_{n \rightarrow +\infty} \left( a^{n+1} - 1 \right) =$$
$$= \lim_{n \rightarrow +\infty} x_{n+1} = \varphi(a).$$

Further, according to the same equality (4)
$$\lim_{n \rightarrow +\infty} a^n = \lim_{n \rightarrow +\infty} a^{n+1} = 1,$$
and therefore
$$\lim_{n \rightarrow +\infty} u'_n = \lim_{n \rightarrow +\infty} \frac{u_n}{a^{n+1}} =$$
$$= \lim_{n \rightarrow +\infty} u_n = \varphi(a), \lim_{n \rightarrow +\infty} v'_n =$$
$$= \lim_{n \rightarrow +\infty} \frac{v_n}{a^{n+1}} = \varphi(a).$$

Note that the sequence $\{v_n\}$ kills monotonically, and $\{u'_n\}$ returns.

So, we came to the following conclusion (see figure): if $0 < |h| \leq 1$, then the relation we are interested in, that is, $(a^h - 1):h$, can be “squeezed” into the interval $]u_n, v'_n$ [(if $h > 0$) or into the interval $]u'_n, v'_n$ [(if $h < 0$), and with the tendency $n \rightarrow +\infty$ the ends of these intervals tend to the same number $\varphi(a)$. It is clear that otherwise the ratio tends to the same number, that is
$$a > 1 \Rightarrow \lim_{h \rightarrow 0} \frac{a^h - 1}{h} = \varphi(a) > 0.$$

Indeed, any $\varepsilon > 0$ is possible, and we will look for a $\delta > 0$ such that
$$|h| < \delta \Rightarrow |\varphi(a) - \frac{a^h - 1}{h}| < \varepsilon.$$

(According to the definition of the limit of a function, this will mean that $\lim_{h \rightarrow 0} (1/h) \times (a^h - 1) = \varphi(a)$).

Since the sequences $\{u'_n\}$ and $\{v'_n\}$ converge to $\varphi(a)$, moreover, the first increases and the second kills, then for a given number $\varepsilon > 0$ one can find a number $N$ such that
$$-\varepsilon < u'_N - \varphi(a) \text{ и } v_N - \varphi(a) < \varepsilon.$$ (6)

Let us now take $\delta = 1/N$. If $|h| < \delta = 1/N$, then we have (see (5)) the inequalities
