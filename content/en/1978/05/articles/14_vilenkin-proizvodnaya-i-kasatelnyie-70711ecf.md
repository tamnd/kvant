---
id: 1978-5-vilenkin-proizvodnaya-i-kasatelnyie-70711ecf
issue: kvant_1978_5
year: 1978
number: "5"
title: Derivative and tangents
authors:
  - Виленкин А. Н.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 46
page_last: 48
page_labels: 44-46
tag: JL9J
lang: en
source: kvant_digital
extraction: vision
content_sha256: 761700d4b9a576c52cdcb88edebc7b7dee1f65f29b57f4ee9d8ee0c939e08f2c
prompt_sha256: draft-1
translated_from: content/ru/1978/05/articles/14_vilenkin-proizvodnaya-i-kasatelnyie-70711ecf.md
source_content_sha256: bff1bc0d014a4dbb62f6296d709e44730740714a576066762f93470ea64e966a
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 44⟧

A. Vilenkin

Derivative and tangents

Although in the school mathematics course only one paragraph is devoted to the tangent to the graph of a function (see “Algebra and the beginnings of analysis,” 9th grade, paragraph 52), in 1977, at the university entrance exams (for the “A” program), many problems related to this topic were offered. The solution to most of them is based on using the equation
$$y = f'(x_0) \cdot x + (f(x_0) - f'(x_0)) \cdot x_0$$
 tangent to the graph of the function $y = f(x)$ at the point with abscissa $x_0$ (Fig. 1). More interesting problems are based on the fact that the angular coefficient $k$ of the tangent is equal, on the one hand, to the tangent of the angle $\varphi$ between the tangent and the abscissa axis, and on the other hand, to the value of an arbitrary $f'(x_0)$. Let's consider some types of such problems *).

Finding the Tangent Equation

Example 1 (MEIS, 1977). National equations of tangents to the graph of the function $f(x) = 4 - x^2$ at the points of intersection of this point at which $f = 0$, so to find $x_0$ one must solve the equation $4 - x_0^2 = 0$. Then, for each value of $x_0$, the tangent equation can be written in the standard way. Let's do this, taking into account that $f'(x) = -2x$.

a) $x_0 = 2$; $f(2) = 0$, $f'(2) = -4$, tangent equation $y = -4x + 8$;
b) $x_0 = -2$; $f(-2) = 0$, $f'(-2) = 4$, tangent equation $y = 4x + 8$.

Finding k and corner

Example 2 (MISI, 1977). Each sample with the x-axis tangent to the parabola $y = x^2 - 4x - 17$, tested in urine with the x-axis $x_0 = 2,5$?

Here, the angle of a straight line with the $Ox$ axis means the value of the angle that is absent from the $Ox$ axis to this straight line counterclockwise (see “Algebra 6”, paragraph 52, “Geometry 8”, paragraph 98 and “Algebra and the beginnings of analysis”, grade 10, materials for repetition, paragraph 8). Since we are given $f$ and $x_0$, we can find $k = f'(x_0)$, and from it the desired angle $\varphi$, since the tangent of the angle formed by the straight line with the axis $Ox$ is equal to the angular coefficient of this straight line: $tg\varphi = k$, and $\varphi = \arctg k$ at $k \geq 0$ and $\varphi = \pi + \arctg k$ at $k < 0$ (Fig. 2).

In this example, $f'(x) = 2x - 4$, $k = f'(2,5) = 1$, $tg\varphi = 1$, $\varphi = \pi/4$.

Example 3. The names of the equations are tangent to the graph of the function $f(x) = x^3 - 4x^2 + 3x + 1$, tested in urine with abscissas $0$ and $1$.

Here the sieve is not about the angle of a straight line with the axis $Ox$, but about the angle of two straight lines. Therefore, let us recall that the equation of two intersecting lines is called the value of the smaller of the angles determined by this line (see “Geometry 9”, § 24), that is, the angle $\alpha$ between two lines always lies within $0 \leq \alpha \leq \pi/2$.

In this example, $f'(x) = 3x^2 - 8x + 3$ and for the first tangent we have $x_0 = 0$, $f(0) = 1$, $f'(0) = 3$, $k_1 = tg\varphi_1 = 3$, $\varphi_1 = \arctg 3$, the tangent equation is $y = 3x + 1$, and for the second $x_0 = 1$, $f(1) = 1$, $f'(1) = -2$, $k_2 = tg\varphi_2 = -2$, $\varphi_2 = \pi - \arctg 2$, tangent equation $y = -2x + 3$. Then, by making an approximate figure (Fig. 3), it is easy to find the angle $\alpha = \pi - \arctg 2 - \arctg 3$.

⟦folio 45⟧

No, it's not clear what you're asking for. It looks like a list of equations or formulas.
Let's re-read the first line: "But is this angle the desired one, that is, is it true that $\alpha \leq \pi/2$, or should there be an angle $\pi - \alpha$? It may seem that the angle $\alpha$ is the desired one (since arctg $2 > \pi/4$ and arctg $3 > \pi/4$), but we will now act differently."
The second line: "Let's derive a general formula for the angle between straight lines $y = k_1x + b_1$ And $y = k_2x + b_2$. First of all, we note that during parallel translations the angles do not change, so the desired angle $\alpha$ equal to the angle between lines $y = k_1x$ And $y = k_2x$ (they are obtained from the data by transfer $\overrightarrow{CO}$). Let the angles between these lines and the axis $Ox$ equal $\varphi_1$ And $\varphi_2$ (Fig. 4). Then it is easy to find the magnitude of one of the side angles on the given straight lines: $|\varphi_2 - \varphi_1|$ (model signs had to be placed, since we don’t know which corner $\varphi_2$, $\varphi_1$ more). The desired one is the one of the angles $|\varphi_2 - \varphi_1|$, $\pi - |\varphi_2 - \varphi_1|$, which does not exceed $\pi/2$."
The third line: "It turns out that it is convenient to take the tangents of these angles, because according to the reduction formulas"
The fourth line: "tg ($\pi - |\varphi_2 - \varphi_1|$) = -tg|$\varphi_2 - \varphi_1$| (if $|\varphi_2 - \varphi_1| \neq \pi/2$) and if $|\varphi_2 - \varphi_1| > \pi/2$, then"
The fifth line: "tg $\alpha =$ tg ($\pi - |\varphi_2 - \varphi_1|$) ="
The sixth line: "= -tg|$\varphi_2 - \varphi_1$| = |tg|$\varphi_2 - \varphi_1$| |="
The seventh line: "= |tg($\varphi_2 - \varphi_1$)|"
The eighth line: "(since tg is an odd function); if $|\varphi_2 - \varphi_1| < \pi/2$, then"
The ninth line: "tg $\alpha =$ tg|$\varphi_2 - \varphi_1$|, which is also equal to |tg($\varphi_2 - \varphi_1$)|."
The tenth line: "Thus, the formula tg $\alpha$ = |tg($\varphi_2 - \varphi_1$)| is correct in all cases. Recall the formula for the tangent of the difference of two angles, we get:"
The eleventh line: "tg $\alpha$ = |$\frac{k_2 - k_1}{1 + k_2k_1}$|."
The twelfth line: "Note that the overdistribution of two straight lines is also easy to detect by their angular coefficients: if $|\varphi_2 - \varphi_1| = \pi/2$, then $\varphi_2 = \varphi_1 + \pi/2$ or $\varphi_2 = \varphi_1 - \pi/2$, and in both cases tg $\varphi_2 = -$ tg $\varphi_1 = -\frac{1}{tg\varphi_1}$"
The thirteenth line: "(if these expressions are defined), that is tg $\varphi_2 \cdot$ tg $\varphi_1 = -1$, and in slopes"
The fourteenth line: "$k_2k_1 = -1$."
The fifteenth line: "This agrees with what's in the formula for"
The sixteenth line: "equations with what's in the formula for"

Picture 1:
$$\begin{align*}
y &= f(x) \\
M_0(x_0, f(x_0))
\end{align*}$$

Picture 2:
$$k > 0, \varphi = \arctg k; k < 0, \varphi = \pi + \arctg k.$$

Picture 3:
$$\begin{align*}
y &= kx + b \\
M_1 \\
M_2
\end{align*}$$

Picture 4:
$$\begin{align*}
y &= kx + b \\
M_1 \\
M_2
\end{align*}$$

⟦folio 46⟧

tg α the right part is undefined if $k_1 k_2 + 1 = 0$.

There is another case when two lines are perpendicular - if the equations of these lines have the form $y = b$, $x = a$. In this case, $k_1 = 0$ and $k_2$ do not exist, since the straight line $x = a$ is parallel to the ordinat axis.

In example 3 we get:

$$\text{tg} \alpha = \left| \frac{-2 - 3}{1 - 6} \right| = 1, \quad \alpha = \frac{\pi}{4}.$$

Compare this answer with the one above!

Determining a graph point along a tangent

In some problems, some conditions on the tangent are given in one form or another, and it is asked to find the points of tangency.

Example 4. The name on the graph of the function $f(x) = 3x^3 - 4x^2 + 1$ is power, the tangent in which is formed by the axis Ox well $\pi/4$.

For the angle of the tangent with the Ox axis to be equal to $\pi/4$, it is necessary and sufficient that the angular coefficient of the tangent be equal to 1. But $k = f'(x_0)$, which means we need to solve the equation $f'(x_0) = 1$, that is, $9x_0^2 - 8x_0 = 1$. From it, using the formula for the roots of a quadratic equation $x_0 = 1$ or $x_0 = -1/9$. At these points $f(1) = 0$, $f(-1/9) = 230/243$. This means that there are two required points: $M_1(-1/9; 230/243)$ and $M_2(1; 0)$, which is good on the graph of this function (Fig. 5).

Example 5. At what point is the tangent to the graph of the function $f(x) = x^2$

a) parallel to straight line $2x - y + 1 = 0$;

b) perpendicular to the same line?

a) As is known (see “Algebra 6”, paragraph 52), two lines are parallel if the angular coefficients are equal. The equation of this line can be written in the form $y = 2x + 1$, which shows that $k = 2$. For the tangent $k = f'(x_0)$, so we need to solve the equation $f'(x_0) = 2$, that is $2x_0 = 2$, hence $x_0 = 1$. This means that the tangent must be drawn at the point $M_1(1; 1)$ (Fig. 6). Checking shows that the equation of this tangent is $y = 2x - 1$.

6) Let us use the fact that the lines $y = k_1 x + b_1$ and $y = k_2 x + b_2$ are perpendicular if $k_1 k_2 = -1$. In this example, $k_1 = 2$, therefore $k_2 = -1/k_1 = -1/2$, and from the equation $2x_0 = -1/2$ we find $x_0 = -1/4$. This corresponds to point $M_2(-1/4; 1/16)$, and the tangent equation is $y = -1/2 x - 1/16$. The "geometry" of this example is clearly visible in figure 6.

Example 6 (MSU, Faculty of Psychology, 1977). On the graph of the function $\frac{1}{3} x^3 - 2x^2 - 22x - 28$, find all points such that the tangents to the graph at these points intersect the positive semi-axes, cutting off segments of equal length from them.

Let the tangent be drawn at the point $M_0(x_0; f(x_0))$. Then its equation has the form

$$y = \left(x_0^2 - 4x_0 - 22\right) \cdot x - \frac{2}{3} x_0^3 + 2x_0^2 - 28.$$

No straight line $y = kx + b$ intersects the positive semi-axes, cutting off segments of equal length, only at $k = -1$ and $b > 0$ (b≠ 0, since
