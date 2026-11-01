---
id: 1978-6-zvonkin-analiz-pomogaet-algebre-34e66b52
issue: kvant_1978_6
year: 1978
number: "6"
title: Analysis helps algebra
authors:
  - Звонкин А. К.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 55
page_last: 58
page_labels: 53-56
tag: NXFC
lang: en
source: kvant_digital
extraction: vision
content_sha256: bda31a0912e4f70c8917a050de151973a69351150451bb565baf73063ab064d3
prompt_sha256: draft-1
translated_from: content/ru/1978/06/articles/11_zvonkin-analiz-pomogaet-algebre-34e66b52.md
source_content_sha256: cb176d117bce53ee9468b96ec8f079ae0dad68434fa22c224ff37f73964e7a47
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 53⟧

A. Zvonkin

Analyz
helps algebra

Quite often it is possible to solve an algebraic problem by finding and studying some suitable auxiliary function using analytical methods. We will get acquainted with such problems in this math club lesson.

Example 1. How many roots does the equation have?
$$x^3 - 3x = a^2$$ (1)

Solution. As is known, there is a formula for solving the Kubne equation («Kvant», 1976, No. 9). However, this formula is very cumbersome. Is it possible to find the number of roots of an equation without solving it?

Using an arbitrary one, we draw a graph of the function $y = x^3 - 3x$ (Fig. 1a). In the same drawing we will draw a graph of the function $y = a$, that is, a horizontal straight line (on figure 16 several such straight lines are shown at once - for different values ​​of $a$). The number of roots of equation (1) is simply the number of points of intersection of our graph and the line*). Straightaway

*) The fact that the straight line actually intersects the graph as shown in the drawing follows from paragraph 84 of the textbook “Algebra and the beginnings of analysis 10”. Indeed, the function $x \rightarrow x^3 - 3x$ is continuous and monotonous on each of the intervals $] -\infty, -1]$, $[-1, 1]$, $[1, +\infty]$; therefore, its set of values ​​on each of these intervals is an interval; therefore, for example, for any $a \in [-2; 2]$ there is a $x_0 \in [-1; 1]$ such that $f(x_0) = a$, and, due to the monotonicity of the function $f$ on the interval $[-1; 1]$, such $x_0$ is unique. In the following examples, the reader can easily verify this reasoning himself.

Fig. 1.

⟦folio 54⟧

Fig. 2.

Fig. 3.

no less together with $a^x$ we substitute $x$, we get $x = \frac{1}{\ln a}$. We substitute the resulting value $x$ into the first equation:
$$a^{\frac{1}{\ln a}} = \frac{1}{\ln a};$$
logarithm and transform:
$$\frac{1}{\ln a} \cdot \ln a = \ln \left( \frac{1}{\ln a} \right) \Leftrightarrow 1 = -\ln (\ln a) \Leftrightarrow \ln a = \frac{1}{e} \Leftrightarrow a = e^{\frac{1}{e}}.$$
So, $a_0 = e^{\frac{1}{e}}$.

Problem 3. How many roots does the equation have?
$$a^x = \log_a x?$$
Indication $*$). There are 3 images on figure
*) See also the article by A. Egorov in «Kvant»
No. 10 for 1977, p. 37.

wife five cases of mutual arrangement of graphs $y = a^x$ and $y = \log_a x$. For convenience, the straight line $y = x$ is also shown with a dotted line. The functions $a^x$ and $\log_a x$ are co-imaginable, so their graphs are symmetrical about this line. All you have to do is find the values ​​of $a_1$ and $a_2$.

Note, by the way, that figure 3 is depicted on the cover of the Algebra 8 textbook (at $a = 10$). We find the case depicted in figure 3d particularly interesting. This picture is obtained, for example, at $a = \frac{1}{16}$.

Strengthening. For $a = \frac{1}{16}$, find the coordinates of the intersection points.

Example 3. For what values ​​of $a$ is there a positive $b$ such that the equation
$$x^2 + a = 2b \cdot \ln x$$
has a single root?

⟦folio 55⟧

Solution. As always, let's start with the picture. figure 4 shows three cases of relative positions of graphs $y=x^2+a$ and $y=2b\cdot \ln x$ (for $b>0$). It is clear that equation (3) has a unique root if and only if these graphs touch (Fig. 46). At the point of tangency, not only the values ​​of the simultaneous functions $f(x)=x^2+a$ and $g(x)=2b\cdot \ln x$, but also the values ​​of their arbitrary functions $f'(x)=2x$ and $g'(x)=\frac{2b}{x}$ coincide. The resulting system:

$$\begin{cases} x^2+a=2b\cdot \ln x \\ 2x=\frac{2b}{x} \end{cases}$$

From the second equation of this system we find $x=\pm \sqrt{b}$ (recall that by assumption $b>0$). The value $x=-\sqrt{b}$ does not satisfy the system, since $\ln x$ does not determine at $x=-\sqrt{b}$. Substituting the resulting value $x$ into the first equation, we get $a=b\cdot \ln b-b$. (4)

Thus, the graphs $y=x^2+a$ and $y=2b\cdot \ln x$ are tangent if and only if condition (4) is satisfied; in this case, the tangency occurs at the point with the abscissa $x=\sqrt{b}$.

The problem boiled down to clarifying the following question: for what values ​​of $a$ does the maxim $b$ exist such that the equality $a=b\cdot \ln b-b$ holds? Another equivalent formulation: find the set of values ​​of the function $f(b)=b\cdot \ln b-b$.

Security Question: Why did we omit the requirement for positive $b$?

On the coordinate plane $Oba$ we violate the graph of the function $b \rightarrow b\cdot \ln b-b$ (Fig. 5). Now the answer to the question posed is “almost clear”: the value $b$ must exist at $a\geq a_0$ (there can be two values!). The value of $a_0$ is found in equation $f'(b)=0$. Because $f'(b)=\ln b$, $b_0=1$.

Thus, $a_0=f(b_0)=-1$.

Security Question. As can be seen from figure 5, if $a$ belongs to the interval $[-1, 0]$, then it corresponds to two values ​​$b$. What does this mean for graphs $y=x^2+a$ and $y=2b\cdot \ln x$? Draw.

Sometimes the value of the number of roots puts the solution to the equation. For example, if it is known that some equation has exactly one

⟦folio 56⟧

root, you can just try to guess it.

Technique 4. Solve the equation
$$\cos x = 1 - \frac{x^2}{2}.$$

Solution e. One of the roots of this equation is easy to guess: $x = 0$. Are there still roots? Let's look at the graph (Fig. 6). Near point $x = 0$, the graphs of functions $y = \cos x$ and $y = 1 - \frac{x^2}{2}$ are so similar to each other that without additional research it is impossible to determine which of figure, ba or 66, is correct. Let's try to prove that for all $x \neq 0$ the equation $\cos x > 1 - \frac{x^2}{2}$ is valid (that is, equality is impossible).

Let $f(x) = \cos x - 1 + \frac{x^2}{2}$.

This function is even, (i.e. $f(x) = f(-x)$), so consider only positive values ​​of $x$. Since $f(0) = 0$, to prove the equation $f(x) > 0$ for $x > 0$ it is sufficient to establish that $f$ is returned for $x = 0$, it is sufficient to establish that $f'(x) > 0$ for $x > 0$ (“Algebra and Principles of Analysis 9”, paragraph 54). Since $f'(x) = x - \sin x$, the equation $f'(x) > 0$ is equivalent to the equation $\sin x < x$, which at $x > 0$ is very indo*).

The last example we'll look at concerns the generalization of the equation between the geometric mean and the argumentative mean. It is easy to prove that for $x > 0$, $y > 0$ $\sqrt{x y} \leq \frac{x + y}{2}$ holds, and the equation is achieved if and only if $x = y$. Let's write this equation in this form:
$$\frac{1}{2} \cdot \frac{1}{2} \leq \frac{1}{2} x + \frac{1}{2} y.$$

Let us make the following generalization:

Technique 5. Let the positive numbers $a$ and $b$ be maxims such that $a + b = 1$. Prove that for all $x > 0$,

$$y > 0 \quad \text{справедливо уравнение}$$
$$x^a y^b \leq ax + by,$$
(5)

where the equation is achieved if and only if $t = 1$. We leave this proof as an exercise to the reader. (Indicated. The function $at - t^a + 1 - a$ at $t = 1$ has a minimum).

Task and

4. How many roots does the equation have?
a) $e^x = ax$?
b) $3x^4 + 4x^3 - 36x^2 = a$?
b) $\frac{x}{\ln x} = a$?

5. Solve (one equation with two unknowns):

a) $\frac{1}{x} + 2\sqrt{x} = 3y (1 - \ln y)$;
b) $\frac{\ln x}{x} = e^{\cos y}$;
b) $4^x + 1 = 2^{x+1} \sin y$.
6. Draw on the plane $(p, q)$ the set of values ​​$(p, q)$ for which the equations
a) $x^3 = 3p^2x + q$;
b) $p^x = x^q (x > 0)$ have 0, 1, 2, ... solutions with respect to $x$.
7. Solve the equation
a) $\ln x = x - 1$
b) $(x - 1)e^x + x^2 - 3x + 2 = 0$
b) $\sin x = x - \frac{1}{6}x^3$.

8. Determine (without the help of a table) which number is greater than $e^\pi$ or $\pi^e$.
