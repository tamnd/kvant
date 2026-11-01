---
id: 1986-3-faddeev-sokolovskiy-o-kasatelnoy-k-grafiku-funktsii-c8b1818f
issue: kvant_1986_3
year: 1986
number: "3"
title: About the tangent to the graph of a function
authors:
  - Фаддеев Д. К.
  - Соколовский И. Ф.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 19
page_last: 20
page_labels: 17-18
tag: 7YK4
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2a0a663964ed2d49878222d9c1b2a3f39b0bfc32222693951b516c2445f8f260
prompt_sha256: draft-1
translated_from: content/ru/1986/03/articles/07_faddeev-sokolovskiy-o-kasatelnoy-k-grafiku-funktsii-c8b1818f.md
source_content_sha256: e5dc254dcea3845dd07b12e37b90f1daaa2d673b041fc5a9daf77c14c01b3870
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 17⟧

About the tangent to the graph of a function

Corresponding Member of the USSR Academy of Sciences
D. K. FADDEYEV,
I. F. SOKOLOVSKY

The main goal of this article is to clearly explain how the tangent to the graph of a differentiable function differs from other lines passing through the point of tangency. It turns out that the answer to this question not only clarifies the geometric meaning of the tangent, but allows you to find its equation without calculating the derivative function.

The tangent to the graph of the function $y = f(x)$ at the point $M(x_0; f(x_0))$ is most often defined as the limiting position of the secant $MN$, when the point $N$ indefinitely approaches the point $M$, moving along the graph of the function (Fig. 1). From this definition the well-known tangent equation is derived (“Algebra and the beginnings of analysis”, paragraph 23)

$$y = f'(x_0)(x - x_0) + f(x_0),$$

(1) where $f'(x_0)$ is the value of the derivative $f'$ of the function $f$ at $x = x_0$. This formula is valid under the assumption that the function $f$ has a derivative at the point $x_0$.

The question may arise: “Why is so much attention removed from the understandable tangent? Why is the tangent at the point $(x_0; y_0)$, where $y_0 = f(x_0)$, “better” than other lines passing through this point?” Indeed, in the general case, one cannot even say about a tangent to the graph of a function (by analogy with a tangent to a circle) that it has a single common point with the graph of the function. Further, a tangent to the graph of a function can intersect the graph, moving from one side of the graph to the other, precisely at the point of tangency; for example, this is the behavior of the tangent to the graph of the function $y = x^3$ at the point $(0; 0)$, or the tangent to the graph of the function $y = x^3 - 3x^2$ at the point $(1; -2)$. And the tangent to the graph of the function $y = x^4$ sin $(1/x)$ intersects the graph an infinite number of times.

So, how do we apply the tangent to the graph of the function $y = f(x)$ at the point $(x_0; y_0)$? It turns out that in a sufficiently small neighborhood of the point of tangency, the tangent belongs to the graph of the function more closely than any other line passing through the point of tangency. Let's look at this in more detail.

Let $y = f(x)$ be a given function that has a derivative $f'(x_0)$ at a given point $x_0$. The equation of an arbitrary inclined line passing through the point $(x_0; y_0)$ has the form $y = k(x - x_0) + y_0$. For $k = f'(x_0)$ we obtain the equation of the tangent to the graph of the function $y = f(x)$ at point $(x_0; y_0)$. The ordinate of a point on the graph.function $y = f(x)$ differs from the ordinate of the corresponding point on the line to the vertex

$$\varepsilon = f(x) - (k(x - x_0) + f(x_0)) = f(x) - f(x_0) - k(x - x_0) = (x - x_0) \left( \frac{f(x) - f(x_0)}{x - x_0} - k \right).$$

By introducing the notations $x - x_0 = \Delta x$ and $f(x) - f(x_0) = \Delta f(x_0)$, this expression can be written more briefly:

$$\varepsilon = \Delta x \cdot \left( \frac{\Delta f(x_0)}{\Delta x} - k \right).$$

If $k = f'(x_0)$, that is, in the case of a tangent, at $\Delta x \to 0$ we have $\frac{\Delta f(x_0)}{\Delta x} \to f'(x_0)$ and, therefore, each component on the right side of the equality tends to zero.

Fig. 1.

⟦folio 18⟧

If $k \neq f'(x_0)$, then $k = f'(x_0) + c$, where $c$ is some constant that is not equal to zero. Then

$$\varepsilon = \Delta x \left( \frac{\Delta f(x_0)}{\Delta x} - f'(x_0) - c \right).$$

For $\Delta x \to 0$, the second factor on the right side of the equality tends to $c \neq 0$. Thus, at $\Delta x \to 0$, a point on the tangent approaches the corresponding point on the graph faster than a point with the same abscissa on a line other than the tangent.

What is especially important is that the tangent fits against the curve not just quantitatively better than other straight lines, but in a certain sense “an order of magnitude better.” Let's explain this.

Let us rewrite the expression for $\varepsilon$ in the case of $k \neq f'(x_0)$ in the form

$$\varepsilon = \Delta x \left( \frac{\Delta f(x_0)}{\Delta x} - f'(x_0) \right) - c \Delta x.$$

From this writing formula it is clear that in the case when the straight line differs from the tangent, the difference between the ordinates of the corresponding points on the straight line and on the graph of functions contains a term proportional $\Delta x$, that is, the form $c \cdot \Delta x$, where $c$ is a constant, but in the case of approaching along a tangent, the distance between the point on the straight line and the corresponding point on the graph decreases “an order of magnitude faster” than $\Delta x$ itself, that is has the form $\gamma \cdot \Delta x$, where $\gamma$ is a variable tending to zero together with $\Delta x$. Thus, among all the lines passing through a point on the graph of a function, only the tangent differs from the function by an amount that does not contain a linear term with respect to $\Delta x$.

This property of a tangent is the feature that distinguishes it from the entire family of lines passing through the point of tangency. It fully characterizes the tangent and therefore can be used as the basis for the definition of the tangent; then the derivative of a function at a point can be defined as the slope of the tangent to the graph of the function at that point. The derived property of the tangent justifies the method of obtaining the equation of the tangent through approximate equalities estimating the value of the magnitude function from the point of tangency. Let's show the application of this method with examples. (In what follows, $\Delta x$ will be denoted by the letter $\alpha$.)

Example 1. Let us write the equation of the tangent to the graph of the function $f(x) = x^2 - 3x - 6$ at the point $x_0 = -1$.

Solution e. Let $x = -1 + \alpha$, where $|\alpha|$ is close to zero. Then $f(-1 + \alpha) = (-1 + \alpha)^2 - 3(-1 + \alpha) - 6 = 1 - 2\alpha + \alpha^2 + 3 - 3\alpha - 6 = -5\alpha + \alpha^2 - 2$. Transforming $\alpha^2$, we get $f(-1 + \alpha) \approx -5\alpha - 2$. Let's return to the old notation; we get $f(x) \approx -5x - 7$ magnitude $x_0 = -1$. Taking $y = -5x - 7$ the magnitude $x_0 = -1$ differs from $f(x)$ by a value that does not contain the linear relative $\alpha$ term, and only the tangent has this property, which means $y = -5x - 7$ is the equation of the tangent to the graph of this function at the point $x_0 = -1$. (Check this result by obtaining the tangent equation using formula (1).)

Example 2. Let us derive the equation of the tangent to the graph of the function $f(x) = x^2$ at an arbitrary point $x_0$.

Solution e. Let $x = x_0 + \alpha$, where $|\alpha|$ is close to zero. Then $f(x_0 + \alpha) = x_0^2 + 2x_0\alpha + \alpha^2$. We transform $\alpha^2$ and get $f(x_0 + \alpha) \approx x_0^2 + 2x_0 \times (x - x_0) = x_0^2 + 2x_0x - 2x_0^2 = 2x_0x - x_0^2$. Taking $y = 2x_0x - x_0^2$ tangent to the graph of the function at point $x_0$, the slope of tangent $2x_0$ is the derivative of $x^2$ at point $x_0$.

The derivation of the tangent equation becomes especially simple in the case when the expression defining the function $f(x)$ contains linear factors of the form $(x - x_0)$.

Example 3. Let's write the equation of tangents to the graph of the function

$$y = (x - x_0)(x - x_1)(x - x_2)$$

at the points of intersection of the graph with the abscissa axis.

Solution e. Let $x = x_0 + \alpha$, $y = \alpha(x_0 - x_1 + \alpha)(x_0 - x_2 + \alpha)$. It is clear that when opening the brackets of the term, the linear relative $\alpha$ has the form $\alpha(x_0 - x_1)(x_0 - x_2)$, then

$$y = (x - x_0)(x_0 - x_1)(x_0 - x_2)$$

is the equation of the tangent to the graph of the function at the point $x_0$. Similarly, we obtain the equation for the tangents at points $x_1$ and $x_2$:

$$y = (x - x_1)(x_1 - x_0)(x_1 - x_2),$$

$$y = (x - x_2)(x_2 - x_0)(x_2 - x_1).$$

Let us show specific examples in which it is necessary to find the equation of the tangent at the point $x_0$.
