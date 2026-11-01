---
id: 1981-9-perevalov-mozhno-i-bez-proizvodnoy-e3d30c1b
issue: kvant_1981_9
year: 1981
number: "9"
title: It is possible without derivative
authors:
  - Перевалов Г. Е.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 38
page_last: 41
page_labels: 36-39
tag: VAHI
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9fada5e8bc579ed3496a5d83502672941e3bab2a1d14a3a060be1fbfa8e48294
prompt_sha256: draft-1
translated_from: content/ru/1981/09/articles/13_perevalov-mozhno-i-bez-proizvodnoy-e3d30c1b.md
source_content_sha256: f4efe10f7e6c6f6bbd768d9f1ade939e7ccb4a0c3ff299bd3ea0ab2608f27a03
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 36⟧

G. Perevalov

Possible without free program

Graph Transformation

During the entrance exams, one of the applicants was asked to construct a graph of the function $f(x) = 2\lg(x-1)$. He, as recommended by the textbook “Algebra and the beginnings of analysis 9-10” (p. 27), found the domain of definition of the function $f$, calculated an arbitrary $f'$, saw that it was positive everywhere on $D(f)$, concluded that the function $f$ increases on $D(f)$, found the point of intersection of the graph with the axis abscissa, recorded the results of the study in the form of a table and constructed a graph (Fig. 1, a).

However, the desired graph can be constructed without any calculations if you apply the rules for converting graphs set out at the end of the mentioned manual (“Material for repetition”, paragraph 9). Let's list these rules:

1. The graph of the function $y=f(x)+B$ is obtained from the graph of the function $y=f(x)$ by transferring $\vec{r}(0; B)$, that is, by transferring parallel to the ordinat axis by $B$ - upward, if $B>0$; down if $B<0$ (Fig. 2).

2. The graph of the function $y=f(x+b)$ is obtained from the graph of the function $y=f(x)$ by transferring $\vec{s}(-b; 0)$, that is, by transferring parallel to the abscissa axis by $-b$ - to the left, if $b>0$; to the right if $b<0$ (Fig. 3).

3. The graph of the function $y=A\cdot f(x)$ is obtained by multiplying each ordinate of the graph of the function $y=f(x)$ by $A$, that is, stretching from the abscissa axis by $A$ times, if $A>1$, and rolling towards the abscissa axis by $\frac{1}{A}$ times, if $0<A<1$ (Fig. 4).

3′. The graph of the function $y=-f(x)$ is obtained by the symmetry of the graph of the function $y=f(x)$ about the abscissa axis (Fig. 5).

4. The graph of the function $y=f(ax)$ is obtained by skating the graph of the function $y=f(x)$ to the ordinat axis by $a$ times, if $a>1$, and by stretching it from the ordinat axis by $\frac{1}{a}$ times, if $0<a<1$ (Fig. 6).

4′. The graph of the function $y=f(-x)$ is obtained by the symmetry of the graph of the function $y=f(x)$ about the ordinat axis (Fig. 7).

As a backdrop, we will now present two less important, less universal rules that may be useful in “entrant” tasks:

5. The graph of the function $y=|f(x)|$ coincides with the graph of the function $y=f(x)$ where $f(x) \geq 0$, and is obtained from it by symmetry about the abscissa axis where $f(x) < 0$ (Fig. 8).

6. The graph of the function $y=f(|x|)$ at $x \geq 0$ coincides with the graph of the function $y=f(x)$; with $x<0$ it turns out

⟦folio 37⟧

symmetry of the “right half” of the graph of the function $y=f(x)$ relative to the ordinat axis (Fig. 9).

To construct a graph of the function $y=2\lg(x-1)$ using the graph transformation method, you need to translate the graph of the function $y=\lg x$ parallel to the x-axis to the right by 1 and stretch the resulting graph from the x-axis by 2 times (Fig. 1, ​​b). Compare, reader, the “general” way of constructing this graph (see the beginning of the article) with the one presented here. Isn't it true, this one is much nicer!

Sometimes, in order to apply this method, you must first transform the expression with which the function is specified. For example, the graph of the function $y=\frac{2x-3}{3x+5}$ is easy to construct

⟦folio 38⟧

Fig. 10.

There is a method for converting the graph because
$$\frac{2x-3}{3x+5} = \left(-\frac{19}{9}\right) \cdot \frac{1}{x+\frac{5}{3}} + \frac{2}{3}.$$

Let's write an “auxiliary chain”:

$$y_1 = \frac{1}{x}$$
$$y_2 = \frac{1}{x+\frac{5}{3}}$$
$$y_3 = \frac{19}{9} \cdot \frac{1}{x+\frac{5}{3}}$$
$$y_4 = -\left(\frac{19}{9} \cdot \frac{1}{x+\frac{5}{3}}\right)$$
$$y_5 = \left(-\frac{19}{9}\right) \cdot \frac{1}{x+\frac{5}{3}} + \frac{2}{3}$$

Thus, the desired graph is obtained from the graph of the function $y = \frac{1}{x}$ by four successive transformations: transfer of parallel

Fig. 11.

Linear to the abscissa axis blevo by $\frac{5}{3}$, stretched from the abscissa axis by $\frac{19}{9}$ times, symmetry relative to the abscissa axis and transferred parallel to the ordinate axis by $\frac{2}{3}$ (Fig. 10).

The graph transformation method serves a very wide class of functions. For example, use this method to plot the functions $y = \frac{1}{2x-2}$, $y = \lg(-x) + 2$, $y = 3\sin(2x-1) + 5$, $y = \sin^4x + \cos^4x$.

Make no mistake: the graph of the function $y = f(ax+b)$ is obtained, of course, by transferring the graph of the function $y = f(ax)$ parallel to the abscissa axis, but by transferring it not to $-b$, but to $-\frac{b}{a}$ (why?).

The graph transformation rules listed above allow us to say that if the number $T$ is the period of the function $y = f(x)$, then the period of the function $y = A \cdot f(ax+b) + B$ is the number $\frac{T}{a}$ from all transformations.

⟦folio 39⟧

Actions on charts

Sometimes the desired graph can be obtained by performing arithmetic operations on the “composing graphs” specified in the formula defining the function.

Example 1. Let's try to construct a graph of the function $f(x) = x + \sin x$ using the ordinat graphs of the function $y = x$ and $y = \sin x$ (Fig. 11). Let us note, first of all, that the function $f$ is odd, and therefore we will “add the graph” only for $x \ge 0$. Obviously, where $\sin x > 0$, the desired graph will lie above the straight line $y = x$; on intervals on which $\sin x < 0$, it will lie under this line; at points $x = \pi k$ ($k \in \mathbb{N}$) it will intersect it.

On the segment $[0; \frac{\pi}{2}]$ both terms increase, which means their sum $f$ will also increase. But on the segment, say, $[\frac{\pi}{2}; \pi]$, the first term increases, the second decreases - what will happen to the sum $f$ is not clear. You can't do without calculations here. $f'(x) = 1 + \cos x > 0$ everywhere except points $x = \pi + 2\pi k$ ($k \in \mathbb{N}$). This means that the function $f$ increases by $[0; +\infty]$.

Example 2. Let us now try to construct a graph of the function $f(x) = x \cdot \sin x$ by multiplying the ordinat of the corresponding graphs (Fig. 12). Function $f$ is even, so it will “jump the graph” at $x \ge 0$.

Example 15. On the interval $[0; \frac{\pi}{2}]$ both are positive and increasing, which means that the function $f$ will also increase on this interval. But in the interval $[\frac{\pi}{2}; \pi]$ one of the positive ones with the help of reggae, the second one kills. What will happen to the work? If in the previous example it was still possible to do without an arbitrary one (a proof without an arbitrary one that $x_1 < x_2$ implies $x_1 + \sin x_1 < x_2 + \sin x_2$), then here it was hardly possible to do so. The study of arbitrary ($f'(x) = \sin x + x \cdot \cos x$, $f'(x) = 0 \Leftarrow \mathrm{tg} x = -x$) shows that the extremum points of the functions $f$ and $y = \sin x$ do not coincide (Fig. 13).

Example 3. The graph of the function $f(x) = \frac{1}{\sin x}$ is easily constructed by dividing the ones by the ordinates of the function $y = \sin x$ (Fig. 14). It is also easy to construct any graph of the form $g(x) = \frac{1}{f(x)}$, if the graph of the function $f$ is known (Fig. 15).

Try to construct a graph of the function $y = x + \lg x$, $y = 2^x \cdot \sin x$, $y = \frac{\sin x}{1 + x^2}$ in a similar way.
