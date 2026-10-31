---
id: 1970-6-goldberg-vstupitelnyie-ekzamenyi-po-matematike-v-moskovskom-institute-stali-i-splavov-1969-goda-d344e2d2
issue: kvant_1970_6
year: 1970
number: "6"
title: Entrance exams in mathematics at the Moscow Institute of Steel and Alloys in 1969
authors:
  - Гольдберг В. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 31
page_last: 36
page_labels: 29-34
tag: 5IUN
lang: en
source: kvant_digital
extraction: vision
content_sha256: 268913f4f23a5889561571ab6096296c1faf7fdd3e2c9a3873983735ed340f42
prompt_sha256: draft-1
translated_from: content/ru/1970/06/articles/09_goldberg-vstupitelnyie-ekzamenyi-po-matematike-v-moskovskom-institute-stali-i-splavov-1969-goda-d344e2d2.md
source_content_sha256: 70114eca239335160495fdaa8d5b514c42acc28c4127eca69a15e831f862e3b0
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 29⟧

Entrance exams in mathematics at the Moscow Institute of Steel and Alloys are typical for most technical schools.

At the faculties of MCHMIS (metallurgy of ferrous metals and alloys) and MCRMIS (metallurgy of non-ferrous metals and alloys) the disciplines are written mathematics, physics and chemistry; at the faculties of Physics (physics and chemistry) and PMP (semiconductor materials and devices) - written and oral mathematics and physics. The competition for all faculties is held separately.

Note that about 19% (179 people) of the new student body was recruited in industrial centers: Bekabad, Volgograd, Zaporozhye, Norilsk, Orsk, Cherepovets.

The content of the tickets for written and oral examinations strictly corresponded to the mathematics program for applicants to universities.

Let's look at one of the options offered at the faculties of MCHMIS and MCRMIS.

Option 1.

1. Solve the equation
$$\sec^2 \frac{x}{2} + \cos^2 \frac{x}{2} = 16 \text{ ctg } x.$$

2. Solve inequality
$$\frac{3x^2 - 2x - 1}{\lg(x - 1)} < 0.$$

3. Simplify
$$\left[ 4(a + 1) + \left( \frac{\sqrt{ab^2} + \sqrt{a}}{\sqrt{3}a + \sqrt{3}b} + \frac{\sqrt{6}a}{3} \right)^3 \right]^{1/2}$$

4. Let $E$ be the midpoint of side $AB$ of the trapezoid $ABCD$ ($BC \parallel AD$). Prove that the area of ​​the triangle $ECD$ is equal to half of the trapezoid $ABCD$.

5. A cube with edge $a$ is inscribed in a regular quadrangular paramid such that four of its vertices are on the side edges, and four other vertices are on the base of the paramid. The lateral faces of the paramid are inclined to the plane of the base at an angle $\alpha$. Determine the volume of the paramid.

Solution

1. Let us define the ODZ equation:
$$x \neq \pi l \quad (l = 0, \pm 1, \dots).$$

Let's start solving the equation. We have
$$\frac{1}{\cos^2 \frac{x}{2}} + \frac{1}{\sin^2 \frac{x}{2}} = 16 \frac{\cos x}{\sin x},$$
where
$$\frac{1}{\cos^2 \frac{x}{2}} \sin^2 \frac{x}{2} = 16 \frac{\cos x}{\sin x}$$
or
$$\frac{4}{\sin^2 x} = 16 \frac{\cos x}{\sin x}.$$

Since $\sin x \neq 0$, we get
$$4 \sin x \cos x = 1$$
or
$$\sin 2x = \frac{1}{2},$$
where
$$2x = (-1)^n \frac{\pi}{6} + \pi n,$$

⟦folio 30⟧

or

$$x = (-1)^n \frac{\pi}{12} + \frac{\pi n}{2}$$
$$(n = 0, \pm 1, \dots).$$

The resulting solutions are included in the ODZ equations.

Answer: $x = (-1)^n \frac{\pi}{12} + \frac{\pi n}{2}$
$$(n = 0, \pm 1, \dots).$$

2. To solve the inequality
$$\frac{3x^2 - 2x - 1}{\lg(x - 1)} < 0$$

Note that a fraction will be negative if its numerator and denominator have different signs. Thus, this inequality is equivalent to two systems of inequalities:

$$\begin{cases} 3x^2 - 2x - 1 > 0, \\ \lg(x - 1) < 0 \end{cases}$$

or
$$\begin{cases} 3x^2 - 2x - 1 < 0, \\ \lg(x - 1) > 0. \end{cases}$$

Solving these systems, we find the corresponding

$$\begin{cases} x < -\frac{1}{3}, x > 1, \\ 0 < x - 1 < 1, \\ x - 1 > 1, \end{cases}$$

that is
$$\begin{cases} x < -\frac{1}{3}, x > 1, \\ 1 < x < 2, \\ x > 2. \end{cases}$$

The second system has no solution, and the solution to the first is the inverval $1 < x < 2$.

Answer: $1 < x < 2$.

3. First of all, we find the valid values ​​$a$ and $b$:
$$a \geq 0, b \geq 0, a \neq -b.$$

We note further that
$$\sqrt[6]{ab^2} + \sqrt{a} = \sqrt[6]{a} \left( \sqrt[3]{a} + \sqrt[3]{b} \right).$$

Considering that $a + b \neq 0$, and reducing the fraction by $\sqrt[3]{a} + \sqrt[3]{b}$, we get

$$\left[ 4(a + 1) + \left( \frac{\sqrt[6]{ab^2} + \sqrt{a}}{\sqrt[3]{a} + \sqrt[3]{b}} + \sqrt[6]{a} \right)^3 \right]^{1/2} =$$
$$= \left[ 4(a + 1) + \left( 2\sqrt[6]{a} \right)^3 \right]^{1/2} =$$
$$= 2\left[ \left( \sqrt{a} + 1 \right)^2 \right]^{1/2} = 2\left( \sqrt{a} + 1 \right).$$

4. Given (Fig. 1): $ABCD$ - trapezoid, $AE = EB$.

Prove:
$$S_{ECD} = \frac{1}{2} S_{ABCD}.$$

Proof. Let's draw the middle line $EF$ of the trapezoid.

Then $S_{ABCD} = EF \cdot H$, where $H$ is the height of the trapezoid. On the other side,

$$S_{ECD} = S_{ECF} + S_{EFD} = \frac{1}{2} EF \cdot \frac{H}{2} +$$
$$+ \frac{1}{2} EF \cdot \frac{H}{2} = \frac{1}{2} EF \cdot H.$$

⟦folio 31⟧

---
running_head:
folio:
---

Fig. 3.

Therefore
$$S_{ECD} = \frac{1}{2} S_{ABCD}.$$

5. First of all, note that the vertices of the lower base of the cube lie on the diagonals of the base of the paramid (projection of the side edges) and that $\angle ETO = \alpha$ (Fig. 2).

Let us denote the side of the base of the paramid by $x$. From $\triangle EOT$ there is $EO$ paramid:

$$EO = OT \cdot tg\alpha = \frac{x}{2} tg\alpha.$$ Next, from the similarity of triangles $EO_1K_1$ and $EOC$ we have $EO_1:EO = O_1K_1:OC$ or

$$\frac{x}{2} tg\alpha - a}{\frac{x}{2} tg\alpha} = \frac{a \sqrt{2}}{2},$$

where

$$x = \frac{2a(1 + tg\alpha)}{tg\alpha}.$$

The volume of paramid $EABCD$ is equal to

$$V = \frac{1}{3} x^2 \frac{x}{2} tg\alpha = \frac{1}{6} x^3 tg\alpha =$$

$$= \frac{4}{3} a^3 \frac{(1 + tg\alpha)^3}{tg^2\alpha} =$$

$$= \frac{8 \sqrt{2} a^3 \cos^3(\alpha - \frac{\pi}{4})}{3 \sin^2\alpha \cos\alpha} =$$

$$= \frac{16 \sqrt{2} a^3 \cos^3(\alpha - \frac{\pi}{4})}{3 \sin 2\alpha \sin\alpha}.$$

Answer:

$$V = \frac{16 \sqrt{2} a^3 \cos^3(\alpha - \frac{\pi}{4})}{3 \sin 2\alpha \sin\alpha}.$$

Let us now examine one of the options offered in the written exam at the faculties of PH and PMP.

Option 2

1. A quadrangular paramid is inscribed in a ball of radius $R$, the lateral edges of which are inclined to the plane of the base at an angle $\alpha$. Determine the volume of the paramid if at its base lies a rectangle with an angle $\beta$ between the diagonals.

2. Solve the equation

$$\sqrt{2} \sin 10x + \sin 2x = \cos 2x.$$

3. Solve inequality

$$\log_{3x+4} x^2 < 1.$$

4. Simplify an expression

$$(a + x^{1/2})^{-1/2} + (a - x^{1/2})^{-1/2},$$

where $x = 4(a-1)$, and $1 < a < 2$.

Solution

1. The plane of the base of the paramid intersects the ball in a circle (Fig. 3) circumscribed near the base $ABCD$. The height of the paramid will pass through the center $O$ of the ball and through the center $O_1$ of this circle, since all the edges are inclined to the base at equal angles. A plane passing through the diagonal of the base $AC$ and the vertex $E$ will intersect the ball along a great circle circumscribed about the diagonal section of the paramid $AEC$. From $\triangle AEC$, where $\angle AEC =$

⟦folio 32⟧

= 180° - 2α, by the theorem of sines, finding that
AC = 2R sin (180° - 2α) = 2R sin 2α. Because
AO₁ = $\frac{1}{2}$ AC = R sin 2α.

From △ AEO₁ we determine the straightness height:
EO₁ = H = AO₁ · tg α = R sin 2α · tg α.

The area of ​​the base of the straight line is equal to
S_{ABCD} = 2 (S_{AO₁B} + S_{BO₁C}) =
= 2 [$\frac{1}{2}$ AO₁² sin β +
+ $\frac{1}{2}$ AO₁² sin (180° - β)] =
= 2R² sin² 2α sin β.

The volume of straight line V will be equal to
V = $\frac{1}{3}$ 2R² sin² 2α sin β · R sin 2α · tg α =
= $\frac{2}{3}$ R³ sin³ 2α tg α sin β.

Answer:
V = $\frac{2}{3}$ R³ sin³ 2α tg α sin β.

2. Noticing that
cos 2x - sin 2x =
= sin ($\frac{\pi}{2}$ - 2x) - sin 2x =
= $\sqrt{2}$ sin ($\frac{\pi}{4}$ - 2x),

we rewrite the equation in the form
$\sqrt{2} \sin 10x = \sqrt{2} \sin (\frac{\pi}{4} - 2x)$

or
sin 10x + sin (2x - $\frac{\pi}{4}$) = 0,

where
sin (6x - $\frac{\pi}{8}$) cos (4x + $\frac{\pi}{8}$) = 0.

Equating each of the components to zero, we get
x₁ = $\frac{\pi}{48}$ (8n + 1) (n = 0, ±1, ...),
x₂ = $\frac{\pi}{32}$ (8k + 1) (k = 0, ±1, ...).

3. Let's consider two cases: 3x + 4 > 1 and 0 < 3x + 4 < 1.

In the first case we get
$$\begin{cases} 3x + 4 > 1, \\ x^2 < 3x + 4, \\ x^2 > 0 \end{cases}$$ or $$\begin{cases} x > -1, \\ -1 < x < 4, \\ x \neq 0, \end{cases}$$

where is the location from?
-1 < x < 0, 0 < x < 4.

In the second case we have
$$\begin{cases} 0 < 3x + 4 < 1, \\ x^2 > 3x + 4, \\ x^2 > 0 \end{cases}$$

or
$$\begin{cases} -\frac{4}{3} < x < -1, \\ x < -1, x > 4, \\ x \neq 0, \end{cases}$$

where do we get it from?
- $\frac{4}{3} < x < -1$.

Answer:
- $\frac{4}{3} < x < -1$;
- -1 < x < 0; 0 < x < 4.

When solving this problem, the conditions x ≠ 0 were not taken into account, and therefore, together with the last two integrals, we obtained -1 < x < 4.

4. We have
$$(a + x^{1/2})^{-1/2} = \frac{1}{\sqrt{a + \sqrt{x}}} =$$
$$= \frac{1}{\sqrt{a + 2\sqrt{a - 1}}} =$$
$$= \frac{1}{\sqrt{(a - 1) + 2\sqrt{a - 1} + 1}} =$$
$$(a - x^{1/2})^{-1/2} = \frac{1}{\sqrt{a - \sqrt{x}}} =$$
$$= \frac{1}{\sqrt{a - 2\sqrt{a - 1}}} =$$
$$= \frac{1}{\sqrt{(a - 1) + 2\sqrt{a - 1} + 1}} =$$
$$= \frac{1}{\sqrt{(a - 1) - 1} + 1} =$$

⟦folio 33⟧

$$\frac{1}{\sqrt{a-1}-1} = \frac{1}{1-\sqrt{a-1}},$$

since $1 < a < 2$, i.e. $\sqrt{a-1} < 1$.

Finally we get

$$\left(a + x^{1/2}\right)^{-1/2} + \left(a - x^{1/2}\right)^{-1/2} = \frac{1}{1+\sqrt{a-1}} + \frac{1}{1-\sqrt{a-1}} = \frac{2}{2-a}.$$

When solving this problem, they forgot a lot about the condition $1 < a < 2$ and therefore made mistakes when extracting the root.

Written exams showed the following highest places among those who built:

1) Many mistakes are still made when simplifying algebraic expressions: applicants have poor knowledge of degrees and make mistakes where they need to use a certain argument root (see problem 4 from option 2 discussed above).

2) Many applicants do not have fluency in trionometric formulas, as a result of which errors arose when solving a trionometric problem, or they chose far from the shortest path to solve such a problem.

3) When solving inequalities, mistakes were made due to the insignificance of both the properties of inequalities and the properties of functions. Very often, for example, applicants did not take into account the VA of the functions included in the inequality (see task 2 from option 1, task 3 from option 2).

4) When solving stereometric problems, the stumbling block was often the lack of meaning of the basic concepts of stereometrics. For example, people often incorrectly found the linear angle of the arc angle between adjacent lateral edges parameters. Many people mistakenly believed that the linear angle in this case would be the angle at the vertex of the underlying polygon parameters.

Now try to solve some problems from other entrance exam options yourself.

Problems proposed at the faculties of MCHMIS and MCRMIS.

1. Convert to work

$$\sin 5\alpha \cdot \sin 4\alpha + \sin 4\alpha \cdot \sin 3\alpha - \sin 2\alpha \cdot \sin \alpha.$$

2. Find $tg \frac{\alpha}{2}$ if $\sin \alpha + \cos \alpha = 1,4$; $0 < \alpha < 45^\circ$.

3. Prove the same gesture

$$\frac{1}{1 + tg \alpha tg 2\alpha} = \sin \left(\frac{\pi}{2} + 2\alpha\right).$$

4. Compute $18 \sin \frac{3}{2} x \sin \frac{x}{2}$ if $\cos x = \frac{2}{3}$.

5. Prove equality

$$\cos 10^\circ \sin 20^\circ - 2 \sin 70^\circ = 1.$$

6. Solve inequality

$$3^{x+1} + 18 \cdot 3^{-x} < 29.$$

7. Solve the equation

$$\log_2 \left(4^{x-2} + 1\right) - x + 4 = \log_2 17.$$

8. Solve inequality

$$\log_3 \frac{5x-3}{2-x} > 0.$$

9. Solve inequality

$$\log_x \frac{15}{1-2x} < -2.$$

10. Solve system of equations

$$\begin{cases} \frac{x}{2} + \frac{3}{y} = 7,5, \\ \frac{7}{x} + \frac{y}{6} = 1,5. \end{cases}$$

11. Solve system of equations

$$\begin{cases} \sqrt[3]{\frac{x}{y}} + \sqrt[3]{\frac{y}{x}} = 2,5, \\ x + y = 9. \end{cases}$$

12. Solve system of equations

$$\begin{cases} 2 \log_a x + \log_a y = 3, \\ \log_b x - \log_b y = 1. \end{cases}$$

13. Find all real values ​​of $a$ for which the system of equation

$$\begin{cases} x^2 - y^2 = 1, \\ y = ax \end{cases}$$

has valid solutions.

14. Find all values ​​of $a$ for which trilen

$$(a^2 - 1)x^2 + 2(a - 1)x + 2$$

will be positive for all real values ​​of $x$.

⟦folio 34⟧

15. Find for what values ​​of $a$ the solution of the system
$$\begin{cases} x + y = 3, \\ ax + 4y = 6 \end{cases}$$
satisfies the inequalities $x > 1, y > 0$.

16. For what values ​​of $a$ do equations $3x^2 - x - a = 0$ and $4x^2 + 8x + a = 0$ both have real roots?

17. In what interval should the number $m$ change so that the roots of the equation $x^2 - 2mx + m^2 - 1 = 0$ are between -2 and 4?

18. Prove that if the median and altitude drawn from one vertex of a triangle divide the angle into three equal parts, then the triangle is rectangular.

19. Prove that in a regular pentagon one of the segments of intersecting diagonals is equal to the side of the pentagon.

20. Triangle $ABC$ rotates around bisector $AD$. Prove that the areas of the surfaces described by the sides $AB$ and $AC$ are related as volumes obtained by rotating the parts $ABD$ and $ACD$.

21. Prove that if a ball can be inscribed in a truncated cone, then the volume of the cone is equal to the product of its total surface and $1/6$ height.

22. Prove that the volume of a cone is equal to the product of its total surface and $1/3$ the radius of the inscribed ball.

Problems proposed at the faculties of PH and PMP.

23. A rectangular parallelepiped is inscribed in a cylinder, one of the sides of its base is equal to $b$. The diagonal of the parallelepiped forms an angle $\alpha$ with the plane of the base, and an angle $\beta$ with the side face passing through this side of the base. Determine the lateral surface of the cylinder.

24. Determine the volume of a regular quadrangular paramid whose lateral edge is equal to $l$, and the angle between adjacent lateral faces is equal to $\beta$.

25. Calculate without using a table
$$\text{tg} 9^\circ - \text{tg} 27^\circ - \text{tg} 63^\circ + \text{tg} 81^\circ.$$

26. Solve the equation
$$\sec^2 x = \frac{2 - \cos x - \sin x}{1 - \sin x}.$$

27. Solve inequality
$$x^2 + \frac{5}{2} x - \frac{3}{2} < 1.$$

28. Solve inequality
$$\frac{|x - 2| - |x + 2|}{x - 1} < 0.$$

29. Solve inequality
$$\left(\frac{1}{2}\right)^{\log_3 \log_2 \left(x^2 - \frac{4}{5}\right)} < 1.$$

30. Solve inequality
$$\lg \left| \frac{3x - 1}{2x + 1} \right| < 0.$$

31. Solve inequality
$$\log_2 x 2 \log_2 x 2 \log_2 (4x) > 1.$$

32. Prove that for $n^2 < a < 2n^2(n > 0)$
$$\left(\sqrt{a + 2n \sqrt{a - n^2}} + \sqrt{a - 2n \sqrt{a - n^2}}\right):$$
$$\left(\frac{1}{\sqrt{a} + \sqrt{a + 1}} + \frac{1}{\sqrt{a + 1} + \sqrt{a + 2}} + \dots + \frac{1}{\sqrt{a + n - 1} + \sqrt{a + n}}\right) = 10^{\lg 2} + \lg \left(\sqrt{a} + \sqrt{a + n}\right).$$

33. Solve the equation
$$\sqrt{a^2 + bx} + \sqrt{a^2 - bx} = \sqrt{2abx}$$
at $a > 0, b > 0$.

34. Simplifying, solve the equation
$$\frac{\left(\sqrt{x - 1} + \sqrt{x + 1} + 2\right)(2x - \sqrt{x^2 - 1})}{(x + 1)^{3/2} + (x - 1)(x - 1)^{1/2}} = \sqrt{x^2 - 1} \left(\frac{\log_a x}{\log_ab x} - \log_a b\right).$$

35. Solve system of equations
$$\begin{cases} 3 |x| - 5y = 3, \\ 2x + |y| = 11. \end{cases}$$

36. Prove that
$$\left[ \frac{1}{2^{1/4} + 2^{1/8} + 1} + \frac{1}{2^{1/4} - 2^{1/8} + 1} - 2 \cdot \frac{2^{1/4} - 1}{2^{1/2} + 2^{1/4} + 1} \right] \cdot \frac{2^{1/2} + 2^{1/4} + 1}{2} = 1 + \lg 4 + \sqrt{4 \lg^2 2 + \lg 5 - \lg 8}.$$

37. For what values ​​of the parameter $t$ the equation
$$1 + \sqrt{x + 2 \lg t} = \sqrt{x - 1}$$
has valid solutions?

V. V. Galdbere
