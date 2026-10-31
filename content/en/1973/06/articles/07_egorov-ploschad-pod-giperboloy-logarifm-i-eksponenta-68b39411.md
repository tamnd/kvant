---
id: 1973-6-egorov-ploschad-pod-giperboloy-logarifm-i-eksponenta-68b39411
issue: kvant_1973_6
year: 1973
number: "6"
title: Area under a hyperbola, logarithm and exponent
authors:
  - Егоров А. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 32
page_last: 40
page_labels: 30, 31, 32, 34, 36, 38
tag: HOPC
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4420395ab555cf99321f495d101a0c17b4ebd5b77af666e6c261bada73bd14f4
prompt_sha256: draft-1
translated_from: content/ru/1973/06/articles/07_egorov-ploschad-pod-giperboloy-logarifm-i-eksponenta-68b39411.md
source_content_sha256: 68280c9140ddf60c9fdcac91d25e8cc07632bfd85813ae1daaadb811489a7063
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

1. Introduction.
Definition of logarithm

The exponential function $x \rightarrow a^x$ is studied in school after several generalizations of the operation of raising to a power: first, a degree with a natural exponent is determined, then with a rational exponent, and finally with an irrational exponent. The logarithm is then defined as the inverse of the exponential function.

We'll do it right: we'll start right away with the definition of the logarithm, and then move on to the inverse function - the “exponent”. The definition that we are now giving makes it possible to study the basic properties of these functions and obtain estimates that are especially important for physical applications, as well as to demonstrate one of the frequently used methods in mathematics for constructing new functions using already known ones.

Such a well-known function will serve us as the function $x \rightarrow \frac{1}{x}$, the graph of which $y = \frac{1}{x}$ is the familiar hyperbola.

Definition. Let $b$ be a positive number. Let us denote by $\ln b$ the number whose model is equal to the area of the function limited by the graph of the function $y = \frac{1}{x}$, the abscissa axis $y = 0$ and the lines $x = 1$ and $x = b$, and the sign is flat if $b > 1$ (Fig. 1, a), and minus if $b < 1$ (Fig. 1, b); if $b = 1$, then $\ln b = 0$.

The function $b \rightarrow \ln b$ is called the natural logarithm.

We soon see that $\ln b$ real is the logarithm of the number $b$ to the base $e$, where $e = 2,71828\dots$ is a substitute mathematical constant, which was already discussed in «Kvant» (see the article by L. G. Limenov “On the number $e$ and $n$” in No. 5 for 1972).

For those who are familiar with the understandable integral (for example, according to the article by Yu. I. Ionin in «Kvant» No. 9), our definition of the logarithm can be formulated as follows:

$$\ln b = \begin{cases} \int \frac{1}{x} dx, \text{ если } b > 1, \\ 0, \text{ если } b = 1, \\ -\int \frac{1}{x} dx, \text{ если } 0 < b < 1. \end{cases}$$

We will sometimes refer to the articles “On the number $e$” and “Integral”, but only for comparison: the reader is not required to have prior knowledge of it. A reader who would like to follow all the arguments in detail and strictly and solve problems (and they contain a significant part of the content of the article) will need knowledge of the basic properties of real numbers *). However, Sta-

*) See, for example, the trial textbook by B. E. Weizza and I. T. Demidov “Algebra and the beginnings of analysis”, 9th grade, M., “Prosveshchenie”, 1969.

⟦folio 31⟧

Fig. 1.
It is written, if possible, in such a way that the basic facts concerning the properties of the logarithm and exponent can be understood, using only naive ideas about real numbers, continuity, limit, etc., without delving into the subtleties associated with strict definitions of these concepts.

2. Square
One of the concepts that should be strictly defined is the concept of area. Indeed, we need to explain what we mean by the area of ​​a “curvilinear trapezoid” (see Fig. 1). After all, at school we only talk about the areas of a polygon, a circle and its parts, and our trapezoid is limited on one side by a hyperbola.

Here we will limit ourselves to the replacement that area is a function, which can be defined on a sufficiently wide class of functions (this class includes polygons, and all convex bounded functions, and our “trapezoid”) so that the conditions are satisfied:

1) the area of ​​any function is a non-negative number;
2) the areas of equal (congruent) functions are equal;
3) if a function is cut into two parts, for each of which the area is determined, then the sum of these areas is equal to the area of ​​all functions;

Fig. 2.
4) the area of ​​the rectangle on the sides $a$ and $b$ is equal to $ab$.

We will not describe the class of functions for which such a function $S$ can be defined, but we will prove that by conditions 1–4 the area $S$ of the “curvilinear trapezoid” $a \leq x \leq b$; $0 \leq y \leq \frac{1}{x}$ (Fig. 2) is uniquely determined.

To do this, we divide the segment $[a, b]$ into $n$ equal parts and construct two “stairs” - step functions consisting of rectangles with bases $\frac{b-a}{n}$ on the axis $Ox$, one of which contains our curvilinear trapezoid, and the other is contained in it (Fig. 2). Let $S'_n$ and $S''_n$ be the areas of these “stairs” $^*$). It is clear that $S'_n < S < S''_n$. On the other hand, it is clear that

$$S''_n - S'_n = \frac{b-a}{n} (a^{-1} - b^{-1}),$$

that is, for a sufficiently large $n$, the difference between $S''_n$ and $S'_n$ can be made arbitrarily small. Therefore, there is only one number $S$, contained between $S'_n$ and $S''_n$ for all $n$ (it also follows that both sequences $S'_n$ and $S''_n$ approach $S$ as $n$ increases, that is, that $S$ is their common limit).

*) We can determine these areas using conditions 3 and 4.

⟦folio 32⟧

3. The main property of the natural logarithm

This property is expressed by the formula

$$\ln x_1 x_2 = \ln x_1 + \ln x_2$$

(1)

(at $x_1 > 0$ and $x_2 > 0$)

and means that the natural logarithm of the product is equal to the sum of the natural logarithms of the factors.

Before proving formula (1), let us establish one important property of curvilinear trapezoids for functions $y = \frac{1}{x}$.

Let us denote by $S[A, B]$ the area of ​​a curved trapezoid with vertices $A, B$ (Fig. 3). Then, if $b > a > 0$ and $k$ are arbitrary positive numbers, then (Fig. 4)

$$S[a, b] = S[ka, kb].$$

(2)

To prove this, let us consider a transformation of the plane, which consists of stretching by a factor of $k$ from the axis $Oy$ and skating by a factor of $k$ to the axis $Ox$, that is, a transformation that takes the point $(x, y)$ to the point $(kx, \frac{y}{k})$ (Fig. 5). It's easy to see that this is a conversion by:

$$\int_a^b \frac{1}{x} \, dx = \int_k^a \frac{1}{x} \, dx.$$

⟦folio 34⟧

5. Exhibitor

It can be proven that the function we studied in the previous paragraphs takes all real values ​​*). In this case, each value is taken, of course, exactly once, that is, for any $x$ the equation $\ln y = x$ has a unique solution. For the number $y$, which is a solution to this equation, the notation is accepted

$$y = \exp x.$$

The resulting new function $x \rightarrow \exp x$, the inverse of function $x \rightarrow \ln x$, is called an exponential.

Note that by definition of exponent the equality

$$\exp (\ln x) = \ln (\exp x) = x.$$ (6)

The graph $y = \exp x$ is symmetrical to the graph $y = \ln x$ with respect to the straight line $y = x$. In fact, since $y = \exp x$ is equivalent to $\ln y = x$, the graph of the exponent is obtained from the graph of the logarithm by transforming the plane, in which the point $(x, y)$ goes to the point $(y, x)$, and this transformation is symmetry with respect to the straight line $y = x$ (Fig. 8**)).

*) We will not prove this, but note that it is almost obvious “from continuity messages.” A rigorous proof of this fact can be carried out in approximately the same way as the proof of the existence of $\sqrt{a}$ for any $a \geq 0$.

**) In order to verify the correctness of this figure, you should prove that $\ln x < x$ for all $x > 0$.

Thus, the exponent is an increasing function defined on the entire number line $-\infty < x < +\infty$ and taking positive values. In addition, the exponent takes on an appreciably larger value as $x$ increases indefinitely and tends to zero as $x$ tends to $-\infty$.

6. The main property of the exponent

This property is expressed by the following formula:

$$\exp \left( x_1 + x_2 \right) = \exp x_1 \cdot \exp x_2.$$ (7)

To prove it, we will use the main property of the natural logarithm and correspondence (6). Since $\ln y_1 y_2 = \ln y_1 + \ln y_2$, then for $y_1 = \exp x_1$ and $y_2 = \exp x_2$ we get $\ln y_1 y_2 = x_1 + x_2$, that is, $y_1 \cdot y_2 = \exp \left( x_1 + x_2 \right)$ or $\exp x_1 \cdot \exp x_2 = \exp \left( x_1 + x_2 \right)$.

It is easy to deduce from the basic property of exp (or from the corresponding properties of the ln function) that

$$\exp (-x) = \frac{1}{\exp x}$$

And

$$\exp \left( x_1 + x_2 + \dots + x_n \right) = \exp x_1 \cdot \exp x_2 \dots \cdot \exp x_n).$$

Let us denote the number exp1 by $e$. In other words, $e$ is a solution to equation $\ln e = 1$.

Using the main property of the exponential, we prove that for rational $x = \frac{m}{n}$ exp $x = e^x$.

First of all, with natural $m$ exp $m = \exp \left( 1 + 1 + \dots + 1 \right) = \exp 1 \cdot \exp 1 \cdot \dots \cdot \exp 1 = e^m$ and exp $(-m) = \frac{1}{\exp m} = \frac{1}{e^m} = e^{-m}$.

So exp $m = e^m$ for any integer $m$.

In addition, with natural $n$

$$\exp \left( \frac{1}{n} \right)^n = \exp \left( \frac{1}{n} + \frac{1}{n} + \dots + \frac{1}{n} \right) = \exp 1 = e,$$

⟦folio 36⟧

true tangent of the angle of inclination to the Ox axis is equal to (Fig. 9)

$$\text{tg} \alpha = \frac{f(x_1) - f(x_0)}{x_1 - x_0}.$$

When the point $x_1$ approaches $x_0$, the secant tends to its limit position - the tangent drawn to the curve $y = f(x)$ at the point $x_0$. Thus, the value of the arbitrary at $x = x_0$ is equal to the slope of the tangent to the graph at point $(x_0, f(x_0))$.

Let's try to calculate the “instantaneous” rate of change for the function $f(x) = \ln x$. Its increment on the segment $[x_0, x_1]$ is equal to

$$\ln x_1 - \ln x_0 = \ln \frac{x_1}{x_0} = \ln \left(1 + \frac{x_1 - x_0}{x_0}\right),$$

pose

$$\frac{\ln x_1 - \ln x_0}{x_1 - x_0} = \frac{1}{x_0} \cdot \frac{\ln(1 + h)}{h},$$

Where

$$h = \frac{x_1 - x_0}{x_0}.$$

When $x_1$ tends to $x_0$, the quantity $h$ tends to 0. Thus, it remains to be seen how the ratio $\frac{\ln(1 + h)}{h}$ behaves for small $h$.

From our definition of the logarithm, as we will soon see, estimates are easily obtained from which it follows that as $h$ approaches zero, the value $\frac{\ln(1 + h)}{h}$ approaches 1, that is

$$\ln(1 + h) \approx h \text{ (при малых } h).$$

This formula, which is important for approximate calculations, can also be rewritten as follows:

$$\exp h \approx 1 + h \text{ (при малых } h).$$

From here we derive the basic formulas for the rate of change of the logarithm and exponent:

$$(\ln x)' = \frac{1}{x}$$

And

$$(\exp x)' = \exp x.$$

9. Estimates of the natural logarithm of the magnitude of units

Here is one of the main properties of the logarithm:

$$\left| x - \frac{x^2}{x+1} \right| = \left| \frac{x}{x+1} \right| < \left| \ln(1+x) \right| < |x|.$$

To prove these inequalities for $x > 0$, it is sufficient to compare the area of ​​the curved trapezoid $ABCD$ with the areas of two straight lines $AD'CB$ and $ADC'B$ (Fig. 10). Indeed, the area of ​​a curved trapezoid is equal to $\ln(1+x)$, the area of ​​$AD'CB$ is equal to

⟦folio 38⟧

terms

$$e^x = 1 + x + \frac{x^2}{1 \cdot 2} + \dots + \frac{x^k}{1 \cdot 2 \cdot \dots k} + \dots$$

(16)

just as the infinite geometric progression $1 + x + x^2 + \dots$ is represented at $|x| < 1$ by the function $y = \frac{1}{1-x}$.

This representation is convenient for two reasons. Firstly, to calculate the exponent with high accuracy (for example, when compiling a table) using the formula $e^x \approx 1 + x + \frac{x^2}{2!} + \dots + \frac{x^n}{n!}$, a relatively small number of terms is enough and, secondly, this expansion will allow you to study the exponent in more depth (for example, to prove the irrationality of the number $e$ (see problems 11, 12).

We will limit ourselves to proving formula (16) for $x > 0$.

So let $T_n(x) = \left(1 + \frac{x}{n}\right)^n$ and $S_n(x) = 1 + x + \frac{x^2}{1 \cdot 2} + \dots + \frac{x^n}{n!}$. We must prove that

$$\lim S_n(x) = \exp x.$$

Using the binomial formula we get

$$\left(1 + \frac{x}{n}\right)^n = 1 + n \cdot \frac{x}{n} + \frac{n(n-1)}{1 \cdot 2} \frac{x^2}{n^2} + \dots + \frac{x^n}{n!} = 1 + x + \frac{\left(1 - \frac{1}{n}\right) x^2}{1 \cdot 2} + \dots + \frac{\left(1 - \frac{1}{n}\right) x^k}{1 \cdot 2} + \dots + \frac{x^n}{n!}.$$

The numbers on the right side of this equality in parentheses are all less than one. If they are replaced by units, then the right side increases
38
