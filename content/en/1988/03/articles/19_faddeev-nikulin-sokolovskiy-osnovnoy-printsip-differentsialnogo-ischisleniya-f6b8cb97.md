---
id: 1988-3-faddeev-nikulin-sokolovskiy-osnovnoy-printsip-differentsialnogo-ischisleniya-f6b8cb97
issue: kvant_1988_3
year: 1988
number: "3"
title: Basic principle of differential calculus
authors:
  - Фаддеев Д. К.
  - Никулин М. С.
  - Соколовский И. Ф.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 48
page_last: 51
page_labels: 46-49
tag: FA5R
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4bb05fbf7737923895d204529b76a42b4647e3f2caa8de1bbb155e3b96bc3417
prompt_sha256: draft-1
translated_from: content/ru/1988/03/articles/19_faddeev-nikulin-sokolovskiy-osnovnoy-printsip-differentsialnogo-ischisleniya-f6b8cb97.md
source_content_sha256: 55d2bed68dc901a160f429e73c80427eb796d7ba44af3409993402af006aa4c8
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

Basic principle of differential calculus

Part I:
Linear function

Corresponding Member of the USSR Academy of Sciences
D. K. FADDEYEV,
Candidate of Physical and Mathematical Sciences
M. S. NIKULIN,
I. F. SOKOLOVSKY

In this article, the author wanted to confirm the idea that mathematics in its elementary part is the simplest of sciences, since it studies the roughest aspects of reality. This fully applies to the elements of mathematical analysis, the main ideas of which are very simple and clear if they are shown at the intuitive level at which they actually arose. Unfortunately, very

Many results of mathematical analysis, their clear geometric and physical meaning are often sacrificed at the first acquaintance to problems of justification and so-called mathematical structure.

Essentially, the basic idea of ​​"higher mathematics" is the following communication process, which we call the basic principle of differential calculus:

In a small section of any sufficiently “good” curve, it manages to bend a little, and the smaller the section in question, the less. Therefore, a small piece of the linearity curve coincides with a segment of some straight lines, and their closeness becomes more and more perfect as the section of the curve contracts to a certain point. The line that is tighter than the other straight line is pressed against the curve near a given point is called the tangent to the curve at that point. In part, the graph of a fairly “good” function on

⟦folio 47⟧

in a small section is almost linear, and a small change in the functions is almost equal to a small change in the tori of the linear function. In other words, a “good” function is almost linear locally, that is, in an infinitely reduced neighborhood of any value of the argument. The angular coefficient of the tangent to the graph of the functions is called the value of an arbitrary function at the point in question.

The “fundamental principle” is not a theorem and does not contain clear definitions. A sufficiently “good” curve and a “good” function are concepts that can be defined more precisely only after the concept of arbitrary has been taught and formalized. However, rational, power, exponential and logarithmic, as well as trigonometric functions are all “good”. Moreover, the function that arises from the study of natural and technical processes usually turns out to be “good”. The function $|x|$ in the vicinity of zero can be called a “plop”.

In this article, leaving aside the problems of justification, we will obtain the main results of the school course in mathematical analysis, based on the “basic principle” of differential calculus. But before we move on to solving this problem, which is the subject of the second part of this article, we will take a closer look at the linear function. This must be done according to two principles. The first is that the linear function in the school course is studied very early and, as a consequence of this, somewhat simplified and divorced from its most important applications. The second reason is fundamental, it is associated with the special role played by the concept of a linear function in the basic concepts of mathematical analysis.

Definition of a Linear Function

A linear function is a function of the form $y=kx+b$, where $k$ and $b$ are constants. At $k=0$ the function takes a constant value $y=b$. For $b=0$, the function $y=kx$ is called direct proportional, and the parameter $k$ is called coefficient proportional.

Characteristic property of a linear function

This property is as follows: the increment of a linear function is proportional to the increment of the argument.

Indeed, empty $y=kx+b$ is the given function and the empty argument changes from $x_1$ to $x_2$. Let us express the increment of function $\Delta y=y(x_2)-y(x_1)$ through the increment of argument $\Delta x=x_2-x_1$:

$$y(x_2)-y(x_1)=kx_2+b-(kx_1+b)=k(x_2-x_1).$$

Thus, $\Delta y=k\cdot \Delta x$, i.e., indeed, the increment $\Delta y$ of the function $y=kx+b$ is proportional to the increment $\Delta x$ of the argument with a proportional coefficient equal to $k$.

The converse statement is true, namely: if the increment of the function $f(x)$ is proportional to the increment of the argument, then $f(x)$ is a linear function.

Indeed, let us choose (fix) some value $x_0$. Then for any $x$, by virtue of the condition, the equality

$$f(x)-f(x_0)=k(x-x_0),$$

where

$$f(x)=kx-kx_0+f(x_0),$$

i.e. the function looks like:

$$f(x)=kx+b,$$ where $b=f(x_0)-kx_0$ means $f(x)$ is a linear function.

So, we come to the conclusion that the displaced property is possessed by a linear and only a linear function, which is why we call it a characteristic property of a linear function.

Monotonicity of a linear function

At $k>0$ the function $y=kx+b$ is a possibility, at $k<0$ it is decreasing.

Let's prove this for $k>0$; if $x_2>x_1$ is empty, then $y(x_2)-y(x_1)=kx_2+b-(kx_1+b)=k(x_2-x_1)>0$, i.e. $y(x_2)>y(x_1)$, which is what needed to be proved.

Composition of linear functions

A complex function, which is a composition of linear functions, also

⟦folio 48⟧

A linear function with a proportionality coefficient equal to the product of the proportionality coefficients of its constituent functions.

Indeed, let
$$F(x) = f(g(x)) \text{ и } f(x) = k_1 x + b_1, \quad g(x) = k_2 x + b_2.$$
Then
$$F(x) = k_1 (k_2 x + b_2) + b_1 = k_1 k_2 x + k_1 b_2 + b_1 = kx + b,$$
where $k = k_1 k_2, b = k_1 b_2 + b_1$.

Obviously, the statement is true for a complex function composed of any number of linear functions.

Graph of a Linear Function

Theorem. The graph of the linear function $y = kx + b$ is a straight line.

The reader can easily prove this theorem using a similar right triangle. However, it is not difficult to construct a proof without using subdivision theory, relying on the monotonicity of a linear function.

Let $y = kx + b$, and we will consider points on the graph with abscissas $0, x_1, 2x_1, 3x_1, \dots$. Let us show that these points lie on the same line. The idea of ​​the proof is clear from figure 1. All pink triangles are equal, and the sum of the angles at any of the points of the series under consideration is $180^\circ$, since the sum of the acute angles of a right triangle is $90^\circ$, and the third angle at each of the points of the line. Consequently, the hypotenuses of the triangles continue each other and form a straight line. For the same reason, the points of the graph with abscissa $0, x_1/n, 2x_1/n, \dots, nx_1/n$ lie on a straight line, and it coincides with the previous one, or contains a point with abscissa $x_1 = nx_1/n$. The natural number $n$ can be taken as large as possible, so that the found straight line $L$ contains points on the graph with as densely spaced abscissas as possible.

Let us show that all points of the graph lie on the same straight line $L$. Let us assume that point $(x_0, y_0)$ of the graph lies above straight line $L$. (If the point is located below, the reasoning is similar.) Then, as before, we will make sure that on the straight line $L'$ connecting point $(0, b)$ with point $(x_0, y_0)$, the graph points with abscissas $0, x_0/m, 2x_0/m$, ... are located as densely as possible. Thus, under this assumption, the points of the graph of the function $y = kx + b$ would “conjugate” as well as possible the part from the line $L$ to the line $L'$, which is impossible due to the monotonicity of the linear function. So, any point on the graph lies on the previously constructed line.

Conversely, any point $(x_2, y_2)$ of this line belongs to the graph $y = kx + b$. Indeed, the point $(x_2, kx_2 + b)$ is a point on the graph and, by virtue of what has been proven, belongs to a straight line, and since on a straight line not parallel to the ordinat axis there is only one point with the abscissa $x_2$, then $y_2 = kx_2 + b$.

From the theorem proved above it follows that the graph of direct proportionality ($b=0$) is a straight line passing through the origin.

When solving problems, one often has to resort to the converse of the theorem about the graph of a linear function: any straight line that is not parallel to the ordinat axis is the graph of some linear function.

Let's prove it.

Let this line pass through the points $(x_0, y_0)$ and $(x_1, y_1)$, where $x_0 \neq x_1$ (Fig. 2). You can always choose an equation of the form $y = kx + b$, for which the pairs of numbers $(x_0, y_0)$ and $(x_1, y_1)$ will be solved:

$$\begin{cases} y_0 = kx_0 + b, \\ y_1 = kx_1 + b. \end{cases}$$

To do this, it is enough to put
$$k = \frac{y_0 - y_1}{x_0 - x_1}, \quad b = y_0 - \frac{y_0 - y_1}{x_0 - x_1} x_0.$$
Straight line - graph of a linear function
$$y = \frac{y_0 - y_1}{x_0 - x_1} x + y_0 - \frac{y_0 - y_1}{x_0 - x_1} x_0 -$$
passes through points $(x_0, y_0)$ and $(x_1, y_1)$; this is the only line passing through these two points, which means it coincides with this line, which proves our statement.

Application of the characteristic property of a linear function

Example 1. Write the equation of the line $a)$ with slope $k = 3$ passing through the point $(-7, 2)$, $b)$ passing through the point $(-8, -10)$ and $(2, 4)$.

⟦folio 49⟧

Solution. a) Let $M(x, y)$ be an arbitrary point of the desired line; then $\Delta y = y - 2$ and the corresponding increment of the argument is $\Delta x = x + 7$. The equation of the straight line has the form: $y - 2 = 3(x + 7)$.

6) Let's calculate the slope $k = \frac{\Delta y}{\Delta x} = \frac{4 + 10}{2 + 8} = 1,4$.

We have arrived at the previous problem, but we have one “extra” point. We choose any of the two and compose the equation of the straight line, for example, $y - 4 = 1,4(x - 2)$; you could also write $y + 10 = 1,4(x + 8)$.

Example 2. We study the dependence described by the linear function $y = kx + b$; the values ​​of the quantity $x$ are obtained as a result of the change. With what accuracy must changes in quantity $x$ be made in order to calculate the values ​​of quantity $y$ with an accuracy of $\varepsilon$?

Solution. The error in measuring the value $x$ can be considered an increment in the argument $x$, i.e. taken as $\Delta x$. Then, due to the characteristic property of a linear function, the error in determining the value $y$ will be equal to $\Delta y = k \cdot \Delta x$. Requires $|\Delta y| \leq \varepsilon$, hence $|\Delta x| \leq \varepsilon/|k|$.

This is an elementary result, but it is used in very general and not at all elementary situations.

Geometric and physical meaning of the parameters $k$ and $b$ in the equations of the straight line $y = kx + b$

The geometric meaning of the parameter $k$ is that $k$ is equal to the tangent of the angle of inclination of the straight line to the abscissa axis (taking into account the direction of the angle). Module $k$ deals with how round (close to the vertical) a line passes, therefore $k$ is called the equation coefficient of the line. Zakkkat $k$ shows in which direction the line goes (the linear function is increasing or decreasing).

Let us dwell in more detail on the physical meaning of the parameters $k$ and $b$. Let's take the graphs of two linear functions (Fig. 3 a, b) and assign different names to the variables (along the coordinate axes) so that each time this straight line describes a certain possible process.

1) Let the graphs depict the process of changing the temperature of a certain physical body. The ordinate axis shows temperature $(y = T)$ in degrees Celsius, and the abscissa axis represents time $(x = t)$ in seconds. Then

$$k = \frac{\Delta T}{\Delta t} \frac{\text{град}}{c}$$

— rate of temperature change. In case a) $|k|$ is the heating rate, in case b) $|k|$ is the cooling rate, $b = T(0)$ is the initial temperature.

2) Let $y = m$ be the mass of fuel in grams, $x = t$ be the time in seconds. Then

$$k = \frac{\Delta m}{\Delta t} \frac{\text{г}}{c}$$

— rate of change of work — power, $b = A(0)$ — work done at the beginning of the report.
