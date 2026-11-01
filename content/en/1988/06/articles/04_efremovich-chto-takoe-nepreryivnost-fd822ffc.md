---
id: 1988-6-efremovich-chto-takoe-nepreryivnost-fd822ffc
issue: kvant_1988_6
year: 1988
number: "6"
title: What is continuity
authors:
  - Ефремович В. А.
rubric: raznoe
page_first: 24
page_last: 26
page_labels: 22-24
tag: HK7P
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7725e57cfd80ccb34087f064b63e284c4fdccf96659a9793ac4d67451dbbeca7
prompt_sha256: draft-1
translated_from: content/ru/1988/06/articles/04_efremovich-chto-takoe-nepreryivnost-fd822ffc.md
source_content_sha256: 23bcd77c67caa72884784d13e5cee023ed60e65f34122a0c7a245cb38e7cdece
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 22⟧

WHAT IS CONTINUITY

Doctor of Physical and Mathematical Sciences
V. A. EFREMOVICH

This is a basic concept in mathematics. It belongs to what is called qualitative geometry, i.e. that part of geometry that is not at all intersected by concepts of a measuring nature (distances, lengths, volumes, ...). Despite this (or perhaps because of this?), the entire edifice of mathematical analysis and almost all of geometry stands on it.

These concepts were possessed (on an intuitive level) by the mathematicians of antiquity, but a precise definition was given to it only in the first half of the 19th century, replaced by the French mathematician O. Cauchy (1787-1857). To clarify this definition, we need

General concept of functions

The concept of functions has undergone a number of important generalizations. At first, only numerical functions of a numerical argument were considered, for example $x^3$, Тg $x$, $e^x$, and, moreover, specified by one or another analytical expression. Later it turned out that the latter does not exist. The only important thing is that each value of the argument $x$ corresponds to its own numerical value of the function. A continuous function is represented by a continuous curve obtained by moving the pencil without lifting it from the paper (on figure 1 - continuous function, on figure 2 - discontinuous).

Next, we can consider numerical functions of the exact argument, for example, temperature or atmospheric pressure at various points in space. Another example. The flat piece of land is covered with snow; then the height $h$ of the snow cover at each point $p$ is the value of some function: $h=f(p)$. If coordinates $x$, $y$ are set on the site, each point will receive its own “name”: $p=(x, y)$, and the function $f$ in question can be written as follows: $f(p)=f(x, y)$. It is a function of one variable point $p$, or a function of two numeric variables $x$, $y$. The graph of this function is the snow surface.

Finally, one can consider (the most general case) the exact function of the exact argument, i.e. the mapping $f: X \rightarrow Y$ of the funcurus $X$ into the function $Y$. This is the representation of a spatial function on a flat drawing, for example, the orthogonal projection of a body onto a plane. Any artist's painting or photograph can be viewed as a function (i.e., a mapping), where each point $x$ depicted corresponds to point $x'$ of the image. In this case, $x'=f(x)$ is called the image of the point $x$. Artists were primarily concerned with such display functions. Particularly valuable is the contribution of the Great Leonardo da Vinci (1452-1519), one of the first artists who founded the mathematical theory of perspective.

Continuity

The most general concept of mapping functions makes it possible to fully visualize and at the same time strictly mathematical

Fig. 1.
Fig. 2.

⟦folio 23⟧

explain the concept of continuity. To do this, first consider an example where a discontinuity occurs, i.e., a violation of continuity.

Let $X$ be a rubber band for packaging medicines, a rough model of a circle. Let us assume that during the deformation process it suddenly breaks at some point $a$. What does it mean? Some of its part $B$, adjacent equal to $a$, i.e. located at zero distance from $a$ (we write $B\delta a$), after the break (we will denote it $B'$) turns out to be not close to $a'$ (the new position of the point $a$ - see figure 3). So, a break at point $a$ is an event where some part of $B$, close to $a$ ($B\delta a$), becomes not close to the new position $a'$ of point $a$: $B\delta a$, but $B'\delta a'$. Theler understands the following definition:

The mapping $f$: $X \rightarrow Y$ is said to be continuous at the point $a \in X$ if every part $B \subset X$ close to $a$ after the mapping goes to the position $B'$ close to $a' = f(a)$, i.e.

$$B\delta a \Rightarrow B'\delta a'.$$

The designation $B\delta a$ has a precise meaning: for any arbitrarily small positive $\varepsilon$ in the figure $B$ there is a point $x$ such that $xa < \varepsilon$ (here $xa$ is the distance from $x$ to $a$; henceforth, by $pq$ we denote the distance from $p$ to $q$). Similarly, $A\delta B$ means that in the figures $A$, $B$ there are points $x \in A$, $y \in B$ such that $xy < \varepsilon$ for any positive $\varepsilon$. Note that two lines e of a point cannot be close in this sense: if $a \neq b$, then $a\beta b$ (hereinafter $ab = 10^{-100}$).*

This definition is equivalent to the classical Cauchy definition:

The mapping $f$: $X \rightarrow Y$ is continuous at the point $a \in X$ if for every $\varepsilon > 0$ there is a $a > 0$ such that $xa < \alpha$ implies $x'a' < \varepsilon$ (here $a' = f(a)$, $x' = f(x))$.

The equivalence of the two definitions is proven at the end of our note.

If a function is continuous at every point $x \in X$, then saying that it is continuous on the entire set $X$.

This definition, together with Cauchy's definition, is not so easy to clear. The changed Cauchy himself made mistakes more than once, inadvertently replacing the requirement of continuity with a stronger one - what is now called uniform continuity. This spring is an important part of the case of continuity, and we will dwell on it.

Uniform continuity

The mapping $f$: $X \rightarrow Y$ is called uniformly continuous on $X$ if any two close parts $A$, $B \subset X$ go at $f$ to close parts $A'$, $B' \subset Y$, i.e. $A\delta B \Rightarrow A'\delta B'$.

Exercise. What display

$$tg: \left( -\frac{\pi}{2}; \frac{\pi}{2} \right) \rightarrow R$$

is not uniformly continuous on $(-\pi/2; \pi/2)$. (Here it is more difficult to find the necessary $A$, $B$ such that $A\delta B$, but $A'\delta B'$: these are two sequences of points, for example, the inverse images of the set $A' = \{1, 3, ...\}$, $B' = \{2, 4, ...\}$, $A'\delta B'$.)

There is a fundamental difference between the concepts of continuity and uniform continuity. The first is based on the proximity between a point and a set, the second on the proximity between two sets refers to topology, and the proximity between a set refers to geometric proximity, a more “subtle” science than topology. To understand this difference, let's give just one example. From a topological point of view, a branch of a hyperbola and its asymptote cannot be distinguished from a pair of parallel lines (any point of the hyperbola is not close to its asymptote).

*) The definition of proximity given here was first proposed by the author of this article in 1936. The concept of proximity can be defined axiomatically, without using distance, and the entire topology can be built on its basis. (Moreover, ed.)

⟦folio 24⟧

Otte!), while these two pairs of objects are not the same in the geometry of proximity (asympotate is close to a hyperbola!).

Proof of the equivalence of definitions of continuity

Let the mapping $f: X \rightarrow Y$ be continuous at the point $a$ according to Cauchy, where $X, Y$ are figures for which the distance between points is defined, which has a general property. Then for each $\varepsilon > 0$ there is a positive number $\alpha = \alpha(\varepsilon)$, depending on $\varepsilon$, such that $ax < \alpha$ implies $a'x' < \varepsilon$. Let the part $B \subset X$ be close to $a$; this means for every $\alpha > 0$ in $B$ there is a point $x$ such that $ax < \alpha$. If $\alpha = \alpha(\varepsilon)$, then $a'x' < \varepsilon$, and since $\varepsilon$ is arbitrarily small, then $B' = f(B)$ is close to $a' = f(a)$ ($B\delta a \Rightarrow b'\delta a'$).

Suppose, on the contrary, that $f$ satisfies the first definition of continuity.

Numbers and functions
(See beginning on p. 12)

It follows from equality (9) that and $PQ' : Q$. But since $(P, Q) = 1$, then $Q' : Q$. Therefore, the degree $Q$ is not higher than the degree $Q'$. The latter is only possible if $Q$ is a constant. It also follows from (9) that $P$ is a constant. But then $r_0 = P/Q$ is a constant. When constructing $r_0$, equality (8) takes the form $nr_0 = 0$, $r_0 \neq 0$. And since $n \geq 1$, this equality is contradictory. The theorem has been proven.

Exercise 11. a) Prove the transcendence of the function
$y = \sin x; y = \sqrt{e^x} + 1$.

6) Give examples of transcendental functions $f$ and $g$ such that $f + g, fg, f(g(x))$ are not transcendental.

b) Prove that if $f$ and $g$ are transcendental functions, then at least one of the functions $f + g$ and $fg$ is also transcendental.

At the end of § 2 we tried to find some connection between the irrationality of a function and the irrationality of its values ​​- and failed completely. After this, it will probably no longer occur to anyone to look for a connection between the transcendence of a function and the transcendence of its values. To finally remove all doubts, it is enough to consider the function whose graph is shown in figure 5. This transcendental function, however, takes not only algebraic, but even rational values ​​for all rational values ​​$x$ (prove the listed properties of this function yourself).
