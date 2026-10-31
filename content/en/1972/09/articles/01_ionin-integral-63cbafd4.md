---
id: 1972-9-ionin-integral-63cbafd4
issue: kvant_1972_9
year: 1972
number: "9"
title: Integral
authors:
  - Ионин Ю. И.
rubric: osnovnye-stati
page_first: 4
page_last: 8
page_labels: 2, 4, 6
tag: K3ES
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8d369a8ba75942a4b00e1ea3e749454c2f9c08ca738acd669ca642f06f28b55f
prompt_sha256: draft-1
translated_from: content/ru/1972/09/articles/01_ionin-integral-63cbafd4.md
source_content_sha256: cb79b150ef03a4306d0004a5d40d211d856c7c2ac9bff257c1c58f708e6ceb74
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

This article talks about one of the most important mathematical concepts - integral. Using this concept, you can solve a variety of geometric and physical problems.

Note that according to the new program, integral calculus will be studied in a high school course.

You can learn more about integral calculus in the book by B. E. Weizza, I. T. Demidav “Algebra and the beginnings of analysis” (trial textbook for grade 10, edited by academician A. N. Kolmogorov). However, it is presented from several perspectives.

When you have encountered the concept of a function so far, it has most often been suggested that the domain of a function consists of numbers.

For example, the function $x \rightarrow \frac{\sqrt{x+2}}{x-3}$ is defined on the set of numbers satisfying $x \geq -2$ and $x \neq 3$, and the function $x \rightarrow \sqrt{1g\cos 2\pi x}$ is defined on the set of integers.

However, no less important are functions whose domain of definition consists not of numbers, but of a set lying on a straight line, in a plane or in space. For example, area can be considered as a function that is defined on a set of planar funcures. This function assigns the number $ab$ to the circle of radius $a$ and $b$, and the number $\pi R^2$ to the circle of radius $R$. If some law of motion of a point is given, then we can consider a function that associates each time interval with the path traveled during this interval; the domain of definition of this function consists of time intervals.

Both considered functions can be said to have the property of aditivity (from the Latin addo - I add): if a function is divided into several parts, then its area is equal to the sum of the areas of these parts; if a period of time is divided into several parts, then the sum of the paths traveled for each of these parts turns out to be equal to the paths traveled during the entire interval.

Physics provides many examples of additive functions.

If the movement of a material point is given, occurring under the influence of a certain force, then it is possible to assign to each segment of the trajectory a correspondence to the work of the force to move the point, performed on this segment. This is an additive function.

Mass, energy, body energy are also additive functions *).

To study additive functions based on the successes of the great scientists of the 17th-18th centuries, first of all

*) The aditivity of mass was discussed in detail in the article by Ya. A. Smorodinsky in «Kvant» No. 3, 1972.

⟦folio 4⟧

Fig. 2.

the mass was distributed “almost evenly”, in other words, the density of the rod at the points of each such segment should differ little from the average density of the rod on this segment.

The average density of the rod on the segment $[a, b]$ is equal to $\frac{m[a, b]}{b-a}$. A similar concept is easy to introduce for an arbitrary interval function. The average density of the interval function $T$ on the segment $[a, b]$ (at $a \neq b$) is the number $\frac{T[a, b]}{b-a}$.

It is much more difficult to give a definition of density “at a point”, and we will not give it here also because we will need only one property of this “point” density. To formulate this property, it is convenient to introduce some notation. If the segment $[a, b]$ is included in the domain of definition of the numerical function $f$, then by the symbols $\min f$ and $\max f$ we will denote, respectively, the smallest and greatest values ​​of the function $f$ on this segment. What is really interesting about the densities is the following. If the numerical function $f$ is the density of the interval function $T$, then the average density of the interval function $T$ on each segment $[a, b]$ is contained between the numbers $\min f$ and $\max f$ (Fig. 2), that is, the inequality holds

$$\min f \leqslant \frac{T[a, b]}{b-a} \leqslant \max f,$$

(3)

which can be rewritten like this:

$$(b-a) \min f \leqslant T[a, b] \leqslant \leqslant (b-a) \max f.$$

Let us assume that for a given function of the number $f$ we managed to select such an additive function of the interval $T$ that inequality (3) is satisfied on each segment from the domain of definition of the function $T$. However, is the interval function $T$ defined by this? One can think of an example of a “bad” numerical function $f$, for which the additive function of the interval $T$ is not uniquely determined by inequalities (3). However, an example is given in Exercise 4. But for any sufficiently “good” function $f$, for example, for any multi-otonic function, there is only one additive function of the interval $T$, the values ​​of which on each interval $[a, b]$ satisfy inequality (3). The same statement is true for piecewise monotonic functions $f$, that is, for a function that has monotonicity on segments. Piecewise monotone are power, exponential, logarithmic, trigonometric and many other functions.

We have come to the definition of the integral.

Definition. Let the function of the number $f$ be defined on the interval $[A, B]$. An additive function of the interval $T$, defined on the set of segments $[a, b]$ contained in the segment $[A, B]$, is called an integral of the function $f$, if for each segment $[a, b]$ the inequality

$$(b-a) \min f \leqslant T[a, b] \leqslant \leqslant (b-a) \max f.$$

Thus, the integral of a numerical function is an additive function of the interval $T$ uniquely determined.

⟦folio 6⟧

This interraal is 0.333. We will find the exact purpose of this interal in the next paragraph. As you may have agreed, it is equal to $1/3$.

And in a more general case, it is possible, by dividing the segment $[a, b]$ into sufficiently small parts, to approximate $\int \limits_a^b f(x) dx$ with a sum of the form
$$f(x_1)(a_1 - a) + f(x_2)(a_2 - a_1) + \dots + f(x_n)(b - a_{n-1})$$
where $a_1, a_2, \dots, a_{n-1}$ are points dividing the segment $[a, b]$ into parts, $x_1, x_2, \dots, x_n$ are points from these parts. This approximation can be made as accurate as desired.

The amount written above is called interral. Obviously, by definition, an interral is the limit to which the interral sum tends as the partition becomes increasingly finer. In our definition of an interval, the concept of limit is not used. From interral sums the designation of interal was also derived. The symbol $\int \limits_a^b f(x) dx$ is like this: “interral from a to be ef from x to de x.” The function $f$ is called subinterral, the numbers $a$ and $b$ are the lower and upper limits of interiorization, respectively. It should be borne in mind that just as $x \rightarrow x^2, t \rightarrow t^2, z \rightarrow z^2$ is the same function, the symbols $\int \limits_a^b f(x) dx, \int \limits_a^b f(t) dt, \int \limits_a^b f(z) dz$ denote the same number - the value of the interval of the function $f$ on the segment $[a, b]$.

§ 4. Integration formulas

Calculating interrals using interral sums is quite a troublesome task, and the result is approximate. Instead, they do this: they calculate several standard, frequently encountered inter- rals, and try to reduce other inter- rals to them. We will calculate two standard intervals

$$\int \limits_a^b x_n dx \quad \int \limits_a^b \cos x dx \quad \text{и установим некоторые теоремы, позволяющие своить ряд интерралов к стандартным.}$$

1° Calculation $\int \limits_a^b x^n dx$.

Consider the interval function $T$ given by the formula
$$T[a, b] = \frac{b^{n+1} - a^{n+1}}{n+1}.$$

This function is additive:
$$T[a, b] + T[b, c] = \frac{b^{n+1} - a^{n+1}}{n+1} + \frac{c^{n+1} - b^{n+1}}{n+1} = \frac{c^{n+1} - a^{n+1}}{n+1} = T[a, c].$$

Let us prove that $T$ is an integral of the numerical function $x \rightarrow x^n$. To do this, we need to establish that on each segment $[a, b]$ the inequality $(b - a) \min x^n \leq T[a, b] \leq (b - a) \max x^n$ holds. Let us check this inequality for non-negative $a$ and $b$. In this case $\min x^n = a^n$, $\max x^n = b^n$, so we need to prove that
$$(b - a) a^n \leq \frac{b^{n+1} - a^{n+1}}{n+1} \leq b^n (b - a)$$
or
$$(n + 1) a^n (b - a) \leq b^{n+1} - a^{n+1} \leq (n + 1) b^n (b - a).$$

Expanding $b^{n+1} - a^{n+1}$ into a set and canceling by $b - a > 0$, the last inequality can be rewritten as
$$a^n + a^n + \dots + a^n \leq b^n + b^n + \dots + b^n.$$

This inequality is valid since the terms in its middle part are no less than the terms on the left side and no more than the terms on the right side.

Thus, the additive function of the interval $T$ is an integral.
