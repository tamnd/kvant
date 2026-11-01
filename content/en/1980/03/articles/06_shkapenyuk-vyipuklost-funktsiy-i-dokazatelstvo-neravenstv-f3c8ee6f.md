---
id: 1980-3-shkapenyuk-vyipuklost-funktsiy-i-dokazatelstvo-neravenstv-f3c8ee6f
issue: kvant_1980_3
year: 1980
number: "3"
title: Convexity of functions and proof of inequalities
authors:
  - Шкапенюк М. Б.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 23
page_last: 24
page_labels: 21-22
tag: 4XE9
lang: en
source: kvant_digital
extraction: vision
content_sha256: bd3136b91a2c1608061fbe4aaaf39bb7d63e466265500495ef04bc8b0ff328a8
prompt_sha256: draft-1
translated_from: content/ru/1980/03/articles/06_shkapenyuk-vyipuklost-funktsiy-i-dokazatelstvo-neravenstv-f3c8ee6f.md
source_content_sha256: b2f3fe1b0085b17fa3967de220a0beaf491f94b73dc1e6817256652c388b346c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 21⟧

M. Shkapenyuk

CONVEX
FUNCTIONS
AND PROOF
INEQUALITIES

This article explores the properties of convex functions. In particular, an inequality is established between the arithmetic mean value of a convex function at n points and its value at the arithmetic mean of these points. From this inequality the classical relations between the harmonic mean, geometric mean, arithmetic mean and quadratic mean are easily obtained.

Convex functions
Let us consider the function $f$, differentiate at any point of the segment $[a; b]$, and denote by $\Gamma$ the part of the graph of the function $f$ corresponding to this segment:

$$\Gamma = \{(x; y) | x \in [a; b] \text{ и } y = f(x)\}.$$

The function $f$ is called upward convex on the segment $[a; b]$ (“Algebra and Principles of Analysis 10”, p. 79) if for any point $T \in \Gamma$ the curve $\Gamma$ lies below the tangent to $\Gamma$ at the point $T$ (Fig. 1 a). Analytically, as is easy to see (Fig. 2), this condition is written in the form of the inequality

$$f(x_2) < f(x_1) + f'(x_1)(x_2 - x_1),$$

which must hold for any (different) $x_1, x_2 \in [a; b]$. The downward convexity on the segment (Fig. 1, b) is determined in a similar way; for it, the sign < in inequality (1) must be replaced by >.

In the same paragraph of the textbook, it is formulated sufficiently for any functions: if on the interval the second is arbitrary positive (negative), then the graph is convex downward (upward). Geometric in the first case obtue is an accelerated increase or a slow decrease, and in the second - a slow decrease or an accelerated decrease.

Examples 1) The function $f(x) = x^2$ is convex downward on any segment $[a; b]$. 2) Function $f(x) = \lg x$ convexes upward $[a; b]$ if $0 < a < b$. 3) Function $f(x) = \sin x$ convex up $[0; \pi]$ and convex down $[\pi; 2\pi]$.

Let us now consider several simple properties of convex functions; We formulate them for the case of upwardly convex functions, leaving the reader to reformulate them for downwardly convex functions.

I. If $f$ is convex upward $[a; b]$, then for any (different) points

$$f\left(\frac{1}{2}(x_1 + x_2)\right) > \frac{1}{2}(f(x_1) + f(x_2)).$$

Fig. 1 a

Fig. 1 6

⟦folio 22⟧

The proof is obvious: it is enough to check the tangent to the graph of the functions at the point $\frac{1}{2}(x_1+x_2) \in [a; b]$ and note that the length of the segment $|AB|$ is equal to $\frac{1}{2}(f(x_1)+f(x_2))$ (Fig. 3).

It can be shown that a function differentiable on the interval $[a; b]$ and possessing property I will be upward convex. This fact is not required, so we do not provide a proof.

II. If the function $f(x)$, $g(x)$ are convex upward on $[a; b]$, then their sum $h(x)=f(x)+g(x)$ is also convex upward on $[a; b]$.

Indeed, adding inequalities (1) for $f$ and $g$ and using the fact that $h'(x)=f'(x)+g'(x)$, we immediately obtain inequality (1) for the function $h$.

III. If the function $f(x)$ is convex upward on $[a; b]$, then the function $h(x)=-f(x)$ is convex downward on $[a; b]$.

This follows immediately from the definition of convexity of a function. The following property immediately follows from properties II and III:

IV. If the function $f(x)$ is convex upward on $[a; b]$, and the function $g(x)$ is convex downward on this segment, then the function $h(x)=f(x)-g(x)$ is convex upward on it.

And here is the promised basic inequality.

Theorem. If the function is convex upward on $[a; b]$ and the numbers $x_1, x_2, \dots, x_n \in [a; b]$ ($n \geqslant 2$) are not all equal, then

$$f\left(\frac{1}{n}(x_1+\dots+x_n)\right) > \frac{1}{n}[f(x_1)+\dots+f(x_n)].$$

This theorem is an inexhaustible source of inequality: it is enough to substitute any convex upward concreting function together with the function $f$ in (*) and... the inequality is complete! For example, taking together the $f$ function sin, we obtain that for any (different) $x_1, \dots, x_n \in [0; \pi]$ the following inequality holds:

$$\sin\left(\frac{1}{n}(x_1+\dots+x_n)\right) > \frac{1}{n}(\sin x_1+\dots+\sin x_n).$$

We will turn off the proof of the theorem until the end of the article, but now let’s see how it turns out.

Classical inequalities

Let us recall several definitions that are often found in mathematics and play an important role in its applications (probability theory, mathematical statistics, etc.).

The harmonic mean positive number $x_1, x_2, \dots, x_n$ is the number

$$P_{-1} = \left(\frac{1}{n}(x_1^{-1}+x_2^{-1}+\dots+x_n^{-1})\right)^{-1} = n/(x_1^{-1}+x_2^{-1}+\dots+x_n^{-1}).$$

The geometric mean positive number $x_1, x_2, \dots, x_n$ is the number

$$P_0 = \sqrt{x_1 \cdot x_2 \cdot \dots \cdot x_n},$$
