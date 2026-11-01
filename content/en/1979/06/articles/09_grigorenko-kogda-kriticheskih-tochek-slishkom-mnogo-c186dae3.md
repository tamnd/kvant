---
id: 1979-6-grigorenko-kogda-kriticheskih-tochek-slishkom-mnogo-c186dae3
issue: kvant_1979_6
year: 1979
number: "6"
title: When there are too many critical points
authors:
  - Григоренко В.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 26
page_last: 27
page_labels: 24-25
tag: D85A
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9739aa8c9d5f2bdb78f99607f7b71c63ba1d27f2aaef7957e06bfdce5d77dff7
prompt_sha256: draft-1
translated_from: content/ru/1979/06/articles/09_grigorenko-kogda-kriticheskih-tochek-slishkom-mnogo-c186dae3.md
source_content_sha256: ab47e8bf4f3a5dbd71566de4424b548368ce363482be35da5bb31f4cdd3759d4
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 24⟧

V. Grigorenko

When
critical points
too much

In paragraph 55 of the manual “Algebra and the beginnings of analysis 9”, the correct study of the critical point at the extremum is indicated (Theorems 1, 2). Is this always correct?

Unexpected situations in which it cannot be used are discussed in this article.

Recall that an interior point $x_0$ has a certain function $f$ called critical for this function if $f'(x_0) = 0$ or $f'(x_0)$ does not exist.

Let us assume (for simplicity of presentation) that the function $f$ is not true at the point $x_0$. (From this assumption it automatically follows that the point $x_0$ is an interior point of the domain of definition of the function $f$.)

According to the sufficient condition for a maximum (“Algebra and Principles of Analysis 9”, paragraph 55, Theorem 2), if there is a maximum $|x_0| - \delta$; $x_0 + \delta$ [lobes $x_0$, left half-cross $|x_0| - \delta$; $x_0$ [side $f'(x) > 0$ and right half-cross $|x_0|$; $x_0 + \delta$ [with $f'(x) < 0$, then the point $x_0$ is a powerful function of $f$.

Naturally they will ask: is the opposite true? Let us clarify our question: let the function $f$ be differentiable in some neighborhood of the point $x_0$ and let this point be the maximum point of the function $f$; Is there necessarily a neighborhood at the point $x_0$ in which the derivative “changes sign from flat to negative”? Roughly speaking, is the maximum condition sufficiently necessary?

It turns out that the answer to these questions is negative.

Example 1. Function

$$f(x) = \begin{cases} 2 - x^2 \left(2 + \sin \frac{1}{x}\right), & если x \neq 0 \\ 2, & если x = 0 \end{cases}$$

differentiate on the entire number line $R$, the point 0 is a strong maximum of the function $f$ and in each of the semi-positives of any neighborhood ] - δ; δ[lobes 0 derivative $f'$ changes sign (Fig. 1*)).

Indeed, the function $f$ is obviously differentiable at any point $x_0 \neq 0$; it is also differentiable at point 0, since

$$f'(0) = \lim_{h \to 0} \frac{f(h) - f(0)}{h - 0} = \lim_{h \to 0} \left[ -h \left(2 + \sin \frac{1}{h}\right) \right] = 0.$$

(The last equality follows from the fact that $\lim_{h \to 0} (-h) = 0$, and the function $y = 2 + \sin \frac{1}{h}$ is limited to $R$, i.e., by virtue of the analogue of Theorem 2 from paragraph 28 of the manual “Algebra and Principles of Analysis 9”.) Point 0 is a powerful maximum of $f$, since at $x \neq 0$, obviously, $f(x) < f(0)$. Finally, in each of the intervals ]—δ; 0 [ and ]0; δ[ derivative

$$f'(x) = -4x - 2x \sin \frac{1}{x} + \cos \frac{1}{x}$$

*) In all figures, the scales along the axes are different. In the vicinity of zero figure they lose the necessary degree of detail and become incorrect.

⟦folio 25⟧

changes sign (explanation “on fingers”: at $x \to 0$ the terms $-4x$ and $-2x \sin \frac{1}{x}$ tend to 0 and, therefore, become arbitrarily small, while the term $\cos \frac{1}{x}$ constantly changes sign, moving from +1 to -1 and vice versa).

The reason for this inappropriate situation is that in any neighborhood of the point 0 there are infinitely many critical points of the functions $f$ (see Fig. 1); passing through them, the derivative $f'$ changes sign.

Of course, such a “cluster” of critical points does not exist if the functions $f$ have a finite number of critical points or at least a finite number on any interval $[a; b]$ (as, for example, the functions $y = \sin x$). In this case, at each interval between adjacent critical points, the derivative $f'$ retains its sign (this statement is geometrically obvious, but it is not very easy to prove).

In the case of a “cluster” of critical points, the vector of a certain point $x_0$ cannot be studied for the extremum at this point by the sign of the derivative.

Example 2. There are also functions $f$ and $g$, differentiable on $R$, such that point 0 is the maximum point for one of them and the minimum point for the other, but at all points in a certain neighborhood of point 0 the derivatives $f'(x)$ and $g'(x)$ have the same sign.

We will not give explicit formulas for the required functions, but will limit ourselves to their graphs (Fig. 2); Please note that function examples do not have to be built “in the language of formulas”; they can simply be drawn).

What to do in this case? No general advice can be given. If you have a suggestion from one or another message that a similar point $x_0$ is, say, a minimum point of the function $f$, you can try to prove the inequality $f(x) > f(x_0)$ for all $x$ from some neighborhood of the point $x_0$ “at any time”.

In example 1, point 0, around which critical points “accumulated”, was also critical. However, this is not necessary.

Example 3. In any neighborhood of point 0 there are infinitely many critical points of functions

$$f(x) = \begin{cases} x + x^2 \cos \frac{1}{x^2}, & \text{ если } x \neq 0, \\ 0, & \text{ если } x = 0, \end{cases}$$

at point 0 is not critical.

Check that

$$f'(x) = \begin{cases} 1 + \frac{2}{x} \sin \frac{1}{x^2}, & \text{ если } x \neq 0, \\ + 2x \cos \frac{1}{x^2}, & \text{ если } x = 0, \\ 1, & \text{ если } x = 0. \end{cases}$$

Since in any neighborhood of the point 0 the derivative $f'$ changes sign (why?), it becomes 0 in any neighborhood *); it's the same

*) It is easy to prove this in this system, using the theorems from paragraph 84 of the manual “Algebra and the beginnings of analysis 10”.

Fig. 2

Fig. 3.
