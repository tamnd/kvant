---
id: 1972-3-kleyman-neuzheli-otkryitie-ce84e03d
issue: kvant_1972_3
year: 1972
number: "3"
title: Is it really a discovery?
authors:
  - Клейман Я. М.
rubric: smes
page_first: 35
page_last: 35
page_labels: "33"
tag: GN8W
lang: en
source: kvant_digital
extraction: vision
content_sha256: aa2f2b4ce6e59967adc4ea94c0d44c171047eca986b8fc9554f6641b68a44a15
prompt_sha256: draft-1
translated_from: content/ru/1972/03/articles/10_kleyman-neuzheli-otkryitie-ce84e03d.md
source_content_sha256: ae1c7a9cd6e23b55c08ead97d04bf7eee6457a4448009dcfe90de5e360e6c4dc
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 33⟧

After considering approximate numerical solutions of the equation of calculated powers using the methods of trials, chords, tangents and integration, in the final elective lesson on the topic: “Approximate solutions of the equation,” students tried to explore the following method for numerically solving the equation.

Let the equation $f(x) = 0$ have a single root $x_0$ on the segment $a \leq x \leq b$, and let the function $f(x)$ be continuous on this segment and take values ​​of different signs at its ends. Let us draw chords $AC$ and $BC$ for the graph of the given function on the segment $[a, b]$.

Let us write down the equation of the line passing through the points $A[b; f(b)]$ and $C(x_0; 0)$:

$$\frac{f(b) - y}{f(b) - 0} = \frac{b - x}{b - x_0},$$

from which it is located

$$y = f(b) - \frac{b - x}{b - x_0} f(b).$$

Similarly, we write the equation of the line passing through the points $B[a; f(a)]$ and $C(x_0; 0)$:

$$\frac{f(a) - y}{f(a) - 0} = \frac{a - x}{a - x_0},$$

![Graph of the function $y = f(b) - \frac{b - x}{b - x_0} f(b)$](image)

where

$$y = f(a) - \frac{a - x}{a - x_0} f(a).$$

To find the coordinates of the intersection point of these lines, we solve the system

$$\begin{cases}
y = f(b) - \frac{b - x}{b - x_0} f(b), \\
y = f(a) - \frac{a - x}{a - x_0} f(a).
\end{cases}$$

Writing out the whole thing 收支

$$f(b) - \frac{b - x}{b - x_0} f(b) = f(a) - \frac{a - x}{a - x_0} f(a),$$

$$f(b) \left[ 1 - \frac{b - x}{b - x_0} \right] = f(a) \left[ 1 - \frac{a - x}{a - x_0} \right],$$

$$f(b) \cdot \frac{x - x_0}{b - x_0} = f(a) \cdot \frac{x - x_0}{a - x_0},$$

$$\frac{f(b)}{f(a)} = \frac{b - x_0}{a - x_0},$$

we find

$$x_0 = \frac{bf(a) - af(b)}{f(a) - f(b)}.$$

A formula has been obtained for the root of this equation $f(x) = 0$! Learning from the unexpected result with great excitement and enthusiasm, they even exclaimed: “Eureka!”

But after a few minutes, an alarming silence was restored in the audience. Everyone was stunned and everyone asked: “How can this be?” Prominent scientists - mathematicians Abel and Evariste Galya for a comprehensive proof that for all equations above the fourth degree it is impossible to create formulas for exact solutions.

Where was the mistake made?

Y. M. Kleiman
