---
id: 1971-4-tonyan-vstupitelnyie-ekzamenyi-po-matematike-v-miem-17bb1a96
issue: kvant_1971_4
year: 1971
number: "4"
title: Entrance exams in mathematics at MIEM
authors:
  - Тонян В. А.
rubric: raznoe
rubric_sub: Разное
page_first: 53
page_last: 57
page_labels: 51-55
tag: 3KDA
lang: en
source: kvant_digital
extraction: vision
content_sha256: b0731d3edab0b5a15e55c9e9d5487c046b9b8e5ff685c769bd0716c76b68bb2c
prompt_sha256: draft-1
translated_from: content/ru/1971/04/articles/13_tonyan-vstupitelnyie-ekzamenyi-po-matematike-v-miem-17bb1a96.md
source_content_sha256: 86debd7d55071c740ec51dfa97c235d02e3f11e6aa2293e018afe36fc2abff9d
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 51⟧

ENTRANCE EXAMINATIONS
IN MATHEMATICS
At MIEM
V.A. TONYAN

At the Moscow Institute of Electronic Engineering, the mathematics exam places increased demands on builders. The first exam for all applicants is written mathematics.

We have already discussed in the pages of Quantum (No. 5, 1970) some issues relating to the 1969 written examination in mathematics. Here I want to talk about the 1970 exams.

Below is an analysis of one option, indicating the most typical mistakes made in the construction of the exam.

At the end there will be a task for the written examinations offered in 1970.

Option

1. Given are two triangles, each with an area of ​​50 cm². The base of the first of them is 10 cm larger than the base of the second. Within each limit, can the base of the first triangle be changed so that the difference in the heights of the triangles is at least 5/6 cm?

2. Solve the equation

$$\sqrt{\frac{x^2+66^2}{x}} - \sqrt{x \sqrt{x^2+66^2}-x^2} = 5.$$

3. Solve inequality

$$\log \frac{1}{5} \sqrt{x^3+x^2+x-14} \log \frac{1}{4} (-x^2 + 5x - 6) < 0.$$

4. Solve the equation

$$\sqrt{3+2(2\sin x-\cos 2x)} + \sqrt{3-2(2\sin x+\cos 2x)} = 2.$$

5. For example, the base of which is a rhombus with an acute angle α, a ball of radius R is inscribed. The lateral faces of the examples are inclined to the plane of the base at an angle β. Find volume examples.

Analysis of variant tasks

1. Let us denote the base of the first triangle by x, then the base of the second will be x−10, and therefore x > 10. (1)

The height of the first triangle will be $$\frac{50}{x/2} = \frac{100}{x},$$ and the second $$\frac{100}{x-10}.$$

According to the conditions of the problem, taking into account that we write $$\frac{100}{x-10} > \frac{100}{x},$$ $$\frac{100}{x-10} - \frac{100}{x} \geq \frac{5}{6},$$ and remember conditions (1), we transform it as follows:

$$x^2 - 10x - 1200 \leq 0,$$ (2)

⟦folio 52⟧

or
$(x+30)(x-40) \leq 0,$
where
$-30 \leq x \leq 40.$
If we now take into account constraint (1), we get the answer: $10 < x \leq 40.$
Some applicants who solved this problem did not think about what was indicated by the letter $x$ and gave the solution to inequality (2) as an answer.
2. Let's introduce new unknowns. Let's put
$$u = \sqrt{\frac{\sqrt{x^2+66^2}+x}{x}},$$
$$v = \sqrt{x\sqrt{x^2+66^2}-x^2}.$$
Then this equation will be rewritten in the form
$$u-v = 5.$$ (1)
Let us now note that
$$u \geq 0, \quad v \geq 0$$ (2)
And
$$uv = \sqrt{\frac{\sqrt{x^2+66^2}+x}{x}} \times \sqrt{x\sqrt{x^2+66^2}-x^2} = \sqrt{(\sqrt{x^2+66^2}+x)}\sqrt{\sqrt{x^2+66^2}-x} = \sqrt{x^2+66^2}-x^2 = 66.$$
The last equation together with (1) and (2) gives a mixed system
$$\begin{cases} uv = 66, \\ u-v = 5, \\ u \geq 0, \quad v \geq 0, \end{cases}$$
which can be rewritten as follows:
$$\begin{cases} u(-v) = -66, \\ u+(-v) = 5, \\ u \geq 0, \quad v \geq 0. \end{cases}$$
Let us recall the Vieta formulas and replace that $u$ coincides with the positive root of the equation $x^2-5x-66 = 0$. Thus,
$$u = \sqrt{\frac{\sqrt{x^2+66^2}+x}{x}} = 11,$$
where
$$\sqrt{x^2+66^2}+x = 121x,$$
and, therefore,
$$\sqrt{x^2+66^2} = 120x.$$
This shows that $x \geq 0$. Squared, we get the equation
$$x^2+66^2 = 120^2x^2,$$ (3)
where is it from:
$$x = \frac{6}{\sqrt{119}}.$$
We found this root by performing equivalent (subject to specified restrictions) transformations, and then checking is not necessary. Many applicants coped with this task, but there were also many works in which the answer contained the construction of roots, for example, the negative root of equation (3).
Let us remind you once again: if nonequivalent transformations are performed when solving an equation, then checking the roots found is an integral part of solving the problem, and without this verification the solution cannot be considered correct.
3. Valid values ​​are only those values ​​of $x$ for which $-x^2+5x-6 > 0$, that is $2 < x < 3$, then $4 < x^2 < 9$ and $8 < x^3 < 27$, so $14 < x^3+x^2+x < 39$ and $0 < x^3+x^2+x-14 < 25$. The base for the first logarithm is found
$$0 < \frac{1}{5}\sqrt{x^3+x^2+x-14} < 1.$$
Hence,
$$\log_{\frac{1}{4}}(-x^2+5x-6) > 1,$$
from where we get the answer: $2 < x < 2,5$ or $2,5 < x < 3$.
4. Let's transform the expression under the first radical:
$$3+2 \quad (2\sin x-\cos 2x) = 3+4\sin x + 4\sin^2x-2 = (2\sin x+1)^2,$$
analgoric
$$3-2 (2\sin x+\cos 2x) = (2\sin x-1)^2.$$

⟦folio 53⟧

Now this equation can be rewritten as
$$|2 \sin x+1|+|2 \sin x-1|=2.$$
It is easy to verify that the last equation is satisfied, and identically, only for $|\sin x| \leq \frac{1}{2}$, from which we find:
$$-\frac{\pi}{6} + \pi n \leq x \leq \frac{\pi}{6} + \pi n$$
$(n=0, \pm 1, \dots)$.

5. The center $O'$ of the inscribed ball (Fig. 1) is a point equidistant from all the edges of the parameters, and therefore it lies at the intersection of the bicsectorial planes of all two boundaries of the angles of the parameters. Since the diagonals of a rhombus are bicsectricals of its internal angles, then the planes passing through the height and diagonals are bicsectricals for two-angle angles at the lateral edges (check this yourself). By condition, the faces are equal to the base, and therefore the point of intersection of the diagonals of the rhombus $O'$ is the base of the height $SO$. Thus, the center of the ball $O'$ lies at the height of the parameters. The perpendicular dropped from the point $O'$ to the lateral boundary of the parameters lies in the plane passing through the height $SO$ and the height of the base $FE$ (FE passes through the point $O$), this is easily deduced from the theorem of three perpendiculars. Now from the right triangle $SOE$ ($O'O = O'O'' = R$, $\Rightarrow SEO = \alpha$) we find
$$SO = OE \mathrm{tg} \beta = R \mathrm{tg} \beta \mathrm{ctg} \frac{\beta}{2}.$$
The height parameters have been found, it remains to determine the area of ​​the base.
From the right triangle $OO'E$ ($OO' = R$, $\Rightarrow O'EO = \frac{\beta}{2}$) we find
$$OE = OO' \mathrm{ctg} \frac{\beta}{2} = R \mathrm{ctg} \frac{\beta}{2}.$$
Next we replace that
$$CD = \frac{FE}{\sin \alpha},$$
and therefore
$$S_{\text{ромба}} = \frac{FE^2}{\sin \alpha} = \frac{4OE^2}{\sin \alpha} = \frac{4R^2 \mathrm{ctg}^2 \frac{\beta}{2}}{\sin \alpha}.$$
For volume parameters we get the final answer:
$$V = \frac{4}{3} R^3 \frac{\mathrm{ctg}^3 \frac{\beta}{3} \mathrm{tg} \beta}{\sin \alpha}.$$

A little about the oral exam

Oral exams at MIEM will be based on tickets. Each ticket contains two theoretical questions, which are strictly in accordance with the Application Examination Syllabus. Each examinee takes approximately 45 minutes to prepare for the answer. After he has answered the questions on the ticket, he is offered additional questions from the theory and problem sections not included in the ticket to test his ability to apply theory to problem solving. These tasks typically do not require computation. Here are examples of such questions and tasks with some comments.

⟦folio 54⟧

1. If we add two periodic decimal fractions, will their sum again be a periodic decimal fraction?

Usually the correct answer is: “Yes, it will, since a periodic decimal fraction is a rational number, and the sum of two rational numbers is again rational.”

This is generally true; it is only necessary to stipulate that not only a periodic, but also a finite decimal fraction can be obtained, for example: 0, (3)+0, (6) = 1, since $\frac{1}{3} + \frac{2}{3} = 1$.

The next question turns out to be more difficult.

2. If the first fraction has p digits in period, and the second q digits, then what period can their sum have?

Usually, without additional help, it is difficult for an applicant to give the correct answer. Meanwhile, to the question “What is the period of the function f(x)+g(x), if the period f(x) is equal to 2π, and the period g(x) is equal to 3π?” applicants, as a rule, give the correct answer: “6π”. Meanwhile, both questions essentially relate to the same section of arithmetic: least common multiple (LCM) and greatest common divisor (GCD). The correct answer to the original question is: the period of the sum does not exceed the LCM of the numbers p and q.

We invite readers to look at several examples themselves when the period of the sum is exactly equal to the LCM and when it is less than this common multiple.

More difficult is the question of the period of the product of two periodic decimal fractions, of which the first has p digits in the period, and the second has q digits.

We will only give the answer: the period of the product does not exceed m (10^n−1), where m is the LCM of the numbers p and q, n is their GCD. Consider the example: 0, (1)×0, (1) = 0, (012345679); here p = q = 1, the period of the product is 9 digits.

3. Given: tan α = a, $\frac{3\pi}{2} < \alpha < 2\pi$.

Find sin α.

I have seen such a “solution” to this example more than once. Pshet arrive:

$$\sin^2 \alpha = \frac{1}{1 + \text{ctg}^2 \alpha},$$

where

$$\sin \alpha = -\sqrt{\frac{1}{1 + \text{ctg}^2 \alpha}}$$

$$= -\sqrt{\frac{a^2}{1 + a^2}} = -\frac{a}{\sqrt{1 + a^2}},$$

and only after the replacement that if the last equality is true, then sin α in the IV quarter has a positive sign, the applicant begins to look for an error in the solution.

4. Determine the sign of the difference

$$\left(\frac{3}{8}\right)^2 \sqrt{2} - 1.$$

This problem raises the question: what is $2^{\sqrt{3}}$? Many applicants who talk in detail about the properties of the exponential function cannot answer this question.

5. Solve equation $x^4 - 10x^2 + 169 = 0$.

Obviously let the solution be like this.

Let us denote $x^2$ by y, then we obtain the equation $y^2 - 10y + 169 = 0$, the roots of which are complex. To determine x, the examinee continues to reason, we need to extract the root of a complex number, and this action is not provided for in the school curriculum. On this basis, some applicants come to the conclusion that the entrance exams offer problems that cannot be solved by someone who knows only a school course in mathematics. Is this conclusion correct? Is it even possible to draw such a conclusion, to replace only that some problem can be solved using methods that are not studied in high school? Doesn't it indicate

⟦folio 55⟧

such a conclusion about the insignificance of its author that not every opposite statement is true?

Let us return, however, to our biquadratic equation.
$$x^4 + 2 \cdot 13 \cdot x^2 + 169 - 36x^2 = 0,$$
where
$$(x^2 + 13)^2 - 36x^2 = 0,$$
and this leads to two quadratic equations with real coefficients:
$$x^2 - 6x + 13 = 0, \quad x^2 + 6x + 13 = 0.$$

Try to prove that any biquadratic equation $x^4 + px^2 + q = 0$, where $p^2 - 4q < 0$ indicates by the above method can be reduced to two quadratic equations with real coefficients.

6. Let's draw a graph of the function $y = \arcsin(\sin x)$.

The function is defined on the interval $-\infty < x < \infty$. Due to the periodicity of the function $z = \sin x$, the function $y = \arcsin z$ is also periodic with period $2\pi$, and it is enough to study it, for example, on the segment $[-\frac{\pi}{2}, 3\pi/2]$.

On the segment $[-\pi/2, \pi/2]$ sin $y = \sin x$ and $y = x$; if $\frac{\pi}{2} \leq x \leq \frac{3\pi}{2}, -\frac{\pi}{2} \leq \pi - x \leq \frac{\pi}{2}$ and from the equality sin $(\pi - x) = \sin x$ it follows that $y = \pi - x$. The final graph is shown in figure 2.

Solve problems on your own from other options for written work for 1970.

1. From points $A$ and $B$, the distance between which is 28 km, 2 pedestrians simultaneously went towards each other. They were supposed to line up in 3.5 hours, but the second one stopped for 0.5 hours to retreat, and when they met, it turned out that the first one had covered 2 km more than the second one. Find the speed of pedestrians.

2. Solve the equation
$$\sqrt{\frac{x^2 + 28^2}{x}} - \sqrt{x \sqrt{x^2 + 28^2}} = 3.$$

3. Solve the equation
$$\sqrt{2 \text{ctg} x + \frac{1}{\sin^2 x}} + \sqrt{2 \text{ctg} x + \frac{1}{\cos^2 x}} = 2 \text{ctg} 2x.$$

4. Solve inequality
$$3 \log_5 \frac{1}{x^2} \Bigg|_{\log_5 |x + 2|} \leq 6.$$

5. The basis of the example is an equilibrium triangle, the equal sides of which have a length of $b$. The lateral boundaries of examples passing through these sides are perpendicular to the plane of the base and form an angle $\alpha$ between themselves. The angle between the triangle of the face and the plane of the base is also equal to $\alpha$. Determine the radius of the ball inscribed in this example.

Solve equations
6. $$\sqrt{x^2 + 1} + \sqrt{x^2 - 2x + 3} = 3.$$

7. 3 sin $x + 5 \cos x = \sqrt{17 + 8 \cos 2x + 15 \sin 2x}$.
