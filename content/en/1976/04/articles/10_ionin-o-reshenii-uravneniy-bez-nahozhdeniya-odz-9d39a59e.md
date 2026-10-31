---
id: 1976-4-ionin-o-reshenii-uravneniy-bez-nahozhdeniya-odz-9d39a59e
issue: kvant_1976_4
year: 1976
number: "4"
title: '[On solving equations without finding the ODZ]'
authors:
  - Ионин Ю. И.
rubric: raznoe
page_first: 45
page_last: 47
page_labels: 43-45
tag: I9EL
lang: en
source: kvant_digital
extraction: vision
content_sha256: f63676c9e56039accd734df0b97c2cca97493692178027d15cba99c9d266dee8
prompt_sha256: draft-1
translated_from: content/ru/1976/04/articles/10_ionin-o-reshenii-uravneniy-bez-nahozhdeniya-odz-9d39a59e.md
source_content_sha256: ff51f101df16896894c7546edbd5927e495a4cc5c8bc6e0201b4b6a364a72001
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 43⟧

4. Solve the equation
$$\frac{x^4 + 4}{x^2 - 2} - 5x = 0.$$
Sometimes even a simple geometric problem gives rise to independent research if one tries to find out the significance of a particular proposal, change the conditions of the problem and consider more general configurations. U. Alla (Võru, Estonian USSR) invites readers of the journal to conduct such research, starting with the following task.

5. The trapezoid $ABCD$ contains diagonals that intersect at the point $O$. Prove that the areas of the resulting quadrilaterals are related by the relation
$$S_{\Delta AOB} \cdot S_{\Delta COD} = S_{\Delta BOC} \cdot S_{\Delta DOA}.$$
Try to establish general relationships for various more general propositions.

6. Let the diagonals $A_1A_3$ and $A_2A_4$ of the convex quadrilateral $A_1A_2A_3A_4$ intersect at the point $O$. Let us denote the area of ​​the quadrilaterals $A_1OA_2, A_2OA_3, A_3OA_4, A_4OA_1$ by $S_1, S_2, S_3, S_4$, respectively. Is it true that $S_1S_3 = S_2S_4$?

7. Is this ratio still valid?
a) for a non-convex non-self-intersecting quadrilateral;
b) for a self-intersecting quadrilateral?

8. Generalize this relation to the case when the point $O$ is an arbitrary interior point of a convex quadrilateral.

9. Is the relation obtained in the previous problem valid if the point $O$ lies outside the convex quadrilateral?

10. Generalize this relation to the case of a convex $2n$-gon ($n \geq 2$) and an arbitrary point $O$ in its plane.

* *

Many applicants begin solving an equation or inequality by finding the range of acceptable values ​​(ADV), i.e., a set of numbers for which the simultaneous left and right sides of this equation or inequality are determined. However, it should be borne in mind that finding ODZ does not need to be done in all cases.

For example, if equivalent transformations are used in the solution process, then finding ODZ is a waste of time.

Example 3 (MINCH and GP, 1974). Solve inequality
$$\log_2 \log_3 \frac{x+2}{x-2} < \log_{1/2} \log_{1/3} \frac{x-2}{x+2}.$$ (4)

Finding the ODZ here requires solving the system of inequalities

$$\begin{cases} x \neq 2, \\ \frac{x+2}{x-2} > 0, \\ \log_3 \frac{x+2}{x-2} > 0, \\ x \neq -2, \\ \frac{x-2}{x+2} > 0, \\ \log_{1/3} \frac{x-2}{x+2} > 0, \end{cases}$$

which is quite a difficult task. Meanwhile, there is no need to find the ODZ, since from inequality (4) we can follow to equivalent inequalities:

$$\log_2 \log_3 \frac{x+2}{x-2} < -\log_2 \log_3 \frac{x+2}{x-2};$$

$$\log_2 \log_3 \frac{x+2}{x-2} < 0;$$

$$0 < \log_3 \frac{x+2}{x-2} < 1;$$

$$1 < \frac{x+2}{x-2} < 3,$$

$$1 < 1 + \frac{4}{x-2} < 3,$$

$$0 < \frac{2}{x-2} < 1,$$

$$\frac{x-2}{x+2} > 1,$$

from where we get the solution: $x > 4$.

Quite often, finding the ODZ turns out to be unnecessary when solving irrational equations. So, squaring both sides of the equation
$$\sqrt{f(x)} = g(x),$$ (5)

we arrive at the equation
$$f(x) = |g(x)|^2,$$ (6)

⟦folio 44⟧

the consequence of which is the inequality $f(x) \geq 0$. Therefore, the roots of equation (6) are always included in the ODZ of equation (5).

Example 4 (MSU, physicist, 1968). For each value of the parameter a, find all solutions to the equation

$$\sqrt{a(2^x - 2) + 1} = 1 - 2^x.$$

Finding the ODZ here would require solving the inequality with the parameter $a(2^x - 2) + 1 \geq 0$, but without this the usual ones can be done. Using $t = 2^x$, we rewrite this equation in the form

$$\sqrt{at - 2a + 1} = 1 - t.$$ (7)

After squaring both clock parts of equation (7) we get

$$at - 2a + 1 = (1 - t)^2,$$ (8)

whence $t_1 = a, t_2 = 2$. For the roots found, there is no need to check the validity of inequality $at - 2a + 1 \geq 0$ - it is a consequence of equation (8). It is only necessary to check the fulfillment of condition $1 - t \geq 0$, which ensures the equivalence of equations (7) and (8), and condition $t > 0$, which follows from equation $t = 2^x$; both of these conditions can be verified without difficulty.

Answer: for $a \leq 0$ and for $a > 1$ there are no solutions; for $0 < a \leq 1$ there is a unique solution $x = \log_2 a$.

Often, when solving equations and inequalities, the ODZ can be found “not completely”, imposing the necessary restrictions not directly on the unknown, but on some expressions from the unknown.

Example 5 (LSU, Math., 1966). Solve the equation

$$tg \frac{2\pi x}{1 + x + x^2} = \sqrt{3}.$$

An 《Exemplary》 applicant, starting with finding the ODZ, will be faced with the need to solve a set of equations

$$\frac{2\pi x}{1 + x + x^2} = \frac{\pi}{2} + k\pi$$

($k = 0, \pm 1, \pm 2, \dots$) to determine the “forbidden” values ​​of the unknown. Meanwhile, it is enough just to know what the DZ describes in terms

$$\frac{2\pi x}{1 + x + x^2} \neq \frac{\pi}{2} + k\pi$$ (9)

($k = 0, \pm 1, \pm 2, \dots$). In fact, the original equation is indivisibly related to the set of equations

$$\frac{2\pi x}{1 + x + x^2} = \frac{\pi}{3} + n\pi$$

($n = 0, \pm 1, \pm 2, \dots$), whose roots, of course, satisfy conditions (9).

Using the above examples, you can make sure that the actual calculation of the ODZ is not a mandatory element of solving equations and inequalities - also carry out the calculation of the following only when it is really necessary.

At the right

11 (MSU, VMK, 1973). Solve inequality

$$\log \frac{x^2 - 10x + 31}{30} \left(5x - \frac{11}{20}\right) \leq 0.$$ (12)

12 (MSU, Faculty of Mechanics, 1974). Solve equation $\sqrt{2\sin 2x} + 2\sin x = 0.$

13 (MSU, Faculty of Economics, 1974). Find all solutions to the equation

$$\log_{\cos 2x - \sin 2x} (1 - \cos x - \sin x) = 1.$$ (Yu. Ionin (Leningrad))

* *

An interesting proposal was expressed in a letter by P. Gorshitey (Kyiv): to publish beautiful, short and “non-standard” solutions to competitive exam problems on the pages of the magazine. In fact, often, for example, in geometric problems, applicants get to the result after checking long and cumbersome calculations. However, sometimes the solution to the same problem can be reduced to just a few lines if you find the “zest” - an agreement to apply a certain geometric theorem or make a successful additional construction.

The author of the letter gives several examples of such problems taken from the

⟦folio 45⟧

Options for entrance exams at Moscow State University. They can be solved without “geometric imagination,” although then a rather tortuous path with complex calculations leads to the goal (see B. I. Aleksadrov and M. V. Lurie, “Mathematics Manual for Those Entering Moscow State University,” Moscow State University Publishing House, 1974). We invite the reader of the magazine to try to find short geometric solutions to the following problems.

14 (MSU, physics department, 1972). In triangle ABC, angle B is equal to π/4, angle C is equal to π/3. Circles are constructed on the medians BM and CN as diameters, intersecting at points P and Q. The chord PQ intersects the midline MN at point F. Find the ratio of the length of the segment NF to the length of the segment FM.

15 (MSU, physics department, 1973). The lateral faces of the triangular paramda SABC with vertex S form equal angles with the plane of the base ABC of the paramda; SO is the height of the paramda. It is known that $\angle ASB = 7\pi/12$, $\angle BSC = \pi/2$, $\angle SCA = \pi/3$. Find the ratio of the area of ​​triangle AOB to the area of ​​triangle ABC.

16 (MSU, Faculty of Geography, 1971). In triangle ABC, on the sides AB = 3, BC = 4, AC = 5, a bissertis BD is drawn. Triangles ABD and BCD have inscribed circles that touch segment BD at points M and N, respectively. Determine the length of the segment MN.

* *

There are several more letters in the editorial mail in which the magazine's readers offer simple and ingenious solutions to specific problems.

Example 6 (MIPT, 1970). A subway passenger goes down a moving escalator in 24 seconds. If a passenger walks at the same speed, but on a stationary escalator, he can descend in 42 seconds. How many seconds does it take for him to descend while standing on the steps of a moving escalator?

If we denote the length of the escalator by l, and the speed of the escalator and passenger by v₁ and v₂, then it is not difficult to create a system of two equations with unknowns, from which the initial ratio l/v₁ is determined (see «Kvant», 1971, No. 5, pp. 46-47).

7th grade student D. Feofanov (Alma-Ata) offers an arithmetic solution to the problem. When the passenger and the escalator move simultaneously, the passenger descends 1/24 of the length of the escalator in 1 second. But in 1 second the passenger himself descends the stationary escalator to 1/42 of its length. Consequently, the jelly of the escalator travels $\frac{1}{24} - \frac{1}{42} = \frac{1}{56}$ part of the length of the escalator in 1 second, and then it sells its length in 56 seconds.

* *

The test work for television courses for university applicants included the following task (see «Kvant», 1973, No. 1, p. 55; No. 2, p. 80).

Example 7. Find sin 2α if it is known that

$$3 \mathrm{tg}^2 \alpha - 10 \mathrm{tg} \alpha + 3 = 0$$

and that uol α satisfies the inequalities

$$\frac{5}{4} \pi < \alpha < \frac{3}{2} \pi.$$

An interesting solution to this problem was sent to the editor by T. Antipova, a student at the State Technical University (Moscow). Let us rewrite the equality given in the conditions in the form

$$10 \mathrm{tg} \alpha = 3 (\mathrm{tg}^2 \alpha + 1).$$

Since $\mathrm{tg}^2 \alpha + 1 \neq 0$, we get from here that

$$\frac{2 \mathrm{tg} \alpha}{1 + \mathrm{tg}^2 \alpha} = \frac{3}{5}.$$

If we recall the expression for sine through the tangent of the given argument

$$\sin x = \frac{2 \mathrm{tg} \frac{x}{2}}{1 + \mathrm{tg}^2 \frac{x}{2}},$$

then we immediately find: sin 2α = $\frac{3}{5}$. Note that the condition 5π/4 < α < 3π/2 turns out to be unnecessary.

Review prepared by N. Rozov and V. Stepanov
