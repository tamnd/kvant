---
id: 1981-5-sukonnik-gornshteyn-mozhno-reshit-prosche-bb5a87ca
issue: kvant_1981_5
year: 1981
number: "5"
title: It could be easier to solve!
authors:
  - Суконник Я. Н.
  - Горнштейн П. И.
rubric: raznoe
rubric_sub: Разное
page_first: 44
page_last: 48
page_labels: 42, 44, 45, 46
tag: R2BD
lang: en
source: kvant_digital
extraction: vision
content_sha256: b044820388dce5a25da05c177cda79ffbafe11196865933232c3082b3bd50f44
prompt_sha256: draft-1
translated_from: content/ru/1981/05/articles/15_sukonnik-gornshteyn-mozhno-reshit-prosche-bb5a87ca.md
source_content_sha256: af86ef521d1ceed545ce46867798c6f182461f03658ae53bc854aa9bc83c06c5
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 42⟧

It could be easier to solve!

Anyone who is preparing for entrance exams in mathematics has probably encountered difficult exam problems more than once, the solution of which requires long discussions and lengthy calculations. And everyone, of course, is occupied with the question: is it possible to come up with a simple, varied and short solution for such a problem?

Quite often it is possible. But reaching such a decision is not easy - it takes a long and persistent effort. But every beautiful solution to a difficult problem always evokes a feeling of satisfaction and testifies to the deep knowledge and creative abilities of the applicant. That is why, when preparing for exams, trying to find or, in extreme cases, analyze such solutions is especially useful.

It is all the more unfortunate that books for applicants sometimes contain unjustifiably cumbersome and irrational solutions.

Let's take, for example, the book by Yu. V. Nesterenko, S. N. OLEXNIK and M. K. Potapov “Problems of entrance exams in mathematics” (M., “Nauka”, 1980), which reproduces the options in mathematics offered in 1977-1979. admitted to Moscow University, and the solutions to some of the options are indicated. Solutions to some problems take up one, two, even three pages in this book.

Meanwhile, they can often be solved much simpler and shorter.

Currently.state contains eight problems from the specified book with simpler solutions.

Shape Properties

When solving geometric problems, students often, without much thinking, come up with lengths and cumbersome calculations, which, however, usually lead to the goal. Meanwhile, such problems can sometimes be solved very quickly if you apply a certain theorem, are able to take advantage of the specifics of the configuration, and see the necessary additional construction. In geometrics, the more successfully we will move forward, the wider our “geometric horizons” are, the better we learn to see the properties of figures that can be “played” into solutions.

Problem 1 (MSU, physics department, 1977). Given an equal trapezoid in which a circle is inscribed and around which the circle is circumscribed. The ratio of the height of the trapezoid to the radius of the circumscribed circle is $\sqrt{\frac{2}{3}}$. Find the corners of the trapezoid.

Solution. Let $ABCD$ be the given trapezoid (Fig. 1). Let's draw the diagonal $BD$ and the height $BE$. We denote $DAB$ by $x$, $ADB$ by $y$. By lowering the perpendicular from the center $O$ along the toboggan circle (we denote its radius by $R$) to $BD$ and continuing it until it intersects with this circle, we can see that $|BD|=2R \cdot \sin x$. (1)

Fig. 1.

⟦folio 44⟧

Fig. 4.

So, $\frac{|CE|}{|EA|} = \frac{4}{5}, \frac{|CE|}{|CA|} = \frac{4}{9}$. Since $[BK]$ is the total height of triangles $BCE$ and $BCA$,

$$\frac{S_{\triangle BCE}}{S_{\triangle BCA}} = \frac{|CE|}{|CA|}.$$

So, $S_{\triangle BCE} = \frac{4}{9} S_{\triangle BCA}$. But $S_{\triangle BCA} = S_{\triangle ADB} = \frac{1}{2} |AD| \cdot |AB| \cdot \sin DAB$.

Therefore, $S_{\triangle BCE} = 10\sqrt{3}$.

Problem 4 (MSU, department of the General Geological Faculty, 1979). The base of parameters $SABC$ is a regular triangle whose side length is $\sqrt{3}$. The base of the altitude dropped from the vertex $S$ is the point $O$, which lies inside the triangle $ABC$. The distance from point $O$ to side $AC$ is 1. The sine of angle $OBA$ is related to the sine of angle $OBC$ as 2:1. The area of ​​face $SAB$ is equal to $\sqrt{\frac{5}{6}}$. Find volume parameters.

Solution. Let us denote the bases of the perpendiculars dropped from $O$ to the sides $AB, BC, CA$, respectively, by $D, E, F$ (Fig. 4). From triangles $OEB$ and $ODB$

$$\frac{|OE|}{|OD|} = \frac{\sin OBC}{\sin OBA}.$$

So, $|OE| = \frac{1}{2} |OD|$. From the equality $S_{\triangle ABC} = S_{\triangle OAB} + S_{\triangle OBC} + S_{\triangle OAC}$ it follows that $|OD| + |OE| + |OF| = h$, where $h$ is the length of the altitude of triangle $ABC$. (Note i.e. This equality is obviously true for any point $O$ inside an equilateral triangle.) Since $h = |BC| \times \sin 60^\circ = \frac{3}{2}$ and $|OF| = 1$, we get

$$|OD| = \frac{1}{3}.$$ Meaning $|AB|$ and $S_{\triangle SAB}$, we find $|SD|$. Then from $\triangle SOD$ we find $|SO|$. Answer. $\frac{\sqrt{3}}{4}$.

A schedule helps.

Often, in entrance exams, equations-systems-of-inequalities are presented containing two variables (say, $x$ and $a$), and the requirement is to find all values ​​of one variable (for example, $a$), for which the second variable (respectively, $x$) or, if angularly, the equation-in-use has some property. (In problems like this, the variable $a$ is usually called a parameter.)

For some reason, many authors of textbooks, including the authors of the above-mentioned book, tend to solve such problems by gramodic research of formulas expressing x through $a$, while a more appropriate “geometric solution” is constructing a graph on the plane $Oxa$ (this method is sometimes called the “Och method”). The required set is “read” from the $Oa$ axis, which ends the solution.

Problem 5 (MSU, department of political economy, economics department, 1977). Find all $a$, for each of which the inequality

$$3 - |x - a| > x^2$$

has at least one negative solution.

Solution. This inequality is equivalent to the inequality

$$|x - a| < 3 - x^2.$$

and, therefore, the system

$$-(3 - x^2) < x - a < 3 - x^2.$$

For Pozny, the problem can be reformulated as follows: find all $a$, for each of which the system

$$\begin{cases} x - a < 3 - x^2 \\ x - a > -(3 - x^2) \\ x < 0 \end{cases}$$

or system

$$\begin{cases} a > x^2 + x - 3 \\ a < -x^2 + x + 3 \\ x < 0 \end{cases}$$

has at least one solution. Nari-

⟦folio 45⟧

Having placed the parabolas $a=x^2+x-3$ and $a=-x^2+x+3$ on the plane $Oxa$ and projecting the set of solutions of the system onto the axis $Oa$ (on figure 5 it is shaded), we obtain the answer: $]- \frac{13}{4}; 3$ [.

Comment. Since in this inequality the parameter $a$ appears in one place, the problem can be solved this way: on the plane $Oxy$ we draw a paraboly $y=3-x^2$ and begin to move the “corner” $y=|x-a|$ (Fig. 6) along the axis $Ox$ from left to right; Obviously, for the inequality $|x-a|<3-x^2$, equivalent to the given one, negative solutions will begin to appear after the “corner” touches the paraboly [the abscissa of the point of tangency is found in the equality $y'=-2x=1$, the abscissa of the vertex of the “corner” is from the equation of the tangent $y=\frac{11}{4}+1 \cdot (x-(-\frac{1}{2}))$], and will end up appearing when the “corner” doit do the vertex of the paraboly.

Problem 6 (MSU, department of the General Geological Faculty, 1978). Find all values ​​of the parameter $a$, for each of which there is at least one $x$ satisfying the condition $\left\{ \begin{array}{l} x^2+(5a+2)x+4a^2+2a<0 \\ x^2+a^2=4. \end{array} \right.$

Solution. The polynomial on the left side of the inequality included in this system will be located in the product of two sets: $x^2+(5a+2)x+4a^2+2a=(a+x)(4a+x+2)$. Therefore, this system is equivalent to the system
$$\left\{ \begin{array}{l} (a+x)(4a+x+2)<0 \\ x^2+a^2=4 \end{array} \right.$$
or aggregates (“Algebra and principles of analysis 9-10”, paragraph 74) of the system
$$\left\{ \begin{array}{l} a+x>0 \\ 4a+x+2<0 \\ x^2+a^2=4 \end{array} \right.$$
$$\left\{ \begin{array}{l} a+x<0 \\ 4a+x+2>0 \\ x^2+a^2=4 \end{array} \right.$$
Let us rewrite systems (1), (2) in the form
$$\left\{ \begin{array}{l} a>-x \\ a<-\frac{1}{4}x-\frac{1}{2} \\ x^2+a^2=4 \end{array} \right.$$
$$\left\{ \begin{array}{l} a<-x \\ a>-\frac{1}{4}x-\frac{1}{2} \\ x^2+a^2=4 \end{array} \right.$$
Let us draw a circle $x^2+a^2=4$ and straight lines $a=-x$, $a=-\frac{1}{4}x-\frac{1}{2}$ on the plane $Oxa$. Having projected onto the axis $Oa$ the set of solutions of system (1') (“blue arc” on figure 7) and the set of solutions of system (2′) (“red arc”) and combining the projections, we obtain the answer: $]- \sqrt{2}; - \frac{16}{17} \cup U]0; \sqrt{2}$ [.

Problem 7 (MSU, Binofak, 1978). Find all values ​​of $a$, for each of which equalize
$$x|x+2a|+1-a=0$$
has a unique solution.

⟦folio 46⟧

Solution. This equation is equivalent to the totality of the system
$$\begin{cases}
x + 2a \geqslant 0 \\
x(x + 2a) + 1 - a = 0 \\
x(-x - 2a) + 1 - a = 0
\end{cases}$$

or system
$$\begin{cases}
a = \frac{x^2 + 1}{1 - 2x} \\
a \geqslant -\frac{x}{2} \\
a < -\frac{x}{2}
\end{cases}$$

Let us construct on the plane $Oxa$ the line $a = -\frac{x}{2}$ and, using the means of differential calculus, the curves $a = \frac{x^2 + 1}{1 - 2x}$（《blue curve》 on figure 8) and $a = \frac{1 - x^2}{2x + 1}$（《red curve》）. The solution to system (1) is the “thick part” of the blue curve, system (2) is the “thick part” of the red curve. Primishes, parallel to the axis $Ox$, intersect the union of these “thick curves” once at $a > 1$ and at $a < \frac{\sqrt{5} - 1}{2}$, twice at $a = 1$ and at $a = \frac{\sqrt{5} - 1}{2}$, three times at $\frac{\sqrt{5} - 1}{2} < a < 1$. Answer. ] $-\infty; \frac{\sqrt{5} - 1}{2}$ [U U] 1; $+\infty$[.

Problem 8 (MSU, department of planning and economics, cybernetics, economics department, 1977). Determine at what a the equation
$$\log_3 (9^x + 9a^3) = x$$
has exactly two solutions.
Solution. This equation is equivalent to the equation
$$3^x = 9^x + 9a^3.$$
Setting $3^x = t$, we obtain the auxiliary quadratic equation
$$t^2 - t + 9a^3 = 0.$$ (1)

Since the equation $3^x = t$ (relative to $x$) has a solution only for $t > 0$, and for each such $t$ it has a unique solution, the problem takes the form: determine for which a equation (1) has exactly two positive roots, and for this it is necessary and sufficient that $a$ satisfies the system
$$\begin{cases}
1 - 36a^3 > 0 \\
9a^3 > 0
\end{cases}$$
(this is sufficiently evident from Vieta’s theorem and the fact that the second coefficient in equation (1) is negative). Answer. ] $0; \frac{1}{\sqrt{36}}$ [.
