---
id: 1972-10-grudenov-metod-resheniya-zadach-s-kontsa-69ce3b22
issue: kvant_1972_10
year: 1972
number: "10"
title: Method of solving problems “from the end”
authors:
  - Груденов Я. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 49
page_last: 53
page_labels: 47, 48, 50, 51
tag: DPHK
lang: en
source: kvant_digital
extraction: vision
content_sha256: c7c0ba096c0b3d48e72d147a419315ac75514098ce45b896d40ca5aa5d588956
prompt_sha256: draft-1
translated_from: content/ru/1972/10/articles/12_grudenov-metod-resheniya-zadach-s-kontsa-69ce3b22.md
source_content_sha256: 531f1bb66fe344036d290266aac5927f3cb137023875c66c02f276300cef435a
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 47⟧

Method of solving problems “from the end”

Typically, we solve a problem or prove a theorem from the known to the unknown, from the given to the desired. But you can act differently. Here we will consider the method of solving problems “from the end”, when reasoning is carried out from the unknown to the known, from the desired to the given.

General scheme

Let it be necessary to prove some assertion $A$. Let us assume that it is true, and based on the data of the problem and known theorems, we will try to obtain the correct corollary from $A$. In this case, several cases are possible.

1. An incorrect result was obtained. This means that our assumption about the validity of the statement $A$ is wrong. Solving the problem with this law - we found that $A$ is incorrect.

2. An incorrect result was obtained. In this case, you should check the reversibility of the argument, because from an incorrect statement (for example, $a = -a$, $a \neq 0$) you can also obtain a correct consequence ($a^2 = a^2$).

a) If all reasoning is reverse, then $A$ is true.

b) If among the arguments there are irreversible ones (for example, at some stage we squared the equality), then it comes to using other methods of finding a solution to the problem.

3. If a correct consequence cannot be obtained, then it is also time to move on to other methods.

Two instructions

1. In the resulting intermediate expressions, it is desirable to reduce the number of parameters and then simplify these expressions.

2. If the task does not contain unnecessary conditions *, then all task data must be used.

Examples

Example 1. In a right triangle ABC, the number AC is three times greater than the number AB. Point K and M of the AC stones is divided into three equal parts. Prove that $\triangle AMB + \triangle AKB + \triangle ACB = 90^\circ$.

Solution e. Let $\triangle AMB = \alpha$, $\triangle AKB = \beta$, $\triangle ACB = \gamma$ (Fig. 1). Suppose $\alpha + \beta + \gamma = 90^\circ$ (1)

or, since $\alpha = 45^\circ$,

$$\beta + \gamma = 45^\circ.$$ (1a)

Then

$$tg(\beta + \gamma) = tg 45^\circ,$$ (2)

$$\frac{tg \beta + tg \gamma}{1 - tg \beta \cdot tg \gamma} = 1.$$ (2a)

*) Finding the line of its conditions is a big advantage of the solution, but usually competitive line problems do not contain their conditions.

⟦folio 48⟧

Equality (2) or (2a) is true, since
$$tg \beta = \frac{AB}{AK} = \frac{1}{2}, \quad tg \gamma = \frac{1}{3}$$

And
$$\frac{\frac{1}{2} + \frac{1}{3}}{1 - \frac{1}{2} \cdot \frac{1}{3}} = 1.$$

Students generally finish solving the problem, which is

**Fig. 1.**

a blunder. Starting to reverse the transformations, we notice that from the validity of equality (2) it follows not equality (1a), but dependence
$$\beta + \gamma = 45^\circ + 180^\circ \cdot n,$$
where $n = 0; \pm 1; \pm 2; \pm 3; \dots$

But from the triangles $AKB$ and $ACB$ we find that $0 < \beta < 45^\circ; 0 < \gamma < 45^\circ$ therefore
$$0 < \beta + \gamma < 90^\circ.$$

Therefore, from correspondences (2) and (3) it follows that $\beta + \gamma = 45^\circ$, and, since $\alpha = 45^\circ$, then $\alpha + \beta + \gamma = 90^\circ$.

Example 2. Prove that in any triangle $R = \frac{a \cdot b \cdot c}{4S}$, where $a, b, c$ are the sides of the triangle, $S$ is its area, $R$ is the radius of the circumscribed circle.

Solution e. Suppose that the equality is true:
$$R = \frac{a \cdot b \cdot c}{4S}.$$

Let's reduce the number of parameters:
$$R = \frac{a \cdot b \cdot c}{4 \cdot \frac{1}{2} b \cdot c \cdot \sin A}, \quad R = \frac{a}{2 \cdot \sin A},$$

where
$$2R = \frac{a}{\sin A},$$

which is true by the law of sines. All transformations are easy to process, therefore equality (4) is proven.

Example 3. The sides of the triangle $a, b, c$ ($a < b < c$) form an arithmetic process. Prove that $ac = 6Rr$, where $R$ is the radius of the circumscribed circle, $a$ $r$ is the radius of the circumscribed circle in the triangle.

Solution e. Let the equality $ac = 6Rr$ be true. Let's reduce the number of parameters by expressing $R$ and $r$ in terms of the sides of the triangle: $R = \frac{abc}{4S}, r = \frac{S}{p}$, where $S$ is the area of ​​the triangle, $p$ is its half-perimeter. We get:
$$ac = 6 \cdot \frac{abc}{4S} \cdot \frac{S}{p}, \quad 1 = \frac{3b}{2p},$$
$$a + b + c = 3b, \frac{a + c}{2} = b,$$

which is true, since $a, b, c$ constitute an arithmetic process.

All these transformations can be checked in reverse order, therefore, the correspondence being proved is correct.

Example 4. Prove that the product of the diagonals of a suspended figure is equal to the sum of the product of the opposite sides (Ptolemy’s theorem).

Solution e. Suppose that equality (Fig. 2) is true:
$$AC \cdot BM = AM \cdot BC + AB \cdot CM.$$

Let's reduce the number of parameters by expressing all segments in terms of some other elements. The need to use all the data of the task (quadruple - vissanny) brings us to the idea

⟦folio 50⟧

where
$$\sin(\alpha + \beta) \cdot \cos \alpha = 2 \sin \alpha \times \cos (\alpha + \beta);$$
$$\left( \alpha + \beta \neq \frac{\pi}{2} + \pi k; \quad \alpha \neq \frac{\pi}{2} + \pi n \right);$$
$$\frac{1}{2} \left[ \sin (2\alpha + \beta) + \sin \beta \right] =$$
$$= 2 \cdot \frac{1}{2} \left[ \sin (2\alpha + \beta) + \sin (-\beta) \right);$$
$$3 \sin \beta = \sin (2\alpha + \beta),$$

which is true according to the conditions of the problem.

These transformations can be proved in reverse order (for all valid values ​​of the arguments), so equality (9) is true.

Example 7. Prove that for all admissible values ​​of $\alpha$ we have the inequality
$$|\mathrm{tg} \alpha + \mathrm{ctg} \alpha| > |\sin \alpha + \cos \alpha|.$$ (11)

Solution e. Suppose that inequality (11) is true. Let's reduce the number of functions:
$$\left| \frac{\sin^2 \alpha + \cos^2 \alpha}{\sin \alpha \cos \alpha} \right| > |\sin \alpha + \cos \alpha|;$$ (12)
$$\frac{1}{|\sin \alpha \cdot \cos \alpha|} > |\sin \alpha + \cos \alpha|.$$ (13)

To compare the magnitude of these expressions, it is advisable to express them through one function, for example, through a sine:
$$\frac{2}{|\sin 2\alpha|} > \sqrt{2} |\sin \left( \alpha + \frac{\pi}{4} \right)|.$$ (14)

But $|\sin 2\alpha| \leqslant 1$, $|\sin \left( \alpha + \frac{\pi}{4} \right)| \leqslant 1$, therefore $\frac{2}{|\sin 2\alpha|} \geqslant 2$, and $\sqrt{2} |\sin \left( \alpha + \frac{\pi}{4} \right)| \leqslant \sqrt{2}$, and inequality (14) is true for all admissible values ​​of $\alpha$.

From inequality (14) follows (13), and hence (12), and from inequality (12) follows (11), therefore inequality (11) is true for all $\alpha \neq \frac{\pi k}{2}$.

The above reasoning shows that it is possible to prove a stronger inequality
$$|\mathrm{tg} \alpha + \mathrm{ctg} \alpha| \geqslant \sqrt{2} |\sin \alpha + \cos \alpha|.$$ (50)

Example 8. Prove that in every triangle
$$h_a > \sqrt{p(p-a)},$$ (15)

where $h_a$ is the height lowered to side $a$, $p$ is the meter of the triangle.

Solution e. Let inequality (15) be true. Let's reduce the number of parameters:
$$\frac{\sqrt{p(p-a)(p-b)(p-c)}}{1/2 a} > \sqrt{p(p-a)}.$$

We used the formulas
$$S_\Delta = \frac{1}{2} h_a \cdot a,$$
$$S_\Delta = \sqrt{p(p-a)(p-b)(p-c)},$$
$$\sqrt{(p-b)(p-c)} > \frac{1}{2} a.$$

Both sides of the inequality are positive - they can be squared
$$(p-b)(p-c) > \frac{a^2}{4},$$
$$\frac{a+c-b}{2} \cdot \frac{a+b-c}{2} > \frac{a^2}{4},$$
$$a^2 + ab - ac + ac + bc - c^2 - ab - b^2 + bc > a^2,$$
$$2bc - c^2 - b^2 > 0,$$
$$-(b-c)^2 > 0,$$

which is not true. Therefore, our assumption about the validity of inequality (15) is false.

At this point, the solution to the problem can be considered complete, or we have proven that formula (15) is incorrect. However, having proven that formula (15) is incorrect, we thereby proved that the formula is always correct
$$h_a \leqslant \sqrt{p(p-a)}.$$

Try to figure out when equality occurs in the last formula. Here our method of solving the problem “from the end” turns into a method “by contradiction”.

This method of solving geometric problems has certain similarities with the described method, when the required

⟦folio 51⟧

and other unknown elements (segments, angles, etc.) are designated by the letters $x, y, z, \dots$ and treated as if they were known.

Example 9. In a seed containing 120°, a square is inscribed. Find the side of the square if the radius of the circle is $R$.

Solution. Let $ABCK$ be a square, $\cup EF = 120^\circ$, $O$ the center of a circle (Fig. 3). Let's denote

Fig. 3.

$BC$ through $2x$ and draw $OP \perp EF$. Then $ON = \sqrt{R^2 - x^2}$, $OM = \frac{1}{2}R$, $MN = 2x$, $OM = ON - MN$.

We have the equation
$$\frac{R}{2} = \sqrt{R^2 - x^2} - 2x$$
solving which, we get $x = \frac{R(\sqrt{19} - 2)}{10}$

Answer: $\frac{R(\sqrt{19} - 2)}{5}$.

Many students make mistakes not only when solving problems, but also when presenting theoretical issues. Here is how, for example, they prove a well-known identity:
$$\log_a \left( \frac{x}{y} \right) = \log_a x - \log_a y$$
(at $x > 0$ and $y > 0$).

“Let us move $\log_a y$ to the left side and use the previously proven theorem:
$$\log_a \left( \frac{x}{y} \right) + \log_a y = \log_a x$$
$$\log_a \left( \frac{x}{y} \cdot y \right) = \log_a x$$
$$\log_a x = \log_a x.$$

We have obtained the correct equality, which means the original formula has been proven.”

It is clear that these arguments have not yet proven the formula. Students usually, not even understandably, swear at the school textbook, where the formula is proven, they say, in exactly the same way. For them, the reference in the textbook to the equivalence of formulas went unnoticed.

Exercises

1. In an equilateral triangle with base $a$ and side $b$, the angle at the vertex is $20^\circ$. Prove that $a^3 + b^3 = 3ab^2$.

2. Prove that in a convex quadrilateral, the bissertrices of angles adjacent to one side form an angle equal to half the sum of the other two angles.

3. Prove inequality
$$\text{ctg} \frac{\varphi}{2} > 1 + \text{ctg} \varphi$$ at $0 < \varphi < \frac{\pi}{2}$.

4. Prove the inequality $(x + y)(x + y + 2\cos x) + 2 \geq 2\sin^2 x$. At what values ​​of $x$ and $y$ is equality achieved?

5. In triangle $ABC$, angles $A, B$ and $C$ form a geometric progression with element value 2. Prove that $\frac{1}{a} = \frac{1}{b} + \frac{1}{c}$.

6. Prove that
$$\frac{1}{\log_2 \pi} + \frac{1}{\log_5 \pi} + \frac{1}{\log_{10} \pi} > 4.$$

7. Prove that the maximum total surface of a straight parallelepiped is equal to $\frac{M^2}{24}$, where $M$ is the sum of the lengths of the edges of the parallelepiped.

8. Is it true that the sum of the squares of the diagonals of a trapezoid is equal to the sum of the squares of the lateral sides added to the product of the bases?

9. Check if the following inequality is proven true:
$$\sin^2 \alpha + \sin^2 \beta \geq \sin \alpha \cdot \sin \beta + \sin \alpha \cdot \sin \beta - 1?$$

“Let us rewrite the inequality to be proved in the form
$$2\sin^2 \alpha + 2\sin^2 \beta - 2\sin \alpha \cdot \sin \beta - 2\sin \alpha - 2\sin \beta + 2 \geq 0,$$
or
$(\sin \alpha - 1)^2 + (\sin \beta - 1)^2 + (\sin \alpha - \sin \beta)^2 \geq 0,$
which was very painful."

10. Is it true that $\sin(\cos \varphi) = \cos(\sin \varphi)?$
