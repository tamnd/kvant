---
id: 1989-4-lvovskiy-proizvodnaya-slozhnoy-i-obratnoy-funktsiy-bc50f6af
issue: kvant_1989_4
year: 1989
number: "4"
title: Derivative of complex and inverse functions
authors:
  - Львовский С. М.
rubric: shkola-v-kvante
page_first: 38
page_last: 41
page_labels: 36-39
tag: S5CM
lang: en
source: kvant_digital
extraction: vision
content_sha256: 22367c36dcee35ca3c6a52b00a2b22d60662336710ab14c70e9b5bc9a9eb1fe2
prompt_sha256: draft-1
translated_from: content/ru/1989/04/articles/08_lvovskiy-proizvodnaya-slozhnoy-i-obratnoy-funktsiy-bc50f6af.md
source_content_sha256: 683e308b6b5e98ca57d79a27edc3a55e854566679d83421f78aeea6cb1c2e7f9
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

Mathematics 8, 9,10

Published article intended for ninth and tenth graders.

Derivative of complex and inverse functions

From your school textbook you know two interpretations of the derivative of a function - geometric and mechanical *). You know that the existence of a derivative of the function $f$ at the point $x$ is equivalent to the existence of a non-vertical tangent at the point $(x; f(x))$

graph of the function, and the slope of this tangent is equal to $f'(x)$. In addition, you know that the derivative of a coordinate with respect to time is the instantaneous speed. Now we will introduce you to another interpretation of the derivative. With its help we will illustrate the formulas for the derivatives of complex and inverse functions.

The derivative is the stretch factor

Let's draw two number lines - blue and red. On one of them - blue - we will plot the values ​​of the argument, and on the other - red - the corresponding values ​​of the functions (on the same scale).

Figures 1 and 2 show what happens for the functions $f(x)=3x+1$ and $g(x)=x^3$. As can be seen from figure 1, ​​the function $f(x)=3x+1$ translates the rep-

*) See the textbook for grades 9-10 “Algebra and the beginnings of analysis” (M., Prosveshchenie, 1988, pp. 22-24).

⟦folio 37⟧

code [−1; 0] into the segment [−2; 1], segment [0; 1] - into the segment [1; 4], segment [1; 2] - into the segment [4; 7], etc. In all these cases, the length of the segment increases by 3 times. This is not surprising: after all, the segment [a; b] our function translates into the segment [3a+1; 3b+1].

So the function $f(x)=3x+1$ changes the lengths of all segments of the real line in the same way: it multiplies by 3. (A similar remark holds for any length of the new function.)

From figure 2 it is clear that the (non-linear) function $g(x)=x^3$ stretches segments located in different places on the number axis in different ways: for example, the segment [0,8; 0.9] - 2.2 times, and the segment [1.1; 1.2] - 4 times. Therefore, it makes no sense to ask how many times $g$ stretches the segments located on the numerical axis $b\ell n\zeta$ of a given point. For example, at close points $x=1$. Let's start with segments of length 0.1: segment [0.9; 1] increases by 2.7 times, and the segment [1; 1.1] - 3.3 times. Let's take short segments - [0.99; 1] and [1; 1.01]. We have: $0,99^3\approx 0,97,1,01^3\approx 1,03$ (we leave two decimal places). Therefore, the segment [1; 1.01] stretches $\frac{1,01^3-1^3}{1,01-1}\approx 3$ times; similarly, the segment [0.99; 1] stretches $\frac{1^3-0,99^3}{1-0,99}\approx 3$ times. If we take even shorter segments containing point 1, the stretch factor will be even closer to 3. So, the function $g(x)=x^3$ expands:

$$\frac{1,01^3-1^3}{1,01-1}=3$$

Gris. 2.

Grisens segments close to point 1 approximately 3 times. The closer the segment is to point $x=1$, the closer to 3 the stretching coefficient at point $x=1$.

Now note that for any (differentiable) function $f$, the dilation coefficient of small segments close to the point $x$ is nothing more than the derivative $f$ at the point $x$. In fact, if the point $x_1$ is close to $x$, the segment $[x; x_1]$ goes into the segment $[f(x); f(x_1)]$, and its dilation coefficient is $\frac{f(x_1)-f(x)}{x_1-x}$, and this is the same expression that is used to define an arbitrary function at the point $x$ (the substitute is the increment of the argument, the numerator is the increment of the function). When $x_1$ tends to $x$ (the segment shortens), this ratio tends to $f'(x)$.

Let's check our choice for the function $g(x)=x^3$. As you know, $g'(x)=3x^2$, so $g'(1)=3$; this coincides with the stretch coefficient, which we found approximately.

In our examples, the stretching coefficient, i.e. the derivative, was greater than unity; if the stretching coefficient is less than one, but positive, then the segments close to a given point are not stretched, but are compressed (their lengths are multiplied by a number less than 1); if $f'(x)<0$, then the segments are “turned over”: the left end of the segment [a; b] goes to the right end of the segment $[f(b); f(a)]$. This is not surprising: where the derivative is negative, the function kills, so from $a<b$ it follows that $f(b)<f(a)$.

⟦folio 38⟧

So, the main choice of this point: small segments close to the point $x$ are stretched by the function $f$ with a coefficient close to $f'(x)$. The closer the segment is to point $x$, the closer the coefficient is to $f'(x)$. Throughout what follows we will, for the sake of brevity, omit these explanations and write phrases like “function $f(x)=x^3$ stretches segments close to point 1 by a factor of 3.” We hope this doesn't bother you.

Function composition (complex function)

Let's take the function $f(x)=\sqrt{x^3}+1$. It takes point $x$ to point $\sqrt{x^3}+1$. This translation can be carried out in two stages: first, transfer the point $x$ to the point $t=x^3+1$, and then transfer the point $t$ to the point $\sqrt{t}$. Consider the functions $g(x)=x^3+1$ and $h(t)=\sqrt{t}$. Then it turns out that $f(x)=h(g(x))$. Sometimes it is written like this: $f=h\circ g$ and they say that $f$ is a composition of the functions $h$ and $g$. About the notation $f(x)=h(g(x))$ they also say that $f$ is written as a complex function.

If we use our schematic representation of the functions, we get what is shown in figure 3. (As before, the values ​​$x$ are on the blue axis, the values ​​$f(x)$ are on the red axis.)

How to calculate an arbitrary complex function

Let us consider the same function $f(x)=\sqrt{x^3}+1$ and find its arbitrary function at the point $x=2$. We already know that arbitrary at point $x=2$ is the stretching coefficient of segments close to point 2 when moving from the blue axis to the red one (Fig. 3). On the way from the blue axis to the red one, the segment ends up on the green axis, where its length is multiplied by $g'(2)=12$; when moving from the green to the red axis, the length of the resulting segment is multiplied, in turn, by $h'(g(2))=h'(9)=\frac{1}{6}$; in total, therefore,

⟦folio 39⟧

the length of the segment will be multiplied by $12 \cdot \frac{1}{6} = 2$, so that $f'(2) = 2$.

Repeating the same reasoning for any point $x$, we obtain the following rule:

$$\text{если } f(x) = h(g(x)), \\
\text{то } f'(x) = g'(x) \cdot h'(g(x)).$$

This is, of course, true for any functions $h$ and $g$.

In our case, when $h(t) = \sqrt{t}, g(x) = x^3 + 1, f(x) = \sqrt{x^3 + 1}$, we get

$$f'(x) = 3x^2 \cdot \frac{1}{2\sqrt{x^3 + 1}}.$$

So, we have obtained the formula known to you from the textbook for an arbitrary complex function. We can write a similar formula for the case when $f$ is complex not of two, but of three, four, etc. functions.

Inverse function

On figure 4 the function $f(x) = x^3 + 1$ is depicted in the way already given to us. The solid arrows on this figure show how the points $x$ on its axis are translated into points $y = x^3 + 1$ on the red axis. Now let’s imagine that figure 4 sets a law according to which, on the contrary, points from the red axis are transferred to the blue axis (arrows going up to figure)—points $y = x^3 + 1$ are transferred to points $x$. We can express $x$ through $y$ by the formula $x = \sqrt[3]{y - 1}$. The result is a description of the new function. Let's denote it by the letter $g$: $g(y) = \sqrt[3]{y - 1}$. The function $g(y) = \sqrt[3]{y - 1}$ is called the inverse of the function $f(x) = x^3 + 1$. Note that in the formula defining the function $g$ (as in general in any formula defining the function), the independent variable $y$ can be denoted by any letter. You can, for example, write $g(t) = \sqrt[3]{t - 1}$ or even $g(x) = \sqrt[3]{x - 1}$.

Note also that not every function has an inverse. Let's take, for example, the function $f(x) = x^2$. This function takes both point 2 and point (-2) to point 4. If $g$ is the inverse
