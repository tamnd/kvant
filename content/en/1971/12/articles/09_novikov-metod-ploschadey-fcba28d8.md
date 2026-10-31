---
id: 1971-12-novikov-metod-ploschadey-fcba28d8
issue: kvant_1971_12
year: 1971
number: "12"
title: Area method
authors:
  - Новиков И. Д.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 43
page_last: 48
page_labels: 41-46
tag: E30X
lang: en
source: kvant_digital
extraction: vision
content_sha256: e940b5f4ed5648eb1c5458a789ff1815272f81bad503b3c1328b960aa2f2f86e
prompt_sha256: draft-1
translated_from: content/ru/1971/12/articles/09_novikov-metod-ploschadey-fcba28d8.md
source_content_sha256: 755d1fe537be7c22e90f01e39efa4ec139f396fb416e17b91ac6188746039d9c
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 41⟧

The art of solving geometric problems is somewhat reminiscent of trio or lozonists - sometimes, even knowing the solution to a problem, it is difficult to understand how one could come up with it. Almost every somewhat difficult geometric problem requires an individual approach. But I would like to have a general solution method, which would also allow the solution to be “adventured” to the end without carrying out calculations explicitly.

Unfortunately, there is no such universal method. But there are techniques applied to many problems. We will consider one of them.

Let's start with a very simple problem, which we will solve in two ways.

Fig. 1. AC = 2, BC = 3, ⇒ ACD = ⇒ DCB = = 45°.

Problem 1. Find the bicsectrix CD of a right triangle ACB with legs AC = 2 and BC = 3 (Fig. 1).

Solution I. By Pythagorean theorem AB = √AC² + BC² = √13. By the property of the bicsectrix of the angle of a triangle inside it

$$\frac{AD}{BD} = \frac{AC}{BC}.$$

From the equality AD + DB = √13 we obtain AD = \frac{2}{5} √13. Next, it’s easy to find the cosine of angle A:

$$\cos A = \frac{AC}{AB} = \frac{2}{\sqrt{13}}.$$

It remains to apply the cosine theorem to determine side CD of triangle ACD:

$$CD^2 = AC^2 + AD^2 - 2AC \cdot AD \cos A = \frac{72}{25}, CD = \frac{6}{5} \sqrt{2}.$$

Solution II. Let's calculate the area of ​​triangle ACB in different ways. On the one hand, S△ACB = \frac{1}{2} AC \cdot BC = 3. On the other hand,

$$S△ACB = S△ACD + S△DCB = \frac{1}{2} AC \cdot CD \sin 45^\circ + \frac{1}{2} BC \cdot CD \sin 45^\circ = \frac{5 \sqrt{2}}{4} CD.$$

⟦folio 42⟧

Equating the part of the two given expressions for $S_{\Delta ACB}$, we obtain $CD = \frac{6}{5}\sqrt{2}$.

The second solution is clearly shorter and simpler. Moreover, it easily leads to the goal in a more general situation. To verify this, find out for yourself how both of these solutions change if

Task 2. Find the bisector $CD$ of $C$ of triangle $ACB$ if $AC=b$, $BC=a$, $\Rightarrow ACB=\alpha$. (Say: $CD = \frac{2ab}{a+b}\cos \frac{\alpha}{2}$)

However, the main advantage of the second solution is its ideological “originality”. In the first solution, a certain “chain” of triangle elements is constructed: each element of this chain is calculated based on the problem data and other elements already found. The last element of the chain is the desired quantity (in this case, the bisector $CD$). At the same time, it is not immediately clear which elements will be needed when determining the desired value, that is, which elements must be pre-calculated.

In the second solution for the quantity that needs to be found, we obtain an equation by writing out expressions for the area of ​​the triangle in terms of the known and desired elements of the triangle. This example - comparing different expressions for the area of ​​a triangle - turns out to be very fruitful. Why specifically for the area? The fact is that the plane of a triangle is quite simply expressed through various combinations of elements of this triangle.

Before giving the following examples, let us recall the most important of these expressions. First, let's agree on notation. In triangle $ABC$:

$a, b, c$ - sides, opposite angles $A, B$ and $C$ respectively;

$h_a, h_b, h_c$ — heights, $m_a, m_b, m_c$ — medians, $l_a, l_b, l_c$ — bisectors, respectively;

$r$ — radius of the inscribed circle;

$R$—radius of the circumscribed circle;

$p$ - half-perimeter;

$S$ are planar triangles $ABC$.

Fig. 2. About the center of the inscribed circle.

The formulas that we will use are written in this notation as follows:

$$S = \frac{ah_a}{2},$$

$$S = \frac{ab \sin C}{2},$$

$$S = \frac{a^2 \sin B \sin C}{2 \sin A},$$

$$S = \frac{abc}{4R},$$

$$S = \sqrt{p(p-a)(p-b)(p-c)},$$

$$S = pr.$$

All these relationships are known from the school course, so we will not prove them in detail, but will limit ourselves to just a few comments. To derive formulas (3) and (4) from (2), you can use the sine theorem:

$$\frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C} = 2R.$$

Formula (5) (Heron’s formula) is sometimes more convenient to use in a transformed form:

$$S = \frac{1}{4} \times \sqrt{2a^2b^2 + 2a^2c^2 + 2b^2c^2 - a^4 - b^4 - c^4}.$$

Formula (6) is easily obtained from a very (Fig. 2) equality:

$$S_{\Delta ABC} = S_{\Delta AOB} + S_{\Delta BOC} + S_{\Delta COA}.$$

Let's now consider a few more problems. In each of them, the application of the area method leads to a short and pronounceable solution.

⟦folio 43⟧

Task 3. Inside a regular triangle with sides a, take an arbitrary point M. Find the sum of the distances from this point to the sides of the triangle.

Solution. It is necessary to find the sum of the lengths of the perpendiculars MP, MQ and MR (Fig. 3) dropped from the point M to the sides AB, BC and CA, respectively. If we connect the point M with the vertices of the triangle, then it is clear that $S_{\Delta ABC} = S_{\Delta AMB} + S_{\Delta BMC} + S_{\Delta CMA}$. Using the formula for the area of ​​a regular triangle $S_{\Delta ABC} = \frac{a^2 \sqrt{3}}{4}$ and replacing that (by formula (1)).

$$S_{\Delta AMB} = \frac{1}{2} a \cdot MP,$$

$$S_{\Delta BMC} = \frac{1}{2} a \cdot MQ,$$

$$S_{\Delta CMA} = \frac{1}{2} a \cdot MR,$$

we immediately receive the answer:

$$MP + MQ + MR = \frac{a \sqrt{3}}{2}.$$

Task 4. Line AD divides triangle ABC into two. Prove that the radius r of the circle inscribed in triangle ABC is less than the sum of the radii $r_1$ and $r_2$ of the circle inscribed in triangles ABD and ACD, respectively.

Solution. Let CD and CE be the rays that are discussed in the conditions of the task (Fig. 5). Obviously $S_{\Delta ABC} = S_{\Delta ACD} + S_{\Delta DCB} = S_{\Delta ACE} + S_{\Delta ECB}$.

Let us use formula (2), taking into account that $ACD = DCE = ECB = \frac{\alpha}{3}$:

$$\frac{AC \cdot DC \sin \frac{\alpha}{3}}{2} + \frac{DC \cdot BC \sin \frac{2\alpha}{3}}{2} = \frac{AC \cdot EC \sin \frac{2\alpha}{3}}{2} + \frac{EC \cdot BC \sin \frac{\alpha}{3}}{2}.$$

⟦folio 44⟧

Fig. 5.

From here we immediately get

$$\frac{DC}{EC} = \frac{AC \sin \frac{2\alpha}{3} + BC \sin \frac{\alpha}{3}}{AC \sin \frac{\alpha}{3} + BC \sin \frac{2\alpha}{3}}$$

$$= \frac{2 \cos \frac{\alpha}{3} + 3}{6 \cos \frac{\alpha}{3} + 1}$$

Here is an example of a more difficult problem. Although in it you simply need to “solve the triangle”, that is, determine its sides by three known elements, it is not possible to obtain a solution in the usual way - using the theorems of sines and cosines.

Task 6. Name triangle ABC if $h_a=6$, $r=2$, $R=5$.

Solution and e. Let us use formulas (1), (4), (5) and (6) and write the following system of equations for the unknown sides $a, b, c$

$$\begin{cases} S = 3a, \\ S = \frac{abc}{20}, \\ S = \frac{1}{4} \sqrt{(a+b+c)(b+c-a)} \times \sqrt{(a+c-b)(a+b-c)}, \\ S = a+b+c. \end{cases}$$

Equating the rules of the parts of the first and last equations, we obtain that $b+c=2a$. Equating the rules for parts of the first and second equations, we obtain that $bc=60$. Finally, equating the rules for parts of the first and third equations, we obtain (after squaring) that

$$144a^2 = (a+b+c)(b+c-a) \times (a+c-b) \times (a+b-c) = [(b+c)^2-a^2] \times [a^2-(b-c)^2] = [(b+c)^2-a^2] \times [a^2-(b+c)^2+4bc] = (4a^2-a^2) \times (a^2-4a^2+240) = 3a^2 (240-3a^2).$$

Therefore, to determine $a$ we obtain the equation

$$144a^2 = 3a^2 (240-3a^2),$$

whence $a=8$. From the system of equations $b+c=16$, $bc=60$ it is now easy to find two pairs of values ​​$b$ and $c$ (two answers):

$$a = 8, b = 6, c = 10 или a = 8, b = 10, c = 6,$$

which are the geometric definitions of odin triangle (to the point of designating the sides $b$ and $c$).

In this example, the main feature of the area method is especially clearly visible - it “makes” an algebraic problem out of a geometric problem, reducing everything to solving some systems of equations.

Task 7. (MSU, physicist, 1966) Prove that if the lengths of the sides of a triangle form an arithmetic

⟦folio 45⟧

Fig. 6a.

the metische cut, the center of the circle inscribed in this triangle, and the intersection point of its median lie on a straight line parallel to the middle side of the triangle.

Solution. Let the sides of triangle ABC be shaped so that $a \leq b \leq c$. Then according to the conditions of problem $a+c=2b$. Let $O$ be the center of the incircle and $M$ the intersection point of the medians $AA_1$, $BB_1$ and $CC_1$ (Fig. 6a).

First, we derive one useful property of the point $M$ of intersection of the median of triangle $ABC$. On figure 6b, triangle ABC is divided by medians into 6 smaller triangles. The area of ​​each of them is equal to $\frac{1}{6}$ the area of ​​the entire triangle $ABC$. This is very easy to prove: using

Fig. 66.

formula (1), writing the equality
$$S_{\triangle BB_1C} = \frac{1}{2} S_{\triangle ABC}, B_1M = \frac{1}{3} BB_1,$$
$$S_{\triangle MCB_1} = \frac{1}{3} S_{\triangle BB_1C} = \frac{1}{6} S_{\triangle ABC}.$$

The area of ​​the remaining triangles can be found similarly.

Now let’s find the length of the perpendicular $MM'$ dropped from the point $M$ to the side $AC$:
$$\frac{1}{3} S_{\triangle ABC} = S_{\triangle AMC} = \frac{1}{2} MM' \cdot AC =$$
$$= \frac{1}{2} MM' \cdot b, \frac{1}{3} S_{\triangle ABC} = \frac{1}{3} rp =$$
$$= \frac{1}{3} r \left( \frac{a+b+c}{2} \right) = \frac{1}{3} r \left( \frac{2b+b}{2} \right) =$$
$$= \frac{1}{2} rb,$$

whence $MM'=r$, that is $MO \parallel AC$.

The area method often turns out to be convenient at certain stages of solving stereometric problems.

Task 8. (MSU, mechanism, 1969) A pyramid is inscribed in a ball, the side edges of the side are equal to c. Its base is a rectangular plane, the sides of which are connected by the arcs $\alpha$ and $\beta$ radians in the sections of the ball by the planes of the lateral faces. Determine the radius of the circumscribed sphere.

Solution (Fig. 7). Since the inscribed angle changes by half

⟦folio 46⟧

no arc on which it rests,
That
$$\Rightarrow DQC = \frac{\alpha}{2}, \Rightarrow AQD = \frac{\beta}{2}.$$

Pozny $DC = 2c \sin \frac{\alpha}{4}$, $AD = 2c \sin \frac{\beta}{4}$.

Let us consider the section of the ball by the plane $AQC$. Since the center of the ball lies in this plane (prove it!), the radius of the ball is equal to the radius $R$ of the circle circumscribed about the triangle $AQC$. But $AQ = QC = c$, and $AC = 2c \sqrt{\sin^2 \frac{\alpha}{4} + \sin^2 \frac{\beta}{4}}$ (like the diagonal of a rectangle $ABCD$). Therefore, to determine the radius $R$, it is enough to use the expressions for the area of ​​the triangle $AQC$ using formulas (4) and (5).

As a result of obvious transformations, we get the answer:

$$R = \frac{c}{\sqrt{2 \left( \cos \frac{\alpha}{2} + \cos \frac{\beta}{2} \right)}}.$$

The area method is also convenient to use in problems in which it is necessary to find various types of estimates for geometric quantities.

Problem 9. Within what limits can the ratio of the radius of a circle described in a right triangle to the height lowered by one change?

Solution. If $c$ is the hypotenuse of the right triangle $ABC$, then we can write (see formulas (1) and (6)):

$$\frac{ch_c}{2} = pr, \text{откуда} \frac{r}{h_c} = \frac{c}{2p}.$$

Thus, it is necessary to evaluate the relationship

$$\frac{c}{2p} = \frac{c}{a + b + c} = \frac{1}{\frac{a}{c} + \frac{b}{c} + 1} = \frac{1}{\sin A + \sin B + 1}.$$

Since $A + B = 90^\circ$, then

$$\sin A + \sin B + 1 = \sin A + \cos A + 1 = \sqrt{2} \cos (45^\circ - A) + 1.$$

The acute angle $A$ of a right triangle can be any value between 0 and 90^\circ. Therefore, the angle $45^\circ - A$ is smaller in the range from $-45^\circ$ to $+45^\circ$, as can be easily obtained from the properties of the cosine, while $2 < \sqrt{2} \cos (45^\circ - A) + 1 \leqslant 1 + \sqrt{2}$.

Consequently, in any right-angled triangle, an indefinite solution to many problems is always satisfied. Of course, it does not replace all other methods, but it is an approach that should not be forgotten when starting to solve a particular problem.

Exercises

1. Find the median $m_a$ of the triangle, the value of its side $a, b, c$.
2. Prove that in an arbitrary triangle

$$\frac{1}{r} = \frac{1}{h_a} + \frac{1}{h_b} + \frac{1}{h_c}.$$

3. (MSU, Faculty of Economics, 1969). In an acute triangle $ABC$ given: $AB = c$ drawn from the vertex $B$ median $BD = m$. Angle $BDA$ is acute and equal to $B$. Calculate the area of ​​triangle $ABC$.
4. (MSU, Faculty of Psychology, 1969). Given an equilateral right triangle. Prove that the radius of the circle tangent to the hypotenuse and extensions of the legs is equal to the sum of the hypotenuse and the radius of the circle described in the triangle.
5. It is known that in the triangle $ABC$:

$$S_{\triangle ABC} = 16, m_a = 6, m_b = 4.$$

Prove that the medians $m_a$ and $m_b$ are perpendicular.
6. Prove that the sum of the distances from an arbitrary point taken inside an unequally lateral triangle to the side of this triangle is enclosed between the smallest and lowest point.

7. The base $ABCD$ of the straight line $ABCDA_1B_1C_1D_1$ (where $AA_1, BB_1, CC_1, DD_1$ are the side edges) is a rhombus on the side $a$ and an acute angle $φ$, and the height of the line is $h$. Find the distance from the vertex $B_1$ to the diagonal $A_1D$ of the side face $ADD_1A_1$.
