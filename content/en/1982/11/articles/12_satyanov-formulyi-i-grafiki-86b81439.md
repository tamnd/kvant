---
id: 1982-11-satyanov-formulyi-i-grafiki-86b81439
issue: kvant_1982_11
year: 1982
number: "11"
title: Formulas and graphs
authors:
  - Сатьянов П. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 50
page_labels: 46-48
tag: RSB4
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5f488d1522f49addd4d84f6cd87183c8f5decf6b95bf1fd93bddf94eb006b7b8
prompt_sha256: draft-1
translated_from: content/ru/1982/11/articles/12_satyanov-formulyi-i-grafiki-86b81439.md
source_content_sha256: 1464668bd8fa8adaa2f665075a0ff1b21232ce5851ad07e2fd8801d9ea3efa84
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

P. Satyanov

Formulas and graphs

Arithmetic symbols are written geometric figures, and geometric figures are drawn formulas.

(D. Gilbert)

How is this or that feature of the formula defining a function reflected in the graph of this function? The ability to answer this question correctly - in different situations - was useful when constructing graphs, in particular those that come across in entrance exams. We do not dwell here on the features of function graphs associated with their extrema (this is discussed in detail in the textbook “Al-

Zeros and sign changes

If the function $y=f(x)$ vanishes at some point $x_0$, this does not mean that the graph of the function $f$ inversely intersects the $Ox$ axis at a non-zero angle. There are other possibilities - for example, touch (change sign or not). How to distinguish a touch from a simple change of sign?

Graph of function$^*$

$$y=(x-1)^3(x-2)^2$$

depicted on figure 1. In formula (1), $x-1$ can appear in an odd degree - therefore, when passing $x=1$, it changes sign. The multiplier $x-2$ does not change the sign when passing $x=1$, of course. Consequently, when passing $x=1$, their product changes sign - the graph intersects the x-axis. The factor $x-2$ is included in formula (1) in even

*) On this and the next figure the scale along the $Oy$ axis differs from the scale along $Ox$.

⟦folio 47⟧

degree - therefore, when passing through $x=2$ it does not change sign. The factor $x-1$ when passing through $x=2$ also, of course, does not change sign. Consequently, their product does not change sign when passing through $x=2$, and the graph touches the $x$ axis without intersecting it at point $x=2$.

The graphs of functions $y=(x-1)^2 \times (x-4)^4$ and $y=-(x-1)^2(x-4)^4$ are shown in Figures 2 and 3, respectively.

Thus, in expressions of the form $f(x)=\varphi(x)(x-a)^k$ ($k \in N$), where $\varphi(a) \neq 0$ and $\varphi$ are nonprime at the point $x=a$, it is all about the purity of $k$: the change of sign at the point $x=a$ occurs if and only if $k$ is odd. In the case where $\varphi$ is differentiable at $x=a$, the graph of $f$ touches the $Ox$ axis at $a$ if $k \geq 2$ (think about why), and remains on the same side of the $Ox$ axis if and only if $k$ is even.

Vertical asymptotes

The graph of functions $y=\frac{1}{x-2}$ is shown in figure 4. As $x$ approaches 2, the model $\left|\frac{1}{x-2}\right|$ increases indefinitely; in this case, the straight line $x=2$ is called a vertical asymptote. We'll write it like this:

$$\lim_{x \to 2} \left|\frac{1}{x-2}\right| = +\infty.$$

In the future, we will use this convenient notation, although it is not in the school textbook. During the exam, of course, it is a little dangerous to use extragram material; therefore, it is better to say in words that for $x \to 2$ the function $1/|x-2|$ increases without limit. For the curious, we provide the corresponding definition in the general case: the function $f(x)$ tends to $+\infty$ for $x \to a$ (notation: $\lim_{x \to a} f(x) = +\infty$), if for any number $A_0$ there exists a $x_0$ such that $f(x) > A_0$, as soon as $x$ is close to $a$ than $x_0$, more precisely, as soon as $0 < |x-a| < |x_0-a|$.

The behavior of the functions $y=\frac{1}{x-2}$ in the neighborhood of the point $x=2$ can be described in more detail - with $x$ tending to 2 from the right (“Algebra and the beginnings of analysis 9-10”, paragraph 11), $\frac{1}{x-2}$ tends to $+\infty$:

$$\lim_{x \to 2+0} \frac{1}{x-2} = +\infty;$$

with $x$ tending to 2 words, $\frac{1}{x-2}$ tends to $-\infty$:

$$\lim_{x \to 2-0} \frac{1}{x-2} = -\infty.$$

The line $x=2$ is also the (vertical) asymptote of the graph of the function $y=\frac{1}{(x-2)^2}$ (Fig. 5):

$$\lim_{x \to \infty} \left|\frac{1}{(x-2)^2}\right| = \lim_{x \to 2} \frac{1}{(x-2)^2} = +\infty.$$

In this case, with $x$ tending to 2 words, and with $x$ tending to 2 words, $\frac{1}{(x-2)^2}$ tends to $+\infty$:

$$\lim_{x \to 2+0} \frac{1}{(x-2)^2} = +\infty,$$

$$\lim_{x \to 2-0} \frac{1}{(x-2)^2} = +\infty.$$

The line $x=2$ is also an asymptote of the graph of the functions $y=-\frac{1}{x-2}$ (Fig. 6) and $y=-\frac{1}{(x-2)^2}$ (Fig. 7).

Any line of the form $x=\frac{\pi}{2}+\pi k$ ($k \in Z$) is an asymptote of the graph of the function $y=\mathrm{tg} x$ (Fig. 8).

The straight line $x=0$ is the asymptote of the graph of the function $y=\log_a x$ at $x$,

⟦folio 48⟧

tending to 0 from the right (at figure 9 $a > 1$).

Horizontal asymptotes

When $x$ increases indefinitely (mathematicians say “tend to +∞”), the graph of the function $y = \frac{1+x}{x}$ indefinitely approaches the straight line $y=1$ (Fig. 10); in this case, the straight line $y=1$ is called a horizontal asymptosis. When $x$ increases indefinitely, that is, increases indefinitely modulo, being negative (mathematicians say “tend to -∞”), the graph of the function $y = \frac{1+x}{x}$ also indefinitely approaches the straight line $y=1$ (see Fig. 10); the straight line $y=1$ is a horizontal asympt also for an unlimited increase $x$. All this can be briefly written as

$$\lim_{x \to +\infty} \frac{1+x}{x} = 1,$$

$$\lim_{x \to -\infty} \frac{1+x}{x} = 1.$$

We'll also use this handy notation, although it's not in the textbook. We give the definition in the general case: the function $f(x)$ strives to $A$ for $x$, strives to $+\infty$ (in formula notation $\lim_{x \to +\infty} f(x)=A$), if for any $\varepsilon > 0$ one can find a $X$ such that $x > X \Rightarrow |f(x)-A| < \varepsilon.$
