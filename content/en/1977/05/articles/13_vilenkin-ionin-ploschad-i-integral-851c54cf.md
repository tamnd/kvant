---
id: 1977-5-vilenkin-ionin-ploschad-i-integral-851c54cf
issue: kvant_1977_5
year: 1977
number: "5"
title: Area and integral
authors:
  - Виленкин А. Н.
  - Ионин Ю. И.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 32
page_last: 36
page_labels: 30-34
tag: DNDN
lang: en
source: kvant_digital
extraction: vision
content_sha256: 878a3db0856e9a59eb750541e566f66f5050b3ecc90e2b844b4cc52030025feb
prompt_sha256: draft-1
translated_from: content/ru/1977/05/articles/13_vilenkin-ionin-ploschad-i-integral-851c54cf.md
source_content_sha256: cb171571682ad124f9e2df7fdf500815f322895cea91cbc7427b7223de85ac04
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 30⟧

Area and integral

From the article by V. Boltyansky “On the concepts of area and volume,” published in this issue, you learned about the definition and various methods of calculating areas. The most universal of them is the use of integral calculus. This method will be discussed in this article (it is intended for tenth graders). But first, we advise you to look at the textbook “Algebra and the beginnings of analysis 10” and look again at paragraphs 97-102 and the table of antiderivatives on p. 219.

Area is an integral

Consider a curved trapezoid on figure 1. This figure is bounded by the graph of a continuous non-negative function $y = f(x)$, defined on the segment $[a; b]$, lines $x = a, x = b$ and the x-axis $y = 0$. Its area $S$ is equal to

$$F(b) - F(a),$$

where $F$ is some antiderivative for the function $f$ (“Algebra and Principles of Analysis 10”, p. 100). Remembering the definition of an integral (“Algebra and Na-

beginning of analysis 10", paragraph 101), the formula for calculating the area can be rewritten as follows:

$$S = \int_{a}^{b} f(x) dx.$$

Example 1. The largest area of ​​the figure is limited by the x-axis, straight lines $x = -1, x = 1$ and the graph of the function $y = 1 - x^2$ (Fig. 2), therefore, according to formula (1), its area

$$S = \int_{-1}^{1} (1 - x^2) dx.$$

Since the antiderivative for the function $f(x) = 1 - x^2$ is the function

$$F(x) = x - \frac{x^3}{3},$$

That

$$S = \left( x - \frac{x^3}{3} \right) \bigg|_{-1}^{1} = \frac{4}{3}.$$

You see that in this example we didn’t have to resort to any tricks; To solve the problem, it turned out to be enough to use ready-made formulas. But this is not always the case.

Aditivity

The `addumивности` area property helps solve more complex problems involving calculating areas. It “allows” to break a given figure into parts and calculate the area of ​​the entire figure as the sum of the areas of these parts.

Fig. 1.

Fig. 2.

⟦folio 31⟧

Example 2. Find the area of ​​the figure bounded by the lines $y = x$, $y = 1/x$, $y = 0$, $x = e$.

This figure (Fig. 3) can be considered as a curved nonlinear trapezoid bounded by the x-axis, straight lines $x = 0$ and $x = e$ and a graph of functions, which is on the segment [0; 1] is equal to $x$, and on the interval [1; $e$] is equal to $1/x$. However, it is impossible to write a transform for such a function.

Posibly we divide the nonlinear trapezoid given by the curve $x = 1$ into two parts (Fig. 3). Their areas are immediately found using formula (1):

$$S_1 = \int_0^1 x dx, \quad S_2 = \int_1^e \frac{1}{x} dx.$$

Since the transform for the functions $f_1(x) = x$ is the function $F_1(x) = x^2/2$, and the transform for the functions $f_2(x) = 1/x$ is (for $x > 0$) the function $F_2(x) = \ln x$, then

$$S_1 = \int_0^1 x dx = \frac{x^2}{2} \bigg|_0^1 = \frac{1}{2},$$

$$S_2 = \int_1^e \frac{1}{x} dx = \ln x \bigg|_1^e = 1,$$

and by the property of area aditivity

$$S = S_1 + S_2 = 1 + \frac{1}{2} = \frac{3}{2}.$$

Invariance

For more complex problems, another property of area helps, called relative displacement invariance: congruent functions have equal areas.

Example 3. Find the area of ​​a figure bounded by lines

$$y = \sqrt{x}, \quad y = 2, \quad x = 0.$$

⟦folio 32⟧

The aditivity and invariance of the area not only make it easier to find the area of ​​a curvilinear trapezoid, but also allows you to find the areas of more complex figures, for example, those bounded by the graphs of certain functions and from above, and the blue-area of ​​“bicurvilinear trapezoids”.

Example 4. Find the area of ​​the figure bounded by the lines $y = x^2 + 2, y = 1 - x^2, x = 0, x = 1$.

A curvilinear trapezoid bounded by straight lines $x = 0, x = 1, y = 0$ (x-axis) and the graph of the function $y = 1 - x^2$ complements this figure to a curvilinear trapezoid bounded by straight lines $x = 0, x = 1, y = 0$ and the graph of the function $y = x^2 + 2$ (Fig. 6, a). In other words, the figure given in the conditions can be considered as the difference of two curvilinear trapezoids (Fig. 6, b, θ). Therefore the area

$$S = \int_0^1 (x^2 + 2) dx - \int_0^1 (1 - x^2) dx = \left( \frac{x^3}{3} + 2x \right) \bigg|_0^1 - \left( x - \frac{x^3}{3} \right) \bigg|_0^1 = \frac{7}{3} - \frac{2}{3} = \frac{5}{3}.$$

This reasoning can be easily generalized as follows.

Let $f$ and $g$ be two continuous functions defined on the interval $[a; b]$, and let the inequality $f(x) \geq g(x)$ hold for all $x \in [a; b]$.

Then the area of ​​the figure bounded by the graphs of the function $y = f(x), y = g(x)$ and the lines $x = a, x = b$ (Fig. 7) is equal to

$$S = \int_a^b f(x) dx - \int_a^b g(x) dx.$$

And since the difference between the intervals of two functions (on the same segment) is equal to the interval from their difference (“Algebra and the beginnings of analysis 10”, p. 106), the expression for $S$ can be written as follows:

$$S = \int_a^b (f(x) - g(x)) dx. \tag{2}$$

If $g(x) \geq 0$ at $x \in [a; b]$, then formula (2) is derived in the same way as in example 4. If at some points $g(x) < 0$, then we add to both functions the same constant $k$, which we choose so large that the graphs of the function $y = f(x) + k$ and $y = g(x) + k$ are above the abscissa axis (Fig.8). The figure at figure 7 is obtained from the figure at figure 8 by parallel translation and therefore also has area. Formula (2) is applied to the figure at figure 8:

$$S = \int_a^b \left[ (f(x) + k) - (g(x) + k) \right] dx.$$

But

$$(f(x) + k) - (g(x) + k) = f(x) - g(x).$$

From here we obtain formula (2) for the figure on figure 7.

If the graphs of continuous functions $f$ and $g$, defined on the segment $[a; b]$, intersect, and in places $f(x) > g(x)$, and in places $g(x) > f(x)$ (Fig. 9), then the

⟦folio 33⟧

The structure of the function bounded by the graphs of the functions $f$ and $g$ and the lines $x = a$, $x = b$ is equal to

$$S = \int_{a}^{b} |f(x) - g(x)| \, dx. \tag{3}$$

This formula generalizes formula (2) (prove it yourself).

Example 5. Find the area $S$ of the function contained between the lines $y = x^3 - 3x$ and $y = x$.

These lines intersect at points with coordinates $(-2; -2)$, $(0; 0)$ and $(2; 2)$ (Fig. 10), with $(x^3 - 3x) - x = x^3 - 4x$ and $|x^3 - 4x| = x^3 - 4x$ at $-2 \leq x \leq 0$, $|x^3 - 4x| = 4x - x^3$ at $0 \leq x \leq 2$. Therefore, according to formula (3)

$$S = \int_{-2}^{2} |(x^3 - 3x) - x| \, dx =$$

$$= \int_{-2}^{2} |x^3 - 4x| \, dx = \int_{-2}^{0} (x^3 - 4x) \, dx +$$

$$+ \int_{0}^{2} (4x - x^3) \, dx = \left( \frac{x^4}{4} - 2x^2 \right) \bigg|_{-2}^{0} +$$

$$+ \left( 2x^2 - \frac{x^4}{4} \right) \bigg|_{0}^{2} = 4 + 4 = 8.$$

Noting that the function at figure 10 is symmetrine with respect to the origin, we can obtain a shorter solution to this problem:

$$S = 2 \int_{0}^{2} |(x^3 - 3x) - x| \, dx =$$

$$= 2 \int_{0}^{2} |x^3 - 4x| \, dx = 2 \int_{0}^{2} (4x - x^3) \, dx =$$

$$= 2 \cdot \left( 2x^2 - \frac{x^4}{4} \right) \bigg|_{0}^{2} = 2 \cdot 4 = 8.$$

Calculation of integrals

So far, we have used integral calculus to solve a geometric problem - calculating areas. Now we apply the geometric message to the calculation of integrals.

Example 6. Calculate the integral

$$\int_{0}^{1} \sqrt{1 - x^2} \, dx.$$

The graph of the function $y = \sqrt{1 - x^2}$, defined on the segment $[0; 1]$, is a quarter circle of radius 1 s

⟦folio 34⟧

Fig. 11.

centered at the origin (Fig. 11),
Therefore $\int_0^1 \sqrt{1-x^2} \, dx$ is a flat quarter circle of radius 1, so this interval is equal to $\pi/4$.

Example 7. Finding the antiderivative for the function $f$ can be given by the formula

$$F(x) = \int_a^x f(t) \, dt$$

(“Algebra and the beginnings of analysis 10”, paragraph 102).

In this case, let's put $a = 1$, then we need to calculate the interval

$$F(x) = \int_1^x \ln t \, dt.$$

If $x > 1$, then this interval is equal to the area of ​​the function, offset in red by figure 12. Let us reflect it relative to the straight line $y = t$; then it will be displayed in the function (Fig. 13), limited by the lines $t = 0, t = \ln x$ and the graphs of the function $y = x$ and $y = e^t$ (the inverse function of $y = \ln t$). The area of ​​this function according to formula (3) is equal to

$$\int_0^{\ln x} |e^t - x| \, dt.$$

Since $e^t \leq x$ is $0 \leq t \leq \ln x$, we get

$$F(x) = \int_1^x \ln t \, dt = \int_0^{\ln x} (x - e^t) \, dt = (xt - e^t) \bigg|_0^{\ln x} = x \ln x - x + 1.$$

The general form of the antiderivative for the function $f(x) = \ln x$ for $x \geq 1$ is as follows:

$$F(x) = x(\ln x - 1) + C,$$

where $C$ is an arbitrary constant. By differentiating the function $F$, we can verify that it is a real antiderivative for the function $f$, and also for $x \in ]0; 1]$.

Carnot cycle

In a school physics textbook, the formula for efficiency is The Carnot cycle is given without derivation. But using integral calculus, deriving this formula is not too difficult.

To do this, let's calculate the work done by 1 mole of gas in the Carnot cycle. Let us recall that when the volume significant to it changes from $V_1$ to $V_2$, the gas does work that is numerically equal to the area of ​​the curved trapezoid bounded by the graph of the function $p(V)$, the axis $OV$ and the straight lines $V = V_1$, $V = V_2$ (“Physics 9”, paragraph 21), i.e., the integral

$$\int_0^{V_1} p(V) \, dV.$$

The Carnot cycle (Fig. 14) consists of four sections (about the Carnot cycle, see «Kvant», 1977, No. 1).

In section $ab$ there will be an isothermal expansion of gas from volume $V_1$ to volume $V'_1$ at constant temperature
