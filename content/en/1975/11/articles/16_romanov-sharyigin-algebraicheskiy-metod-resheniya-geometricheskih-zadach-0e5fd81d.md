---
id: 1975-11-romanov-sharyigin-algebraicheskiy-metod-resheniya-geometricheskih-zadach-0e5fd81d
issue: kvant_1975_11
year: 1975
number: "11"
title: Algebraic method for solving geometric problems
authors:
  - Романов С. В.
  - Шарыгин И. Ф.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 47
page_last: 51
page_labels: 45-49
tag: PK74
lang: en
source: kvant_digital
extraction: vision
content_sha256: 467ffedab2e4e579ebb73781dae81a5750d016d122b1a630d7ff26a433accea0
prompt_sha256: draft-1
translated_from: content/ru/1975/11/articles/16_romanov-sharyigin-algebraicheskiy-metod-resheniya-geometricheskih-zadach-0e5fd81d.md
source_content_sha256: d4e5d5a3932e4a29df1e6980f7fa61687fb82c87e1c053a5ebf40f084c045eb3
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 45⟧

Algebraic method for solving geometric problems

S. V. Romanov, I. F. Sharyzin

When you are presented with a planietry problem during an exam, it is often not worth wasting time on finding a geometric solution or a rational solution to its algebraic ones. Of course, a geometric solution, as a rule, is more elegant, while an algebraic solution contains cumbersome expressions, but in the exam, unlike optimization, the elegance of a practice solution does not affect the grade. Therefore, the main “weapon” when solving geometric problems in the exam is the algebraic method. This is what we will talk about in this article.

First, we present two solutions to the same problem.

Problem 1. Prove that $l^2 = ab - mn$ (Fig. 1). Let's put $\Rightarrow ADB = \alpha$. By the cosine theorem for triangles $ABD$ and $BDC$ we have:
$$a^2 = l^2 + m^2 - 2ml \cos \alpha,$$
$$b^2 = l^2 + n^2 + 2nl \cos \alpha.$$ (2)
Let's multiply (1) by $n$, and (2) by $m$ and add the resulting expressions. Given that $\frac{m}{n} = \frac{a}{b}$, we can easily transform the sum to the form $l^2 = ab - mn$.

This is the algebraic method.

Before reading the following solutions, try solving this geometry problem yourself.

So, a purely geometric solution. Let us describe a circle (Fig. 2) around the triangle $ABC$ and continue the bissertis until it intersects with this circle at the point $E$. By the well-known theorem $mn = l \cdot DE$. In addition, from the similarity of triangles $BCE$ and $ABD$ it follows $\frac{a}{l} = \frac{l + DE}{b}$, whence $ab = l^2 + l \cdot DE$. Replacing $l \cdot DE$ with $mn$, we get the required result.

Fig. 1.
Fig. 2.

⟦folio 46⟧

Of course, this solution is shorter and more elegant than the previous one, but it will probably take quite a lot of time to figure it out.

The algebraic method is based on certain standard techniques. There are two types of algebraic method:

a) “direct counting”;
b) “drawing up an equation.”

The essence of the “direct account” is as follows. We connect the quantities specified in the conditions of the problem and those that need to be found with an integer of intermediate quantities, each of which is sequentially determined through the previous ones.

Problem 2 (MSU, Faculty of Geography, 1966). In a parallelogram with sides a and b and angle α, bicsecrets of the four angles are drawn. Find the area of ​​the quadrilateral bounded by bicsecris (Fig. 3).

It is useful, first of all, to draw up a plan for solving the problem, in other words, to write down an integer of elements that can be sequentially calculated, connecting what is given and what needs to be found.

First of all, note that MNPQ is a parallelogram. Let us find $\triangle ABC$, $\triangle ABM$, $\triangle AMB = \triangle QMN$ sequentially. Then from $\Delta BCQ$ (by the theorem of sines) we find BQ, from $\Delta BMA - BM$ and AM, from $\Delta NAD - AN$. After this, it is easy to calculate MN and QM and the required area $S = QM \cdot MN \cdot \sin \triangle QMN$.

So, $\triangle ABC = 180^\circ - \alpha$, $\triangle ABM = \frac{180^\circ - \alpha}{2}$, $\triangle AMB = 90^\circ = \triangle QMN$, i.e. MNPQ is a rectangle. $BQ = a \sin \frac{\alpha}{2}, BM = b \sin \frac{\alpha}{2}, MQ = BQ - BM = (a - b) \sin \frac{\alpha}{2}$, etc.

The answer is the following:

$$S = \frac{1}{2} (a - b)^2 \sin \alpha.$$

Let us now give an example of a task involving “composing an equation.”

Problem 3 (MSU, Faculty of Geography, 1973). On a given plane there is a right angle. A circle with a center inside an angle touches one side of the angle, intersects the other side at points A and B, and intersects the bisecris of the angle at points C and D; $AB = \sqrt{6}, CD = \sqrt{7}$. Find the radius of the circle.

Let $O$ be the center of the circle, $R$ its radius, $M$ the point of tangency (Fig. 4). The distance from the center to AB is denoted by x. You can immediately create the first equation: $R^2 - x^2 = AN^2$.

Let us give $OP \perp CD$, $OP = \frac{OE}{\sqrt{2}} = \frac{R - x}{\sqrt{2}}$. Now we can create the second equation:

$$R^2 - \left( \frac{R - x}{\sqrt{2}} \right)^2 = CP^2.$$

Let's use the fact that $AN = \frac{\sqrt{6}}{2}$,

⟦folio 47⟧

$$CP = \frac{\sqrt{7}}{2},$$ and create a system
$$\begin{cases} R^2 - x^2 = \frac{6}{4}, \\ R^2 - \left( \frac{R - x}{\sqrt{2}} \right)^2 = \frac{7}{4}. \end{cases}$$

Solving it, we find $R = \sqrt{2}$.

When solving a problem involving “composing equations,” there is often no need for the number of unknowns and the number of equations to coincide. It is important that when constructing equations, all correspondences arising from the condition are used. If this requirement is met, then the necessary unknown or combination of unknowns must be determined by the composite system.

A similar system can also be found in “direct counting” problems.

Problem 4. Circles of radii $R$ and $r$ ($R > r$) touch internally at point $A$. The chord CD of the larger circle is perpendicular to the diameter $AB$ of the smaller circle, $E$ is the point of intersection of $CD$ with a circle of radius $r$, points $E$ and $C$ lie one side away from $AB$. Find the radius of the circle circumscribed about the triangle $AEC$.

We denote $\triangle CEA$ by $\varphi$ and $AF$ by $a$ (Fig. 5). From the triangle $CAM$ we obtain $AC = \sqrt{2aR}$, similarly to $AE = \sqrt{2ar}$. Using the sine theorem from triangle $AEC$ we obtain for the original radius the value

$$\frac{AC}{2 \sin \varphi}.$$ The value of sin $\varphi$ is easy to find from triangle $FEA$. Answer: $\sqrt{Rr}$.

We had to introduce the parameters $a$, $\varphi$, since the condition of the problem did not determine the geometric configuration to be complete. But these parameters are not included in the answer.

Problem 5 (MIPT, 1967). In a right triangle $ABC$ kamet $AB = 3$, kamet $AC = 6$. The centers of circles of radii 1, 2 and 3 are respectively at points $A$, $B$ and $C$. Find the radius of the circle externally tangent to each of the three given circles.

Let $O$ be the center of the desired circle, $x$ its radius, $\angle OAC = \alpha$ (Fig. 6). Let us write down the cosine theorem for triangles $AOC$ and $AOB$. We obtain a system of equations
$$\begin{cases} (x+3)^2 = (x+1)^2 + 36 - 12(x+1)\cos \alpha, \\ (x+2)^2 = (x+1)^2 + 9 - 6(x+1)\sin \alpha. \end{cases}$$

By expressing sin $\alpha$ and cos $\alpha$ from these equations and using the correspondence $\sin^2 \alpha + \cos^2 \alpha = 1$, we obtain an equation containing only one unknown $x$; Having solved this equation, we get the answer: $x = \frac{8\sqrt{11} - 19}{7}$.

Note that the use of the cosine theorem for composing equations is one of the most frequently used and plays a whole

⟦folio 48⟧

Ma plays an important role in solving geometric problems; here a lot depends on experience and intuition.

Problem 6 (MIPT, 1966). The bisectors AM and BN of the reeology ABC intersect at point O. It is known that AO = $\sqrt{3}$ MO, NO = $(\sqrt{3}-1)$ BO. Find the ABC reeology lesson.

Let us introduce the following unknowns (Fig. 7): BC = x, AC = y, AB = z. $\frac{MC}{BM} = \frac{AC}{AB}$, so MB = $\frac{zx}{y+z}$, similarly AN = $\frac{yz}{x+z}$. Now, having considered the triangles BMA and BAN with bisectors BO and AO, it is easy to obtain the following system of equations:

$$\begin{cases} \frac{x}{z+y} = \frac{1}{\sqrt{3}}, \\ \frac{y}{x+z} = \sqrt{3}-1. \end{cases}$$

Next, you can express all the unknowns in terms of one thing (for example, in terms of x) and use the cosine theorem to find the angles of the triangle - $30^\circ$, $60^\circ$ and $90^\circ$. Try to solve this problem using unknown starting angles, and you will see that the solution becomes much more complicated.

It is necessary to note the fact that most problems solved by the algebraic method can have two solutions - both “direct calculation” and “composition of equations”; these methods do not interact with each other.

Problem 7. Inside the acute angle $\alpha$, take a point A, distant from the side of the angle at p and q. Find the distance from point A to the vertex of the corner.

Let M be the intersection point of AC and OB (Fig. 8), it is easy to see that $\triangle BAM = \alpha$. Now we find MC = q + $\frac{p}{\cos \alpha}$, OC = MC $\cdot$ctg $\alpha$ = $\frac{q \cos \alpha + p}{\sin \alpha}$. We find the required distance AO from triangle AOC:

$$AO = \frac{\sqrt{p^2 + 2pq \cos \alpha + q^2}}{\sin \alpha}.$$

This is a “direct count”. Meanwhile, it is not difficult to solve the problem and “make up equations”, and the solutions to bypass the paths, please, are not inferior to each other in diversity. So, “make up equations.”

Let us introduce the unknowns $\triangle AOC = \varphi$, AO = x. Having examined the triangles AOB and AOC, we compose a system of two equations with two unknowns:

$$\begin{cases} x \sin \varphi = q, \\ x \sin (\alpha - \varphi) = p. \end{cases}$$

Solve this system yourself.

If you once again carefully review the examples given in the articles, it is easy to notice that in almost all the examples some additional constructions were made using a number of geometric considerations. So, solving the planimetric

⟦folio 49⟧

Fig. 9.

algebraic method, we should not forget that this is a planimetric problem, not an algebraic one, that is, many geometric considerations cannot be used, since they usually forgive solutions. Otherwise, you can turn a simple geometric problem into a more cumbersome algebraic one, as is the case, for example, when solving the following problem with the authors of the same admissions manual.

Task 8 (MSU, Faculty of Geography, 1969). In the equilibrium trapezoid ABCD, the bases AD = 12, BC = 6, the height of the trapezoid is 4. Design_AC divide the angle BAD of the trapezoid into angles BAC and CAD. Which of these angles is greater?

The solution to this problem, proposed in the mentioned manual, was as follows. Let $\Rightarrow BAC = \alpha$ (Fig. 9), $\Rightarrow CAD = \beta$. You can first calculate $tg \Rightarrow BAD = tg(\alpha + \beta)$, then $tg \beta$ and finally, using trionometric formulas, find $tg \alpha$. Comparing $tg \alpha$ and $tg \beta$, we get the answer to the question posed in the problem. Meanwhile, a significant solution is to notice that $\Rightarrow BCA = \beta$ and $AB = 5$ (by the Pythagorean theorem). From triangle $ABC > \beta$, since in a triangle there is a larger angle opposite the larger side.

Exercises
1 (MSU, Faculty of Geography, 1966). In an equilibrium trapezoid, the bases are $a$ and $b$, and the angle of the dinagoal with the base is $\alpha$. Find the length of the segment connecting the point of intersection of the diagonals with the middle of the side of the trapezoid.

2 (MSU, physicist, 1963). In a circle of radius $R$ through a point $M$ of diameter a chord $AB$ is drawn at an angle $\varphi$ to the diameter; at the same time $BM : AM = p : q$. Through point $B$ a chord $BC$ is drawn, perpendicular to the given diameter, and point $C$ is connected to point $A$. Find the area of ​​triangle $ABC$.

3 (MSU, Faculty of Economics, 1968). In the trapezoid $ABCD$ the angles at the larger base $a$ are $\alpha$ and $\beta$, and the height of the trapezoid is $h$. Let $O_1, O_2, O_3, O_4$ be the centers of the circle circumscribed respectively about the triangles $ABC, BCD, CDA, DAB$. Find the area of ​​quadrilateral $O_1O_2O_3O_4$.

4. Circles of radii $R$ and $r$ intersect. Let us draw a common tangent to them. Let the point $A$ of intersection of the circle and the tangent points $B$ and $C$ lie on opposite sides of the center lines. Find the radius of the circle circumscribed about the triangle $ABC$.

5 (MSU, Mechanical Engineering, 1968). In a convex quadrilateral $ABCD$, the bisset of angle $ABC$ intersects side $AD$ at point $M$, and the perpendicular dropped from vertex $A$ to side $BC$ intersects $BC$ at point $N$ so that $BN = NC$ and $AM = 2MD$. Find the sides and area of ​​the quadrilateral $ABCD$ if its perimeter is $5 + \sqrt{3}$, $\Rightarrow BAD = 90^\circ$, $\Rightarrow ABC = 60^\circ$.

6 (MIPT, 1967). Circles of radii $R$ and $r$ touch internally at point $A$. Find the side of a regular triangle $ABC$ whose vertices $B$ and $C$ lie respectively on a circle of radius $R$ and $r$.

7. The straight line $l$ intersects the lateral sides $AB$ and $BC$ of the isosceles triangle $ABC$, respectively, at points $M$ and $N$. It is known that $\frac{AM}{BM} = m$, $\frac{CN}{BN} = n$. Find the ratio in which the line divides the altitude of the triangle dropped from the vertex $B$.

8 (MSU, physicist, 1969). In the triangle $ABC$ ($AB \neq AC$) the medians drawn from the vertices $B$ and $C$ to the sides $AC$ and $AB$. accordingly, are inversely proportional to these sides. Find sides $AC$ and $AB$ of the triangle if $BC = a$, $\Rightarrow BAC = a$.

9 (MSU, Mechanical Engineering, 1971). You can write in the quadrilateral $ABCD$ and you can draw a circle around it. The diagonals of this quadrilateral are mutually perpendicular. Find its area if the radius of the circle is $R$ and $AB = 2BC$.

10 (MSU, physicist, 1974). Two identical regular triangles $ABC$ and $CDE$ from side 1 are located on the plane so that they have only one common point $C$, and $\Rightarrow BCD < \pi/3$. Point $K$ is the middle of $AC$, $L$ is the middle of $CE$, $M$ is the middle of $BD$. The area of ​​triangle $KLM$ is equal to $\sqrt{3}/5$. Find $BD$.
