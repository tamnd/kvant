---
id: 1975-4-berkolayko-ispolzovanie-neravenstva-koshi-pri-reshenii-zadach-d6a65256
issue: kvant_1975_4
year: 1975
number: "4"
title: Using Cauchy's inequality to solve problems
authors:
  - Берколайко С. Т.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 39
page_last: 42
page_labels: 37-40
tag: WHVD
lang: en
source: kvant_digital
extraction: vision
content_sha256: 58a5357e34ed7017bd19337986bf5058f214dc3cf807843b899e0fc893e8bee3
prompt_sha256: draft-1
translated_from: content/ru/1975/04/articles/09_berkolayko-ispolzovanie-neravenstva-koshi-pri-reshenii-zadach-d6a65256.md
source_content_sha256: 2300b17c96897028e74e971b8cd03b606e65b2e03e3bff79e802c36fe3638051
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 37⟧

Using Cauchy's inequality to solve problems
S. T. Berkolaiko

In the school course of mathematics, the properties of elemental inequalities and methods of proving them are given a significant place. However, in the introductory samples of universities, many applicants have difficulty applying inequalities in the study of elemental functions and solving maximum and minimum problems (mainly of geometric and physical content). Meanwhile, to solve such problems it is enough to know and, most importantly, be able to apply comparative research.

Among such inequalities is, first of all, Cauchy’s inequality: the arithmetic mean of two positive numbers a and b is not less than their geometric mean:

$$\frac{a+b}{2} \geq \sqrt{ab}.$$

(1)

Along with the Cauchy inequality, it is useful for applicants to know some of its corollaries, namely:

$$a+b \geq 2\sqrt{ab},$$
$$a^2+b^2 \geq 2ab,$$
$$ab \leq \left(\frac{a+b}{2}\right)^2,$$
$$ab \leq \frac{1}{2}\left(a^2+b^2\right)$$

(bring them out yourself).

As is known, in inequality (1) equality is achieved only when a=b. Consequently, inequalities (2)–(5) transform into equalities only when a=b.

Inequalities (1)—(5) are equivalent to each other (for a>0, b>0), any of them can be used when solving problems, and, as the practice of introductory examples shows, the solution to specific maximum and minimum problems can easily be found precisely with the help of these inequalities. Let's look at a number of examples.

Task 1. Name the value of the product of two variables, the sum of which is constructed.

This question is solved by inequality (4), which states that the product of two positive numbers is not greater than the square of their arithmetic mean. Indeed, if a and b are two variables, a+b=M, where M is some constant, then for a≠b ​​according to (4) ab < $\left(\frac{M}{2}\right)^2$, and for a=b inequality (4) becomes the equality ab = $\left(\frac{M}{2}\right)^2$.

Therefore, when a=b, the product ab reaches the maximum value equal to $\left(\frac{M}{2}\right)^2$.

Similarly, if you need to find the maximum value of the sum of two variables whose product is constructed, then inequality (2) is applied.

Task 2 (MSU, mechanism, 1966). From the boundaries it is necessary to cut down and arrange it in the form of a direct complete parallelenade, the height of which should be equal to the diazons of the main

⟦folio 38⟧

vania, and the area of ​​the base should be equal to 4 $м^2$. At what lengths of the sides of the base will the surface area of ​​the pedestal be the smallest?

Let $x$ and $y$ be the lengths (in meters) of the sides of the rectangle lying at the base of the pedestal. Then, according to the conditions of the problem, the height $z$ of the pedestal is equal to $\sqrt{x^2+y^2}$, and the area of ​​its surface (in $м^2$)

$$S = 2(x+y)\cdot\sqrt{x^2+y^2}+8,$$

at the same time $xy = 4$. Using inequalities (2) and (3), we obtain

$$x+y \geqslant 2\sqrt{xy}=4;\quad x^2+y^2 \geqslant 2xy=8,$$

whence $\sqrt{x^2+y^2}\geqslant\sqrt{8}$. Hence,

$$S \geqslant 2\cdot4\cdot\sqrt{8}+8=8+16\sqrt{2}\ (м^2),$$

Moreover, equality is achieved at $x=y$, since the perimeter of the base $(2(x+y))$ and the height $(\sqrt{x^2+y^2})$ simultaneously at $x=y\ (=2)$ reach their smallest value. So, the smallest surface area will be at the pedestal, at the base of which lies a square with a side of 2 m.

Problem 3 (MSU, Mechanics and Mathematics, 1966). *You need to make a box in the shape of a rectangular parallelepiped with a base area equal to 1 $см^2$. The sum of the lengths of all the edges of the parallelepiped should be equal to 20 cm. At what size of the box will its surface area be greatest?*

Let $x$ and $y$ be the lengths of the sides of the rectangle (in centimeters) lying at the base of the parallelepiped, and $z$ its height. Then by condition $xy=1$, $4x+4y+4z=20$, whence $x+y+z=5$.

The surface area of ​​the box is

$$S = 2(x+y)\cdot z+2.$$

Taking into account the relation $(x+y)+z=5$ and inequality (4), we obtain

$$(x+y)\cdot z \leqslant \left[\frac{(x+y)+z}{2}\right]^2 = \frac{25}{4},$$

and this inequality turns into

⟦column⟧

equality only for $x+y=z=2{,}5$. Thus, the product $(x+y)z$, and with it the surface area of ​​the box, reaches its greatest value if $z=2{,}5\ (см)$ and $x+y=2{,}5$. Solving a system of equations

$$\begin{cases} x+y=2{,}5, \\ xy=1, \end{cases}$$

find the dimensions of the box: $2\times0{,}5\times2{,}5\ (см)$.

Problem 4 (NSU, 1968). *Given a rectangle $ABCD$ with sides $AB=a$; $BC=b$. Rectangles are described around it in such a way that each side of the described rectangle passes through one of the vertices of the rectangle $ABCD$. Find the circumscribed rectangle with the largest area and determine its area.*

Let $a$ and $b$ be the lengths of the sides of the given rectangle (Fig. 1), $\alpha$ be the angle between the corresponding sides of the given and described rectangles. Then the lengths of the sides of the circumscribed rectangle are $a\sin\alpha+b\cos\alpha$, $a\cos\alpha+b\sin\alpha$, its area

$$S(\alpha)=(a\sin\alpha+b\cos\alpha)\times$$
$$\times(a\cos\alpha+b\sin\alpha)=$$
$$=(a^2+b^2)\sin\alpha\cos\alpha+ab.$$

Here the variable is the product $\sin\alpha\cdot\cos\alpha$. We need to find the greatest value of this product. Considering that $\sin^2\alpha+\cos^2\alpha=1$, we apply inequality (5):

$$\sin\alpha\cdot\cos\alpha \leqslant \frac{1}{2}(\sin^2\alpha+\cos^2\alpha)=\frac{1}{2}.$$

Equality is achieved only at $\sin\alpha=\cos\alpha$, that is, at $\alpha=45^\circ$ (since by condition $0^\circ<\alpha<90^\circ$). Consequently, the greatest area has the circumscribed rectangle whose sides form an angle $45^\circ$ with the sides of the given one. It is easy to see that this rectangle is a square, its area is

$$S_{наиб}=\frac{1}{2}(a+b)^2.$$

⟦folio 39⟧

Fig. 1.

Task 5 (NSU, 1968). The distance between two parallel lines is h. The third line, parallel to the dinyas, is located outside the stripes between them at a distance H from the far one. The segment AB is redistributed to straight lines, and its ends lie on the first two straight lines.

Find point M on the third straight line so that AMB is the greatest.

The position of point M on the third line is determined, for example, by the distance from it to the point K of intersection of line AB with the third line (Fig. 2). Let us denote KM by x. To solve the problem, it is enough to find the value of x for which the corresponding angle α = AMB is most sufficient.

Let us introduce the auxiliary angle β = KMA and use it to express tan α as a function of x. Using the formula for the tangent of the difference of two arguments and the definition of the tangent of an acute angle, we obtain tan α = tan [(α + β) - β] =
$$\frac{tg(\alpha + \beta) - tg\beta}{1 + tg(\alpha + \beta) \cdot tg\beta} = \frac{H}{x} - \frac{H - h}{x} = \frac{h}{1 + \frac{H - h}{x^2}}.$$

This shows that tan α (a, therefore, α) reaches its maximum value when the sum x + \frac{H(H - h)}{x}

reaches the most significance. Since x \frac{H(H - h)}{x} is constant, we use inequality (2):

$$x + \frac{H(H - h)}{x} \geq 2 \sqrt{x \frac{H(H - h)}{x}} = 2 \sqrt{H(H - h)}.$$

The desired value x is the positive root of the equation x = \frac{H(H - h)}{x}, that is

$$x = \sqrt{H(H - h)}.$$

The required point can now be found using a simple construction: on the segment KB we describe as a diameter a semicircle that intersects the second straight line (passing through A) at point C (Fig. 2), and plot the segment KM₁ = KC on the third straight line; point M₁ is the required one (the proof is independent).

It is easy to see that the point M₂, symmetrical to the point M₁ relative to the point K, has the same properties as the point M₁. So, there are two required points: M₁ and M₂.

Task 6 (MSU, 1971). An edem car from point A to point B at a constant speed of 42 km/h. At point B, it switches to uniformly slow motion, and for every hour its speed decreases by a km/h, and it comes to a complete stop. Then it immediately begins to move uniformly with an acceleration of a km/h².

⟦folio 40⟧

*What should the value of $a$ be so that 3 hours after the resumption of movement the car is closest to point $B$?*

Let the car stop at point $C$, and after 3 hours it was at point $D$. Consider the movement of a car in section $BC$. According to the condition, the speed of the car at point $B$ is equal to $v_B=$ $=42$ $\mathit{км/ч}$; this speed is the initial one in section $BC$. The final speed on the section under consideration is $v_C=0$, so the travel time on section $BC$ (in hours) is $t_{BC}=\dfrac{42}{a}$.

Using the formula for path length with uniformly variable rectilinear motion, we express $BC$ and $CD$ through the parameter $a$:

$$BC=\frac{882}{a},\quad CD=\frac{9a}{2}.$$

Thus,

$$BD=BC+CD=\frac{882}{a}+\frac{9a}{2}.$$

Since the product of the terms $\dfrac{882}{a}$ and $\dfrac{9a}{2}$ is constant, the resulting sum—this follows from inequality (2)—reaches its minimum value at

$$\frac{882}{a}=\frac{9a}{2},$$

whence $a=14$ $\mathit{км/ч^2}$. In this case, $BD=$ $=126$ $\mathit{км}$.

Exercises

1 (MSU, 1966). You need to make a kite in the shape of a straight prism with a base in the shape of a right triangle with a hypotenuse equal to 50 $см$. The lateral surface of this prism has an area of ​​0.96 $м^2$. What should the sides of the base triangle be so that the sum of the lengths of all the edges of the prism is minimal?
2 (MSU, 1966). At the base of a right prism lies a right triangle with an area equal to 2 $м^2$, and the height of the prism is equal to the hypotenuse of the base. What should the sides of the base be so that the lateral surface of the prism is the smallest?
3 (MSU, 1966). It is required to make a box in the shape of a rectangular parallelepiped. The bottom area of ​​the box should be

⟦column⟧

is equal to 2 $дм^2$, and the lateral surface is 18 $дм^2$. At what size of the box will the sum of the lengths of all its edges be the smallest?
4 (MSU, Faculty of Economics, 1969). For what real $x$ is the expression

$$y=\frac{2x-1}{2x-x^2-4}$$

takes the smallest value?
5 (MSU, 1971). The motorcyclist leaves point $A$ and moves with a constant acceleration of 12 $км/ч^2$ (the initial speed is zero). Having reached a speed of $v$ $км/ч$, he travels at this speed of 25 $км$, and then switches to uniformly slow motion, and for every hour his speed decreases by 24 $км/ч$, and moves like this until he comes to a complete stop. Then he immediately turns back and drives to point $A$ at a constant speed $v$ $км/ч$.

At what speed $v$ will the motorcyclist make the fastest way back from the stop to point $A$?
6 (MSU, Faculty of Philology, 1972). For what positive $x$ does the expression

$$y=2x+\frac{3\dfrac{1}{8}}{x+1}$$

takes the minimum value?
7 (MEPhI, 1972). Find the volume of the smallest cone among all those cones that can be described around a ball of radius $R$.

---

Amendments

The following typos were made in «Kvant» No. 2.
Page 25, left column, 14th line from the bottom.
Printed: Should read:
$\ldots \overline{A}\Rightarrow\overline{B}$					$\ldots A\Rightarrow B$

Page 26, at problem M309.
Printed: Should read:
$x^{2n}+x+1$					$x^{2n}+x^n+1$

Page 44, right column:
figure 1 and figure 2 should be swapped.
Page 47, left column:
figure 5 and figure 6 should be swapped.
Page 63, right column, 2nd line from top.
Printed: Should read:
$-(\overrightarrow{A}-\overrightarrow{B})+\ldots$					$=(\overrightarrow{A}-\overrightarrow{B})^2+\ldots$

Page 64, left column, 5th line from the bottom.
Printed: Should read:
$заказ=59259$					$заказ=59295$

⟦folio 40⟧
