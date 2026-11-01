---
id: 1983-10-pecherskiy-nx-xn-0b008072
issue: kvant_1983_10
year: 1983
number: "10"
title: n^x = x^n
authors:
  - Печерский Л. Б.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 33
page_last: 33
page_labels: "31"
tag: Q8RI
lang: en
source: kvant_digital
extraction: vision
content_sha256: c0081b52d3932d3179456208e444be20435b026df3cdbec6a4a22607d743be12
prompt_sha256: draft-1
translated_from: content/ru/1983/10/articles/10_pecherskiy-nx-xn-0b008072.md
source_content_sha256: f1b91d6d0c974a690a22190dc1258b92be3ef24414064fbddb73868bf27eb1f1
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 31⟧

$$n^x = X^n$$

L. B. PECHERSKY

How many roots does this equation have if $n \in \mathbb{N}$ and $n \neq 1$?

With open roots, everything is simple and clear: if $n$ is even, the equation has one negative root (draw a graph!); if $n$ is odd, there are no such roots.

Will take up positive roots. This equation is strongly equal to the equations

$$\ln (n^x) = \ln (x^n),$$
$$x \cdot \ln n = n \cdot \ln x,$$
$$x \cdot \ln n - n \cdot \ln x = 0.$$

How many zeros*) does the function $y(x) = x \cdot \ln n - n \cdot \ln x$ have on $]0; +\infty[$?

Its product of $y'(x) = \ln n - \frac{n}{x}$ by $]0; +\infty[$ returns (draw a graph!). At point $x_0 = \frac{n}{\ln n} y'(x_0) = 0$; that means on $]0; x_0[$ $y'(x) < 0$, on $]x_0; +\infty[$ $y'(x) > 0$. Since the function $y$ is non-prime at the point $x_0$, $x_0$ is its minimum point. At $]0; x_0[$ the function $y$ decreases, at $[x_0; +\infty[$ it returns.

What sign does the function $y$ have at the point $x_0$?

$$y(x_0) = n(1 - \ln n + \ln \ln n).$$

To determine the sign of the number $y(x_0)$, we examine the function $z(x) = 1 - \ln x + \ln \ln x$. Since $z'(x) = \frac{1 - \ln x}{x \cdot \ln x}$, $x_1 = e$ is the maximum point of the function $z$, and at $]1; e]$ $z$ returns, at $[e; +\infty[$ it decreases. Since $z(x_1) = 0$, at other points of the domain of definition $z(x) < 0$; in part, at $n \in \mathbb{N}$, $n \neq 1$ $z(n) < 0$. So, $y(x_0) < 0$.

The function $y$ is non-prime on $]0; +\infty[$ it is decreasing. Since “near zero” (for example, obviously at $x < 1$) $y(x) > 0$, and $y(x_0) < 0$, on the interval $]0; x_0[$ the function $y$ has exactly one zero (see figure).

Let us show that for “large” $x$ (“on the plane of infinity”) $y(x) > 0$. To do this, consider the function $u(x) = \frac{x}{\ln x}$. Because $u'(x) = \frac{\ln x - 1}{\ln^2 x}$, $u$ returns to $[e; +\infty[$. If $n \geq 3$, then at $x > n \geq 3$

$$\frac{x}{\ln x} > \frac{n}{\ln n},$$
$$x \cdot \ln n > n \cdot \ln x,$$
$$x \cdot \ln n - n \cdot \ln x > 0,$$
$$y(x) > 0.$$

Prove for yourself that for $n = 2$ $y(x) > 0$ for “large” $x$.

Since $y(x_0) < 0$, $y$ returns on $[x_0; +\infty[$ and $y(x) > 0$, for “large” $x$, on the interval $]x_0; +\infty[$ the function $y$ also has exactly one zero (see figure).

So, for $n \geq 2$, the equation in the title has two roots on $]0; +\infty[$: one on $]0; x_0[$, the other on $]x_0; +\infty[$.

By the way, one of its roots: $x = n$ - very iden right away.

Problems about the number of roots of a certain equation $f(x) = g(x)$ are encountered in entrance exams. As a rule, equations are given that are inaccessible to algebraic means. In such cases, it is often useful to examine the function $f$, $g$ included in the equation, and here it is quite natural to use analysis tools.
