---
id: 1980-5-rozov-chitateli-sovetuyut-24fa04f2
issue: kvant_1980_5
year: 1980
number: "5"
title: Readers advise
authors:
  - Розов Н. Х.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 52
page_labels: 46-50
tag: S85W
lang: en
source: kvant_digital
extraction: vision
content_sha256: 14e6422a21ca46f1f8e6c3033d3f0446fb4987fdf2fb326fb0e9e1c72db73748
prompt_sha256: draft-1
translated_from: content/ru/1980/05/articles/17_rozov-chitateli-sovetuyut-24fa04f2.md
source_content_sha256: aa39e6b6acb3461b40cb356c78104687f6cea9fa801b0ea339168c1448bff7de
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

Entrance workshop

N. Rozov

Reader advise

Letters and notes posted in «Kvant» to students, teachers, and mathematics enthusiasts often touch upon issues related to the subject of the “Application Workshop.” The reader of the magazine makes comments of a theoretical nature, reports techniques for solving certain types of problems, gives methodological advice, and offers independently invented exercises. The messages and tasks contained in these letters and notes are not always new and original, but some of them, in our opinion, are useful to refer to when preparing for university entrance exams. Therefore, the editors decided to prepare another selection of materials, compiled according to ideas for suggestions from readers «Kvant», with the necessary additional comments.

In the variants of entrance exams in mathematics, control systems are often encountered. Applicants, as a rule, are good with the basic methods of solving systems - the method of substitution and the method of elimination. Journal reader P. Chebotarev (Moscow) draws attention to an interesting message that allows solving some control systems. However, before we talk about this, let's talk a little about complex functions of a special kind.

Let the function $f$ be given, and for simplicity we will assume that $D(f) = R$. Based on this function, you can form a new function

$$F(x) = f(f(x));$$

It is, very much so, also defined on the entire number line. Function $F$ is usually called *iteration*) function $f$. From figure 1 it is easy to understand how the graph of the function $f$ can be used to find the iteration value $f(f(x_*))$ for a specific value $x_*$ of the argument.

Consider the equation

$$f(f(x)) = x. \tag{1}$$

First of all, note that if $x_0$ is the root of the equation

$$f(x) = x, \tag{2}$$

then $x_0$ is the root of equation (1). But equation (1) can, of course, have other roots that are not roots of equation (2) (try to discern this fact from figure 1).

Since equation (2) is equation (1), it is useful to indicate situations in which these equations are equivalent. Let us prove, for example, the following proposition: if the function $f$ satisfies the conditions

$$\begin{cases} f(x) \geq x, \text{ при всех } x < a, \\ f(a) = a, \\ a \leq f(x) \leq x, \text{ при всех } x > a, \end{cases}$$

then equations (1) and (2) are equivalent (give a geometric interpretation of this theorem).

It was already noted above that the roots of equation (2) always serve as the roots of equation (1); Let us establish the validity of the converse statement. Let $x_0$ be the root of equation (1):

$$f(f(x_0)) = x_0; \tag{4}$$

*) In general, iteration (from the Latin iteratio - repetition) in mathematics is the result of repeated application of each operation.

⟦folio 47⟧

Let's consider each of the possible cases $x_0 > a$, $x_0 < a$, $x_0 = a$ separately.

If $x_0 > a$, then (see (3))
$$a \leq f(x_0) \leq x_0.$$ (5)

From properties (3) of the function $f$ it follows that the inequalities $a \leq f(z) \leq z$ hold for any $z \geq a$. Therefore, choosing $z = f(x_0)$, taking into account (5), we have
$$a \leq f(f(x_0)) \leq f(x_0).$$ (6)

From the correspondence (6) and (5) it is clear that
$$f(f(x_0)) \leq f(x_0) \leq x_0.$$
Comparing this integer inequality with equality (4), we conclude that $f(x_0) = x_0$, that is, $x_0$, is the root of equation (2).

Let us further assume that $x_0 < a$.
In this case, the inequality $f(x_0) \geq a$ is impossible: if it took place, then correspondence (6) would be satisfied, which, taking into account the inequality $x_0 < a$, would lead to a contradiction with equality (4). Thus, if $x_0 < a$ then $f(x_0) < a$. From properties (3) of the function $f$ it follows that the inequality $f(z) \geq z$ holds for any $z < a$. Therefore, choosing first $z = x_0$ and then $z = f(x_0)$, we have
$$x_0 \leq f(x_0) \leq f(f(x_0)).$$
Using equality (4), we again conclude that $f(x_0) = x_0$.

Listen $x_0 = a$ very iden. Consequently, under conditions (3), any root of equation (1) is a root of equation (2).

In conclusion, we note that from a given function $f$ one can obviously also determine the function
$$f(f(f(x))), f(f(f(f(x))))), \dots$$
The following proposition is true (prove it yourself): if the function $f$ satisfies conditions (3), then each of the equations $f(f(f(x))) = x, f(f(f(f(x)))) = x, \dots$
is equivalent to equation (2).

Now let's see how the formulated proposals can be used to solve systems in which all equations are identical up to the designation of variables and each equation includes only two variables.

Example 1 (MSU, Mechanics and Mathematics, 1977). Find all solutions to a system of equations
$$\begin{cases} y^3 - 6x^2 + 12x - 8 = 0, \\ z^3 - 6y^2 + 12y - 8 = 0, \\ x^3 - 6z^2 + 12z - 8 = 0. \end{cases}$$

let's isolate the function
$$f(x) = \sqrt[3]{6x^2 - 12x + 8}, x \in \mathbb{R};$$ (7)

then this system can be rewritten in the form
$$y = f(x), z = f(y), x = f(z).$$ (8)

Using the substitution method, we get from here
$$f(f(f(x))) = x.$$ (9)

First of all, consider the equation $f(x) = x$, or
$$x^3 - 6x^2 + 12x - 8 = 0.$$
It has a single root $x = 2$ (group the first left-hand side with the last and the second with the third), which is also the root of equation (9). From expression (7) for the function $f$ and equation (8) we obtain the solution to the original system:
(2; 2; 2).

Let us check that function (7) satisfies conditions (3) for $a = 2$, and therefore equation (9) has no roots other than $x = 2$. Inequality $f(x) \geq x$, which in this case is reduced to the form
$$(x - 2)^3 \leq 0$$
(carry out the necessary transformations), indeed holds for $x < 2$, and $f(2) = 2$. Further, that $f(x) \leq x$ for all $x > 2$. Finally, the inequality $f(x) \geq 2$ can easily be rewritten in the form
$$6x^2 - 8x \geq 0,$$
from which it is clear that it is valid for $x > 2$.

Consequently, the original system has a unique solution (2; 2; 2).

Exercises
1. Find integration $f(f(x))$ if:
a) $f(x) = \sin x$;
b) $f(x) = \sqrt{1+x^2}$;
c) $f(x) = -x^2 + 1$.

⟦folio 48⟧

2. Define the function $f(f(x))$ if $f(x) = -x + 3$.

3. Solve equations $f(x) = x$ and $f(f(x)) = x$ if:
   a) $f(x) = -x^2 + 1$;
   b) $f(x) = -x + 3$.
   c) $f(x) \leqslant x$ for all $x \in \mathbb{R}$
   or if $f(x) \geqslant x$ for all $x \in \mathbb{R}$
   then the equation $f(f(x)) = x$ has a single root $x = a$.
   Solve the systems of equations:

6. $\begin{cases} x - 5y = 2y^2 + 2, \\ y - 5z = 2z^2 + 2, \\ z - 5x = 2x^2 + 2. \end{cases}$

7. $\begin{cases} x = \frac{2y^2}{1 + y^2}, \\ y = \frac{2z^2}{1 + z^2}, \\ z = \frac{2x^2}{1 + x^2}. \end{cases}$

8. (MSU, mechanism, 1977).

9. For some value of $a$, can the graphs of functions $y = a^x$ and $y = \log_a x$ touch each other?

Let us explain that two curves touch each other if they have a common tangent at some common point.

Our reader A. Kornilov (Rostov-on-Don) sent a very important letter to the editor. He points out that in the article by Y. Sukonnik and P. Gorshtein “Geometric solutions of geometric problems” («Kvant», 1979, No. 9, p. 38), a server error was made when solving problem 1.

Let us remind you what task we are talking about.

Example 2. A circle is circumscribed around triangle AMB, the center of which is distant from side AM at a distance of 10. The extension of side AM beyond vertex M intersects at point C with the tangent to this circle drawn through vertex B. Find the area of ​​triangle BMC if it is known that

$$|BC| = 29, \quad \hat{ACB} = \arctg \frac{20}{21}.$$

The condition of almost any geometric problem does not provide a definition, an exhaustive description of what kind of configuration (figure) is meant: only some of its properties, characteristics or parameters are fixed, and the rest are not detailed in the conditions. If the conditions of the problem refer to the “triangle AMB”, then from a logical point of view this triangle can be, for example, acute, rectangular, or obtuse. In most cases, to solve a problem, it is not necessary to know those properties of the configuration that are not specified in the conditions, and the answer, naturally, does not depend on them.

However, in a number of more serious problems, it is necessary to begin solutions by clarifying or clarifying individual properties of the configuration, which are not explicitly specified in the conditions, but are derived from them by reasoning. Let's say, to solve the problem, you first need to establish that the triangle AMB in question cannot actually be missing. In such problems, it is especially important not to lose sight of any logical possibility and for each of them to find out whether the corresponding configuration is compatible with the data of the problem conditions.

Everything that has been said relates to the task discussed above - to solve it, first of all, it is necessary to extract additional information about the figure from the condition and clarify its appearance. In the mentioned system, solving this problem essentially begins with proving that the triangle AMB is not missing (although this is not directly stated there).

⟦folio 49⟧

But). If angle AMB is a right angle, then the answer is:

$$S_{BMC} = 210.$$

However, this far from exhausts all the logical possibilities of the types of angles of the triangle AMB (or, what is the same, all possible locations of the center of the circumscribed circle), and the reasoning carried out in the article is essentially based on a drawing relative only to the acute triangle AMB. True, case

angle MAB is straight,
angle MAB is obtuse,
angle ABM - straight,
angle AMB - obtuse

according to various principles incompatible with the given conditions of the problem (give the necessary notation). The last possibility remains: angle ABM is obtuse (Fig. 2).

Let us drop the perpendicular $BM_1$ from point B to side AM and continue it until it intersects the circle at point $M_2$, and project the center of the circle O onto the chords AM and $BM_2$. Then, how easy it is to check,

$$|BM_1| = |BC| \sin \widehat{ACB} = 20 = 2|OK|,$$
$$|BM_2| = 2(|BM_1| + |M_1L|) = 3|BM_1|;$$

the last correspondence, unlike the case of the acute triangle AMB, does not contradict the conditions of the problem. If we now consider the triangles $BM_1C$, $BOL$, $OKM$ sequentially and notice that $\widehat{OBL} = \widehat{ACB}$, we get to the answer (make sure of this):

$$S_{BMC} = \frac{1}{7}(3470 - 600\sqrt{22}).$$

In geometry it is usually customary to formulate a problem in such a way that the answer

turned out to be the same for any configuration within the limits of the production that admits the conditions. From this point of view, the above formulation of the problem is a failure: depending on whether triangle AMB is straight or obtuse, different answers (10) or (11) are obtained. In order to avoid such ambiguity, the conditions of the problem should start like this:

“Near the non-obtuse triangle AMB...”, then the problem has a unique answer (10). However, the authors of the above article, due to an oversight, omitted the words “non-obtuse” in the text of the problem statement.

Many readers send in their letters various algebraic equations of degree higher than the second, to solve which you need to “see” even the factorization of the polynomial, sometimes quite tricky. Here are two such equations proposed by 8th grade student Aleksandr Matveev (Riga):

Solve the equations:

10. $x^3 + x^2 - 5x - 6 = 0.$
11. $x^4 - 10x^3 + 24x^2 - 6x - 9 = 0.$

Schoolchildren are well aware that to solve the problem of extrema there is a universal method involving the use of derivatives. However, this does not mean that in any task this method is the easiest and fastest to achieve the goal. Sometimes it is better not to rush to differentiate, but to try to find out whether it is possible to take advantage of some features of the specific problem under consideration.

This is precisely what the reader of “Kvaent” reminds us of in his letter to S. Berkolaiko (village of Kotovo, Belgorod region). Example 3. Find the area of ​​the lateral surface of a rectangular parallelenide $ABCDA_1B_1C_1D_1$, which has the most general, if it is known that

$$|AC| = 2\sqrt{2}, \quad |AA_1| = 1.$$

⟦folio 50⟧

Since the height of the paralleleped is given, the largest parallelepid will have the base plane $ABCD$. If we denote by $x$ the length of one side of the rectangle $ABCD$, then $\sqrt{8-x^2}$ is the length of its other side. Thus, the question of when the base has the flattest area, indicating the absence of the flattest value of the function

$$S(x) = x\sqrt{8-x^2}.$$

The standard method for solving such a problem by examining an arbitrary $S'(x)$ requires some transformations and calculations.

This can be avoided if we approach the problem of finding a rectangle with the flattest area with a given diagonal length in a slightly less formulaic way. Let us choose the angle $\alpha$ between the diagonals of the rectangle $ABCD$ as the variable value. then the expression for its area is obtained (check!)

$$S(\alpha) = 4\sin \alpha,$$

from which it is immediately clear, without any differentiation, that the square has the flattest area on the side of length 2. Consequently, the area of ​​the lateral surface of the paralleleped is equal to 8.

* *

The concept of the limit of a sequence is one of the most important in the school mathematics course and at the same time one of the most difficult for students. Typically, schoolchildren know what a limit of a sequence is (that is, they can recite the definition from memory), but not everyone understands this definition deeply enough (that is, they can work with it freely). V. Lebedenko (Dubna, Moscow region) sent to the editor a problem (albeit a fairly well-known one), the solution of which requires an understanding of the definition of the limit of a sequence.

12. Is there a limit to consistency

$$x_n = \sin n?$$

Mastery of various transformation techniques is of more importance in mathematics - no less than the meaning of various theorems or the ability to carry out logical reasoning. However, one of these techniques is to add and subtract some removed selected expression. This is what is often done, for example, when factoring polynomials.

9th grade student Avaz Naziev (Minjevan village, Zangelan district, Azerbaijan USSR) gives the following example:

Example 4. Prove that if the function $f(x)$ is arbitrary at $x = a$, then

$$\lim_{x \to a} \frac{xf(a) - af(x)}{x - a} = f(a) - af'(a).$$

Before the algebraic transformations of the given expression are calculated (assuming $x \neq a$):

$$\frac{xf(a) - af(x)}{x - a} = \frac{xf(a) - af(x)}{x - a} - \frac{af(x) - af(a)}{x - a} = f(a) - a \frac{f(x) - f(a)}{x - a}.$$

From here it is already clear that the real limit indicated in (12) exists if $f'(a)$ exists and equality (12) is true.

* *

We offer readers of the magazine an independent solution to two more problems. The first of them was sent to us by 10th grade student Aladdin Eyvazov (village of Ashurlu, Masalli district of the AzSSR), the second by 10th grade student Andrey Kazarinov (Tolyatti).

13. Solve the equation

$$3^{\log_2 x} + x^{\log_3 x} = 162.$$

14. Three circles are located in the same plane so that each of them passes through the centers of the other two. Find the area of ​​the figure that is the union of all three circles, if it is known that the area of ​​intersection of all three circles is $S$.
