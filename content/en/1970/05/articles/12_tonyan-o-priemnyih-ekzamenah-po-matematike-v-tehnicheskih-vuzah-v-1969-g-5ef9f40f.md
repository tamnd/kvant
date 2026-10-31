---
id: 1970-5-tonyan-o-priemnyih-ekzamenah-po-matematike-v-tehnicheskih-vuzah-v-1969-g-5ef9f40f
issue: kvant_1970_5
year: 1970
number: "5"
title: On entrance examinations in mathematics at technical universities in 1969.
authors:
  - Тонян В. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 47
page_last: 49
page_labels: 45-47
tag: X9Q6
lang: en
source: kvant_digital
extraction: vision
content_sha256: 56305341defbeb9944c94254ab7b36c7d86ce896764048ec2b13075e9b93fb90
prompt_sha256: draft-1
translated_from: content/ru/1970/05/articles/12_tonyan-o-priemnyih-ekzamenah-po-matematike-v-tehnicheskih-vuzah-v-1969-g-5ef9f40f.md
source_content_sha256: d5c5f19194dda4b0be0469845ba8f52331315a31bf208e3708f404369cf5afce
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 45⟧

ABOUT FOSTERS
EXAMINATIONS
IN MATHEMATICS
IN TECHNICAL
UNIVERSITIES IN 1969
V. A. TONYAN

EXAMINATIONS AT MIEM

In this article we will talk about the entrance exams in mathematics to the Moscow Institute of Electronic Engineering (MIEM).

As in most technical schools, applicants take two exams in mathematics: written and oral. 4 hours (4×60 minutes) are allotted for written work.

Please note that all proposed questions and tasks do not go beyond the approved program for entrance exams.

Below we present problems taken from the various versions of the written examinations offered in 1969, indicating the most common mistakes made by applicants.

Option 0

1. A motorcyclist and a bicycle rider simultaneously head towards each other from points A and B and meet at a distance of 12 km from the middle of AB. The speed of a motorcycle rider is 32 km/h higher than the speed of a bicycle rider. If the motorcycle rider had left an hour later, they would have met halfway along the way. Find the distance AB.

2. Solve the equation
$$x = a - \sqrt{a^2 - x \sqrt{x^2 + a^2}}.$$

3. Solve inequality
$$\log_{\sqrt{3}} \frac{\sqrt{27}}{\arctg x} \cdot \log_{\sqrt{3}} \arctg x > 2.$$

4. Solve the equation
$$\sin \sqrt{4 + 3x - x^2} + \cos \sqrt{4 + 3x - x^2} = \sqrt{2}.$$

5. The centers of two circles, whose radii are R and r, lie on the hypotenuse of a right triangle. One circle touches two legs, the other touches the leg and the first circle. Find the sides of the triangle.

Let us present the solution to these problems.

1. Let's denote the speed of the speedster by x, and the speed of the speedster AB by 2S; then the motorcyclist’s speed will be x+32. If the time spent by the motorcyclist before the meeting is equal to t, then from the conditions of the problem we obtain
$$xt = S - 12,$$
$$(x + 32)t = S + 12.$$

If 动机iklist had left an hour later, he would have spent $t_1$ hours before the meeting, while 动机iklist would have spent $(t_1-1)$ hours and therefore
$$(x + 32)t_1 = S,$$
$$x(t_1+1) = S.$$

Solving this system, we obtain $S=48$ km.

This task turned out to be easy for applicants. The overwhelming number of applicants solved it. However, a lot of cumbersome systems of equations are due to poor choice of notation.

2. By squaring both sides of this equation, we get
$$x^2 - 2ax = -x \sqrt{x^2 + a^2}$$
or
$$x(2a - x - \sqrt{x^2 + a^2}) = 0.$$

From here
$$x_1 = 0$$ and $2a - x = \sqrt{x^2 + a^2}$.

Squared again, we get $3a^2 = 4ax$ or $a(3a-4x)=0$. Now if a=0,

⟦folio 46⟧

then $x_2 - \text{любое число},$ if $a \neq 0$ then
$$x_2 = \frac{3}{4} a.$$

When performing the transformation (squaring), we could violate the equivalence, so the found roots $x_1, x_2, x_3$ must be checked.

1) $x_1 = 0$. We substitute the value $x_1$ into the original equation. Then the left side is 0, and the right side is:
$$a - \sqrt{a^2} = a - |a| = \begin{cases} 0 & \text{при } a \geq 0, \\ 2a & \text{при } a < 0. \end{cases}$$

2) If $a = 0$, then the left side of the equation is $x$, and the right side is:
$$- \sqrt{-x \sqrt{x^2}} = -\sqrt{-x |x|} = \begin{cases} -\sqrt{-x^2} & \text{при } x > 0, \\ -\sqrt{x^2} & \text{при } x \leq 0. \end{cases}$$

3) Substituting the value $x_3 = \frac{3}{4} a$, we find that the left side is equal to $\frac{3}{4} a$, and the right side is:
$$a - \sqrt{a^2 - \frac{3}{4} a \sqrt{\frac{9}{16} a^2 + a^2}} = \begin{cases} a - \sqrt{\frac{a^2}{16}} = \frac{3}{4} a & \text{при } a > 0, \\ a - \sqrt{\frac{31 a^2}{16}} + a + \frac{a \sqrt{31}}{4} & \text{при } a < 0. \end{cases}$$

Answer. If $a > 0$, then $x_1 = 0$, $x_3 = \frac{3}{4} a$; if $a = 0$, then $x \leq 0$.

A far more typical mistake that applicants made when solving this equation was not checking the found values ​​of $x_1, x_2, x_3$. When solving this equation using the above method, verification is an integral part of solving the problem.

3. Denoting $\log \sqrt{3}$ arcctg $x = t$, we get $t^2 - 3t + 2 < 0$, hence $1 < t < 2$.
Returning to the variable $x$, we can write
$$\sqrt{3} < \text{arcctg} x < 3$$
where we get the answer: $\text{arcctg} 3 < x < \text{arcctg} \sqrt{3}$.

4. Requiring $4 + 3x - x^2 \geq 0$ gives us $-1 \leq x \leq 4$.

Now, applying the addition formulas to the left side, we get
$$\sqrt{2} \sin \left(\sqrt{4 + 3x - x^2} + \frac{\pi}{4}\right) = \sqrt{2},$$
where
$$\sqrt{4 + 3x - x^2} = \frac{\pi}{4} + 2\pi n.$$
This means that $n \geq 0$ is necessary.

Solving this irrational equation, we get
$$x = \frac{3 \pm \sqrt{25 - 4 \left(2\pi n + \frac{\pi}{4}\right)^2}}{2};$$
from here
$$\left(2n\pi + \frac{\pi}{4}\right)^2 = \frac{25}{4}.$$
Therefore, $n = 0$ and $x_{1,2} = \frac{6 \pm \sqrt{100 - \pi^2}}{4}$.

By checking we can easily verify that both of these values ​​are roots of the equation.

In solving this equation, many obtained equality (1), but only part of the constructional studies of this formula left a solution corresponding to $n = 0$.

5. Let $ABC$ be a given triangle, $\rightarrow ACB$ a straight line, $O$ and $O_1$ the centers of circles of radii $R$ and $r$; $D$ and $E$ – points of tangency of the circles of leg $CA$. Let's draw $EF \parallel AB$ and denote $\rightarrow BAC = \alpha$. Then from $\triangle FDE$ we have
$$\sin \alpha = \frac{R - r}{R + r}.$$

Noticing that $CD = R$ and denoting $AC = b$, we obtain from $\triangle ODA$
$$\text{tg} \alpha = \frac{R}{b - R}.$$

From (1) and (2) we can write
$$1 + \left(\frac{R}{b - R}\right)^2 = \left(\frac{R + r}{R - r}\right)^2,$$
whence, solving for $b$, we obtain
$$b = R \left[1 + \frac{2\sqrt{Rr}}{R - r}\right].$$

⟦folio 47⟧

---
running_head:
folio:
---

Now you can find the other side and the hypotenuse. (We suggest you check the calculation yourself.)

In conclusion, we present some options for written work offered at the entrance exams in 1969.

Option 1

1. Two tourists left the city at the same time in the same direction. The first tourist travels every kilometer of the journey 20 minutes faster than the second. Having walked part of the way, the first tourist turned back, and after walking 1 km, he went in the same direction. When the first tourist caught up with the second, the second one had been traveling for 1/2 hour. How many minutes does it take the first tourist to walk 1 km?

2. Solve the equation

$$\sin \sqrt{4 + 3x - x^2} + \cos \sqrt{4 + 3x - x^2} = \sqrt{2}.$$

3. Solve inequality

$$\frac{\log_2(x^2 - 3x - 4)}{\log_2(x + 17)} \leq 1.$$

4. Solve inequality

$$\sin^2 2x (\text{ctg} x - \text{tg} x) > 2 \cos 2x.$$

5. The lateral edges of the triangular paramid are mutually perpendicular. The height of the paramid is $h$. Find the radius of the sphere circumscribed about the paramid.

Option 2

1. Two diggers were tasked with digging a ditch in 3 hours and 36 minutes. However, the first one started work when the second one had already dug half of it and stopped digging. As a result, the ditch was dug in 7.5 hours. In how many hours can each digger dig a ditch?

2. Solve the equation

$$\sqrt{3 + 2 \text{tg} x - \text{tg}^2 x} = \frac{1 + 3 \text{tg} x}{2}.$$

3. Solve inequality

$$\log_{\log_2} x \left( \log_2^2 x - \frac{7}{2} \log_2 x + \frac{45}{16} \right) < 1.$$

4. Solve inequality

$$\frac{\sqrt{2}}{2} \cos x - \cos^2 x}{4 \sin^2 x - 3} < 0.$$

5. Find the volume of a regularly truncated triangular paramid if its side greater than the base is equal to $a$, the dihedral angle formed by the side face and the plane of the base is equal to $\pi/6$, and the height of the paramid is equal to $a/12$.

Option 3

1. Two dump trucks had to transfer the cargo in 3 hours 20 minutes, but the second one was late and arrived at the loading site when the first one had already transferred 2/5 of the total cargo. After that, only the second dump truck carried the remaining cargo. Transporting the entire cargo took 8 hours. In how many hours can each dump truck individually transfer the entire load?

2. Solve the equation

$$\sqrt{\cos(\cos x)} = 1 - 2 \cos(\cos x).$$

3. Solve inequality

$$\log_{\frac{1}{3}} x \left( \log_2^2 x - 19 \log_{\frac{1}{3}} x + 84 \right) < 1.$$

4. Solve inequality

$$\frac{\sqrt{3}}{2} (\cos x - 1) + \sin^2 x}{4 \sin^2 x - 3} < 0.$$

5. A ball is described near a regular triangular paramid from the side of the base $a$ and the angle of inclination of the side edge to the plane of the base $\alpha$. Find its volume.

Option 4

1. Two quantities left simultaneously towards each other from points $A$ and $B$ and met after 1.2 hours. How many hours did each of them travel the distance $AB$ if the first arrived at $B$ one hour later than the second at $A$.

2. Solve the equation

$$|\cos 2x| = \left| \sin^2 x - \frac{1}{4} \right|.$$

3. Solve inequality

$$\log_{\frac{1}{2}} \frac{x^2 - 3x + 2}{4x - 10} < 0.$$

4. Solve inequality

$$\frac{1 + \sin \frac{x}{2} - \sqrt{3} \cos \frac{x}{2}}{4 + 4 \sin x + 2 \cos x + \sin 2x} > 0.$$

5. At the base of a quadrangular paramid lies a rhombus with sides $a$ and acute angle $\alpha$. All side faces are inclined to the base plane at an angle $\beta$. Find the complete surface of the paramid.
