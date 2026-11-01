---
id: 1977-8-zhautyikov-krivyie-vtorogo-poryadka-cc71fec5
issue: kvant_1977_8
year: 1977
number: "8"
title: Second order curves
authors:
  - Жаутыков О. А.
rubric: osnovnye-stati
page_first: 24
page_last: 27
page_labels: 22-25
tag: LFF3
lang: en
source: kvant_digital
extraction: vision
content_sha256: bf3b19c0a803813d56e4926c757119c712cf6abe08eecb0c4026974d7b16d5df
prompt_sha256: draft-1
translated_from: content/ru/1977/08/articles/06_zhautyikov-krivyie-vtorogo-poryadka-cc71fec5.md
source_content_sha256: 53aafb2f4beceb95f7959f491f69f42f1c7f2a697c5beb12e999f0aa3712831d
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 22⟧

Second order curves

A second-order curve is a graph of a second-degree equation with two unknowns.

$$Ax^2 + Bxy + Cy^2 + Dx + Ey + F = 0,$$

(1)

where $A, B, C, D, E, F \in \mathbb{R}$. Let us denote the polynomial on the left side of equation (1) by $f(x, y)$. Then the point $M(x_0; y_0)$ belongs to the graph of equation (1) if $f(x_0, y_0) = 0$ (see “Algebra 6”, paragraph 54).

Our main task is to learn to determine the type of this graph based on the coefficients $A, B, C, D, E, F$.

We will assume that $A, B, C$ does not simultaneously vanish (if $A = B = C = 0$, then a first-order curve is obtained - the graph of the linear equation $Dx + Ey + F = 0$).

We will choose the following plan: first we will study several simple special cases - when some coefficients of equation (1) become zero, and then we will learn to obtain a graph of equation (1) from these special cases by parallel translations and rotations.

Special cases

These cases are as follows (all coefficients of the calculated terms, except perhaps $F$, are non-zero):

$$Ax^2 + Ey = 0,$$

(2a)

$$Cy^2 + Dx = 0,$$

(26)

$$Ax^2 + Cy^2 + F = 0,$$

(3)

The graph of equation (5a) is a parabola (see “Algebra 6”, paragraph 24 and the article by I. N. Bronstein “Parabola” in «Kvant», 1975, No. 4). It is easy to understand that equation (56) also defines a parabola - it is obtained by reflecting the parabola $y = -\frac{C}{D}x^2$ with respect to the bissertis of the first coordinate angle (see Fig. 1).

A circumference, an ellipse, a hyperbola, an origin, a pair of lines, or the empty set. All this can be a graph of equation (3).

Indeed, if $A = C$ ($\neq 0$), then equation (3) can be rewritten as

$$x^2 + y^2 = \frac{-F}{A}.$$

(6a)

If $-F/A > 0$, then equation (6a) defines a circle of radius $\sqrt{-F/A}$ (Fig. 2). If $-F/A = 0$, then equation (6a) is satisfied only by the pair $x = 0, y = 0$, and the origin is controlled by the graph. If $-F/A < 0$, then equation (6a) has no solutions, its graph is an empty set.

Let now $A \neq C$. Then if $A$ and $C$ are of the same sign (that is, $C/A > 0$), then the graph of equation (3), which can be rewritten as

$$x^2 + \frac{C}{A}y^2 = \frac{-F}{A},$$

(66)

is an ellipse if $-F/A > 0$ (see Fig. 3 and I. N. Bronshtein’s article “Ellipse” in «Kvant», 1975, No. 1), the origin if $-F/A = 0$, and an empty set if $-F/A < 0$.

⟦folio 23⟧

Fig. 1.

If $A$ and $C$ are of different signs (that is, if $C/A < 0$), then equation (66) for $F \neq 0$ defines a hyperbola (see I. N. Bronstein’s article “Hyperbola” in «Kvant», 1975, No. 3), and for $F=0$ - a pair of lines (Fig. 4)

$$x + \sqrt{\frac{-C}{A}} y = 0,$$
$$x - \sqrt{\frac{-C}{A}} y = 0$$

(see “Algebra 6”, paragraph 21; these equations can easily be reduced to the form $y=kx$).

Whether the set is direct or empty. In equations (4a) and (46), three cases need to be considered: $F=0, F/A > 0$ (or $F/C > 0$) and $F/A < 0$ (or $F/C < 0$).

Fig. 2.

Fig. 3.

Fig. 4.

If $F=0$, then (4a) becomes equation $x=0$, the graph of which is the $Oy$ axis, and (46) gives $y=0$, which is the $Ox$ axis.

If the numbers $F$ and $A$ (or $F$ and $C$) are of different signs, then equation (4) each gives a pair of straight lines parallel to the $Oy$ axis:

$$x = \pm \sqrt{\frac{-F}{A}}$$

or axis $Ox$

$$y = \pm \sqrt{\frac{-F}{C}}.$$

If the numbers $F$ and $A$ (or $F$ and $C$) are of the same sign, then the graph of equation (4a) (and (46)) is an empty set.

⟦folio 24⟧

Changes

These are transformations that transfer a figure into a figure congruent to it. Therefore, as a result of the change, a straight line will remain straight, a parabola will remain a parabola, and a hyperbola will remain a hyperbola. But the equations of these lines change (but will still be equations of the second degree), and this can be used to simplify the equation - say, choose a translation after which the term $Dx$ will disappear into the equations, or a rotation that cancels $Bxy$. We will limit ourselves to translations and rotations.

Parallel transfer. Let the parallel transfer $\vec{r}(a; b)$ move the point $M(x; y)$ to the point $M'(u; v)$. then $x+a=u, y+b=v$ (Fig. 5), so

$$x = u - a,$$
$$y = v - b.$$

If the coordinates of the point $M$ satisfy the equation $f(x, y)=0$, then the coordinates of the point $M'(u; v)$ satisfy the equation

$$g(u, v) = f(u - a, v - b) = 0,$$

that is, when transferring $\vec{r}(a; b)$, the graph of equation $f(x, y)=0$ is displayed in the graph of the equation (in variables $x, y$)

$$g(x, y) = f(x - a, y - b) = 0.$$

The reverse translation $\vec{r}'(-a; -b)$ maps the graph of equation $g(x, y)=0$ to the graph of equation $f(x, y)=0$.

In the textbook “Algebra and Beginning Analysis 10” (section 9*) it is proven that when transferring $\vec{r}(a; b)$, the graph of function $y=f(x)$ is mapped to the graph of function $y=f(x-a)+b$. This fact is easily obtained from the property of transfers that we have proven (it becomes clear why $a$ is included in the last formula with a minus sign, and $b$ with a plus sign). The graph of function $y=f(x)$ coincides with the graph of equation $g(x, y) = y-f(x) = 0$.

When transferring $\vec{r}(a; b)$ from the graph of equation $g(x, y)=0$, we obtain the graph of equation $g(x-a, y-b)=0$, that is, equation $(y-b)-f(x-a)=0$, or function $y = f(x-a)+b$.

Turns. Consider a rotation with center $O(0; 0)$ by angle $\beta$ in the positive direction (counterclockwise). With this rotation, $R_0^\beta$ maps point $M(x; y)$ to point $M'(u; v)$. Let's try to connect $u, v$ and $x, y$. Let $|OM|=r$ and point $M(x; y)$ be obtained from point $K(r; 0)$ on the axis $Ox$ rotate by angle $\alpha$ (Fig. 6). Then (see “Algebra and beginning of analysis 9”, §.14, paragraphs 70, 71) $x=r\cos \alpha, y=r\sin \alpha$. But point $M'(u; v)$ is obtained from point $K(r; 0)$ by turning by angle $\alpha+\beta$, therefore $u=r\cos (\alpha+\beta), v=r\sin (\alpha+\beta)$. Since

$$\cos (\alpha+\beta) = \cos \alpha \cos \beta - \sin \alpha \sin \beta,$$
$$\sin (\alpha+\beta) = \sin \alpha \cos \beta + \cos \alpha \sin \beta,$$

⟦folio 25⟧

we get:

$$u = r \cos(\alpha + \beta) = x \cos \beta - y \sin \beta,$$
$$v = r \sin(\alpha + \beta) = x \sin \beta + y \cos \beta.$$

When turning back $R_0^{-\beta}$, point $M'(u; v)$ is mapped to point $M(x; y)$, so
$$x = u \cos(-\beta) - v \sin(-\beta) = u \cos \beta + v \sin \beta,$$
$$y = u \sin(-\beta) + v \cos(-\beta) = -u \sin \beta + v \cos \beta.$$

If the coordinates of point $M(x; y)$ satisfy the equation $f(x, y)=0$, then the coordinates of point $M'(u; v)$ must satisfy the equation

$$g(u, v) = f(u \cos \beta + v \sin \beta, -u \sin \beta + v \cos \beta) = 0,$$

that is, upon rotation $R_0^{\beta}$, the graph of equation $f(x, y)=0$ is mapped to the graph of equation (in variables $x, y$)

$$g(x, y) = f(x \cos \beta + y \sin \beta, -x \sin \beta + y \cos \beta) = 0.$$

Simplifying Equation $f(x, y)=0$

Let's return to the general equation (1) of the second-order curve

$$Ax^2 + Bxy + Cy^2 + Dx + Ey + F = 0.$$

Let's try by rotating the image from the member $Bxy$. Substituting expressions $x, y$ through $u, v$ (formulas (8)) into equation $f(x, y)=0$, we obtain some equation $g(u, v)=0$ of the second degree. We write out the terms containing only $uv$ and find $B'$—the new value of the coefficient of the product $uv$:

$$B' = (A - C) 2\sin \beta \cos \beta + B (\cos^2 \beta - \sin^2 \beta).$$

Let's equate it to zero:

$$(A - C) \sin 2\beta + B \cos 2\beta = 0$$

and find $\beta$:

$$\mathrm{tg} 2\beta = \frac{B}{C - A}$$

$$\cos 2\beta = 0 (\beta = 45^\circ)$$ at $A = C$.

So, you can always rotate images (1) to view

$$Ax^2 + Cy^2 + Dx + Ey + F = 0.$$

Example Let the equation be given

$$7x^2 + 6\sqrt{3}xy + 13y^2 + 4(\sqrt{3} - 8)x - 4(8\sqrt{3} + 1)y + 4 = 0.$$

Here $A = 7, B = 6\sqrt{3}, C = 13$, therefore $tg 2\beta = \sqrt{3}, \beta = 30^\circ$. Substituting (using formulas (8)) into equation (10)

$$x = \frac{\sqrt{3}}{2} u + \frac{1}{2} v,$$

$$y = -\frac{1}{2} u + \frac{\sqrt{3}}{2} v,$$

we get (check!) the equation

$$4u^2 + 16v^2 + 8u - 64v + 4 = 0.$$

This means that the graph of equation (10) is obtained from the graph of equation

$$4x^2 + 16y^2 + 8x - 64y + 4 = 0$$

turn $R_0^{-30^\circ}$.

Now let's use translations and try to reduce equation (9) to an even simpler one - without the terms $Dx$ and $Ey$. When transferring $r(a; b)$, the graph of equation $f(x, y)=0$ goes into the graph of equation $g(x, y)=0$, where $g(x, y)=f(x-a, y-b)$, that is, equation (9) goes into this:

$$A(x-a)^2 + C(y-b)^2 + D(x-a) + E(y-b) + F = 0.$$

Expanding the brackets and simplifying, we get:

$$Ax^2 + Cy^2 + (D - 2aA)x + (E - 2bC)y + Aa^2 + Cb^2 - aD - bE + F = 0.$$

Let us equate the coefficients of $x, y$ to zero and arrive at the equation for $a$ and $b$:

$$D - 2aA = 0, E - 2bC = 0,$$

whence $a = \frac{D}{2A}$ (at $A \neq 0$), $b = \frac{E}{2C}$ (at $C \neq 0$).

Example (continued). In equation (11) $A = 4, C = 16, D = 8, E = -64, F = 4$, therefore $a = 1, b = -2$, and the translation $r(1; -2)$ transforms the graph of equation (11) into the graph of equation

$$4x^2 + 16y^2 - 64 = 0,$$

or

$$x^2 + 4y^2 - 16 = 0.$$

And this is an equation of the form (3), it defines an ellipse

$$\left(\frac{x}{4}\right)^2 + \left(\frac{y}{2}\right)^2 = 1.$$
