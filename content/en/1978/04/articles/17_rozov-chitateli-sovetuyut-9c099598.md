---
id: 1978-4-rozov-chitateli-sovetuyut-9c099598
issue: kvant_1978_4
year: 1978
number: "4"
title: Readers advise
authors:
  - Розов Н. Х.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 50
page_last: 54
page_labels: 48-52
tag: STA6
lang: en
source: kvant_digital
extraction: vision
content_sha256: fd56937bebc200e5b313b535a7c0435e6dc88071dd7b1a09d5be9abb628f1dbb
prompt_sha256: draft-1
translated_from: content/ru/1978/04/articles/17_rozov-chitateli-sovetuyut-9c099598.md
source_content_sha256: 678d4548dc53cce004d7ba8ab3127ea3f784d7f925f2313f43b37b8b6df4dbd0
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

Reader advise

The editorial office «Kvant» constantly receives letters from schoolchildren, teachers, and simply mathematics lovers regarding the topic of the “Applicant's Practicum” section.
Many of them touch on partial issues, and the editors respond to such letters personally by the author. But in a number of letters various theoretical issues of the school course are discussed, methods for solving certain types of problems are proposed, useful methodological comments and interesting problems are reported.
In our opinion, it is useful to introduce the reader «Kvant» to the contents of such letters.
Not considering it possible to publish such letters in their entirety, the editors decided to prepare a selection of materials compiled according to the ideas and suggestions of the letter authors, with the necessary additional comments. We hope that the questions raised in the selection will help applicants to universities.

As always, there are a lot of letters in the editorial mail about various algebraic and trigonometric equations and systems. Along with standard problems that are not of particular interest, the authors of a number of letters also propose equations whose solutions contain a “zest” - it is necessary to find a non-standard transformation path and indicate a successful replacement for the unknown.

Here is an equation, the idea of ​​solving which was reported to the editor by our reader M. Levin (Tallinn).

Example 1: Solve the equation

$$\sqrt{x^2 - 9x + 24} - \sqrt{6x^2 - 59x + 149} = 5 - x.$$ (1)

Applicants often begin solving an irrational equation by finding the range of acceptable values ​​of the unknown. It must be borne in mind that this operation (sometimes very cumbersome) is not always necessary to solve the equation. In many cases, it is more profitable and easier to move from the original equation to its consequence, and at the end do a check, or, even better, move on to equivalent equations.

It is quite clear that the standard example of solving irrational equations - exponentiation - when applied to equation (1) will lead to time-consuming calculations with no apparent hope of success. Therefore, try to check other transformations.

Since the value $x=5$, very indo, is the root of equation (1), then when finding its other roots we will assume that $x\neq 5$. Let's divide both sides of equation (1) by 5 - x:

$$\frac{1}{5-x}\sqrt{x^2 - 9x + 24} - \frac{1}{5-x}\sqrt{6x^2 - 59x + 149} = 1,$$ (2)

and let's see what happens if the factors: $\frac{1}{5-x}$ are entered under the root sign. Since, as is known from algebra,

$$a = \sqrt{a^2} \text{ при } a > 0;$$

$$a = -\sqrt{a^2} \text{ при } a < 0,$$

two cases should be considered separately: $5-x>0$ and $5-x<0$.

If $5-x>0$, i.e., if we look for roots of equation (1) satisfying conditions $x<5$, then equation (2) can be rewritten as

$$\sqrt{\frac{x^2 - 9x + 24}{(5-x)^2}} - \sqrt{\frac{6x^2 - 59x + 149}{(5-x)^2}} = 1.$$ (3)

Under the sign of the first root we select the whole part:

$$\frac{x^2 - 9x + 24}{(5-x)^2} = \frac{(x^2 - 10x + 25) + (x - 1)}{(5-x)^2} = 1 + \frac{x-1}{(5-x)^2}.$$

⟦folio 49⟧

Similarly, we transform the fraction under the sign of the second root; As a result, equation (3) will be written in the form

$$\sqrt{1 + \frac{x-1}{(5-x)^2}} - \sqrt{6 + \frac{x-1}{(5-x)^2}} = 1.$$

Now it is already clear that it is advisable to make a substitution

$$\frac{x-1}{(5-x)^2} = y,$$

(4)

after which it remains to solve the equation

$$\sqrt{1+y} - \sqrt{6+y} = 1.$$

Using the general method, we can easily verify that this equation has no roots.

If $5-x<0$, i.e., if we look for roots of equation (1) satisfying the condition $x>5$, then equation (2), as can be easily verified, is reduced to the form

$$-\sqrt{1 + \frac{x-1}{(5-x)^2}} + \sqrt{6 + \frac{x-1}{(5-x)^2}} = 1.$$

After substituting (4) we obtain the equation

$$\sqrt{6+y} = 1 + \sqrt{1+y},$$

whose root is $y=3$. According to (4), this value $y$ corresponds to $x_1=4$ and $x_2=19/3$. The value $x=4$ should be discarded as not satisfying the condition $5-x<0$, and the value $x=19/3$ is the root of the original equation (1), since this equation is equivalent to equation (5) on the set $x>5$. Substitution after this allows us to avoid an unrepresented check by substituting the specified value into the original equation.

So, equation (1) has two roots: $x_1=5$ and $x_2=19/3$.

The following equation, which coincides (with a simple substitution) to an equation similar to the previous one, is edited by our reader A. Smolyakov (Neftekumsk, Stavropol Territory).

1. Solve the equation

$$\frac{1}{|\cos x|} + \sqrt{6} (\lg x + 1) = 8 \sqrt{\lg x}.$$

\* \*

In «Kvant», 1977, No. 3, p. 56-57 discussed one way to solve the equation

$$\sqrt[3]{8x+4} - \sqrt[3]{8x-4} = 2,$$

(6)

who used the cube of both sides of the equation. 9th grade student Nikolai Kim (collective farm named after Ya. M. Sverdlov, Sredne-Chirsky district, Uzbek USSR) responded to this publication. Our reader suggests solving equation (6) differently - by introducing auxiliary unknowns.

Let us introduce the auxiliary unknowns $u$ and $v$ as follows:

$$\sqrt[3]{8x+4} = u, \sqrt[3]{8x-4} = v.$$

Then, by the definition of the root and based on equality (6), we can write a system of equations

$$u^3 = 8x+4, v^3 = 8x-4, u-v=2,$$

(7) and the unknowns $u$ and $v$ must satisfy a non-negative number whose cube is equal to $a$; see "Algebra 8", paragraph 24).

System of equation (7) is easy to solve. In fact, if you subtract the second from the first equation: $u^3 - v^3 = 8$, and then, using the third equation, eliminate, for example, $u$, you get a quadratic equation $v^2+2v=0$, which has roots $v_1=0, v_2=-2$. Using the first root of the second equation of system (7) we find $x=1/2$; the second root must be discarded as not satisfying condition (8). Therefore, the original equation (6) has a single root $x=1/2$.

An attentive reader will easily notice that the proposed method is based on a well-known and often used idea - to find a successful replacement for the unknown for a given equation. As we have seen, when solving irrational equations it is sometimes convenient to introduce several auxiliary unknowns.

⟦folio 50⟧

Now, in detail, solve the following irrational equation yourself, which was sent to the editor by our reader A. Aliev (village of Kubra, Lak district, Dagestan Autonomous Soviet Socialist Republic).

2. Find the roots of the equation

$$\sqrt[3]{24+x} + \sqrt{12-x} = 6.$$

Students learned that equations are usually solved by converting them to the “simplest” form (for example, a quadratic equation). Meanwhile, in applied examples in mathematics, problems are sometimes proposed, the solution of which requires, first of all, logical reasoning. In these problems, as a rule, you need to “see” the possibility of using some property of a known function, apply a familiar inequality, etc. It is on such problems that not only the meaning of constructing rules and formulas studied in school is checked, but also the level of their general mathematical development.

Our reader N. Belevsky (Kharkov) sent to the editor two systems of equations, in the solution of which logical conclusions play a significant role.

Example 2. Solve a system of equations

$$\begin{cases} z^2 + 1 = 2\sqrt{xy}, \\ x^2 - 1 = 2yz\sqrt{1-4xy}. \end{cases}$$

At first glance, this system looks rather strange: there are three unknowns, but only two equations. But this circumstance also serves as a kind of “hint” - we should not rush to transform the equations of the system, but try to first study their properties.

If the equation of system (9) is rewritten as $z^2 = 2\sqrt{xy} - 1$, then, since there is a non-negative expression on the left, we can conclude that $2\sqrt{xy} - 1 \geq 0$, from which

$$1 - 4xy \leq 0.$$

On the other hand, from the second equation of system (9) it is clear that the allowed values ​​of the unknowns $x$ and $y$ must satisfy the inequality

$$1 - 4xy \geq 0.$$

Comparison of correspondences (10) and (11) shows that the solution to system (9) can only be a triple of numbers $(x, y, z)$ such that $4xy = 1$. But then from the first equation of the system we obtain $z = 0$, and from the second it follows that $x_1 = 1$, $x_2 = -1$.

Thus, we get two triplets of numbers $x_1 = 1$, $y_1 = 1/4$, $z_1 = 0$; $x_2 = -1$, $y_2 = -1/4$, $z_2 = 0$, which alone can be solved systems (9). We emphasize that from the performed calculations it does not follow that the found triplets of numbers are indeed solutions to system (9); this fact must be proven by direct substitution into the original system.

We offer the second system to the reader as an equation.

3. Solve system of equations

$$\begin{cases} xz = y + 2, \\ x + z = 2\sqrt{y}(\sqrt{x} - \sqrt{y} + \sqrt{z}). \end{cases}$$

Judging by the letters, the teacher was more interested in one mixing an equation with a parameter, which was discussed in «Kvant» No. 6, 1977, p. 71-73. N. Chuliev (Charjuu, Turkmen SSR) informs the editors of a modification of this example, using the idea of ​​​​introducing an auxiliary unknown.

Example 3: Solve the equation

$$x = a - b(a - bx^2)^2.$$

This equation (of the fourth power of the relative unknown $x$) is easy to solve if you open the parentheses and notice that a better equation can be considered as a quadratic relative $a$. However, a slightly different method of de-wondering also leads to the goal.

Let us introduce the auxiliary unknown $z = a - bx^2$. Then, instead of equation (12), you need to solve the system of equations

$$x = a - bz^2, \quad z = a - bx^2.$$

Subtracting the second from the first equation of the system, we obtain the equalities $x = z$, $b(x + z) = 1$; after excluding the auxiliary unknown

⟦folio 51⟧

we come to two equations:
$$x = a - bx^2; \quad b(x + a - bx^2) = 1.$$

The further solution is very indo. You just have to remember that the solution is about equations with parameters, and it follows carefully the conditions under which the calculations are valid on the parameters. The final answer should look like this:
if $ab < -1/4$, then there are no roots;
if $ab = -1/4$, then there is one root: $x = -1/2b$;
if $-1/4 < ab < 0$, then there are two roots:
$$x_1 = \frac{-1 - \sqrt{1 + 4ab}}{2b} \quad \text{и}$$
$$x_2 = \frac{-1 + \sqrt{1 + 4ab}}{2b};$$
if $b = 0$, then there is one root: $x = a$;
if $a = 0$ but $b \neq 0$, then there are two roots: $x = 0$ and $x = -1/2$;
if $0 < ab < 3/4$, then there are two roots: $x_1$ and $x_2$;
if $ab = 3/4$, then there are three roots: $x_1, x_2$ and $x = 1/2b$;
if $ab > 3/4$, then there are four roots: $x_1, x_2,$
$$x_3 = \frac{1 - \sqrt{4ab - 3}}{2b} \quad \text{и}$$
$$x_4 = \frac{1 + \sqrt{4ab - 3}}{2b}.$$

Of course, the above messages also apply in the case when the equation under consideration does not contain any parameter.

Example 4: Solve the equation
$$x^2 + \sqrt{x + 5} = 5.$$

To solve this equation, it is convenient to introduce the auxiliary unknown $z = \sqrt{x + 5}$ and go to the system of equation $x^2 + z = 5, x + 5 = z^2$. After estimated transformations we arrive at two irational equations
$$\sqrt{x + 5} + x = 0; \sqrt{x + 5} = x + 1,$$
from which we obtain two roots of equation (13):
$$x_1 = \frac{1 - \sqrt{21}}{2}, \quad x_2 = \frac{\sqrt{17} - 1}{2}.$$

Among the equations sent to Shimich by readers, many are solved by factorization. However, it is not always easy to “see” the grouping that leads to the desired result. The first of the equations noted below were proposed by A. Ermilov (Kolomna, Moscow region), the next two by L. Slukin (Lipetsk), and the last, most difficult, by 10th grade student Seidazim Mirtsev (village of Khilly, Neftechala region, Azerbaijan USSR).

Solve equations:
4. $$\frac{x^2}{\sqrt{3x - 2}} - \sqrt{3x - 2} = 1 - x.$$
5. $x^2 + \frac{1}{x} - 2 = 0.$
6. $x^4 + 4x^3 + 3x^2 + 2x - 1 = 0.$
7. $x^4 - 12x - 5 = 0.$

It is well known that a geometric problem, in which long and cumbersome calculations lead to the goal, can sometimes be solved in just a few lines. To do this, you just need to select the “key” to the problem—guess how to apply a certain theorem, see the additional construction, and be able to take advantage of the specifics of the configuration. It’s a good idea to get your head around such an unconventional solution, although it’s much more useful to first try it on your own. Find it (and there will be crawling even if the search remains flawless).

Many readers of the magazine responded with interest to the proposal made in the “Applicant's Workshop” to send to the editor short and clear solutions to problems proposed in the entrance exams. Several similar problems are listed below. You can solve them without “geometric imagination” (after the problems are formed, it is indicated where the solutions are also published). We invite applicants to find solutions to these problems that do not require cumbersome calculations. Such solutions for the first three problems were reported to us by P. Gorshitey (Kyiv); solutions to the following problems were indicated by Y. Aizenitam (Kyiv).

8. In parallelogram $ABCD$ the angle at vertex $A$ is equal to $\alpha < \pi/2$. The height dropped from the vertex $B$ to the side $AD$ divides the diagonal $AC$ in the ratio $m:n$. Find the ratio of the side length of the parallelogram.

⟦folio 52⟧

(Shakhno K.U., How to prepare for university entrance exams in mathematics, Minsk, “Higher School”, 1970, problem 423.)

9. On two adjacent sides of the square, as diameters, two semicircles are built, lying in a square, and to each semicircle a quadrilateral is drawn, parallel to the side of the square that is the diameter of this semicircle. Find the length of the radius of the circle, the external image of the quadoceros of these semicircles and the quadoceros constructed by the quadella. (Shakhno K.U. “Collection of problems in elementary mathematics of increased difficulty”, Minsk, “Higher School”, 1969, problem 932.)

10. The legs [AB] and [AC] of a right-angled triangle are located respectively in faces P and Q at the acute dihedral angle of magnitude φ. The leg [AB] forms an acute angle α with the edge of the dihedral angle. Determine the angle between this edge and the leg [AC]. («Kvant», 1976, no. 2, p. 58 and no. 3, p. 76.)

11. A regular triangular triangle is inscribed into a sphere whose radius has length R.

(For the beginning see pp. 21, 38)

(N. Dvor, Grodno region) 46, 51, 54, 56, 60a); I. Savenkov (Bald Mountains, Saratov region) 54; V. Sakovin (Pastavy) 50; M. Sevriok (Moscow) 56, 58; A. Semov (Chelyabinsk) 54; P. Serdore (p/n Anna, Voronezh region) 56; A. Sivatsky (Leningrad) 47, 50, 51; V. Sidorenko (Krasnoisk) 51, 54, 56; P. Silvestrov (Novosibirsk) 48; O. Slavyansky (Leningrad) 47; Yu. Smirnov (Leningrad) 46-48, 50, 51, 53-55; A. Starkov (Moscow) 46, 47; V. Stovba (Moscow) 46, 48, 51, 52, 55—57, 59; F. Sukachev (Tashkent) 54; K. Tamalyan (Yerevan) 51, 53, 54; Z. Tleshov (Alma-Ata) 52, 54; V. Trofimov (Moscow) 46, 48, 50-58; K. Trumnev (Kazan) 51, 57; G. Tyurin (Kursk) 46; A. Udavixin (Ioshkar-Ola) 46; V. Falko (Kharkov) 46; N. Fedin (Omsk) 47, 52, 54, 56; Y. Fedorov (Leningrad) 51, 57; G. Firsova (Leningrad) 52, 54; I. Fomenko (Dnepropetrovsk) 49a); M. Khaimov (Voronezh) 50; I. Hangl (Czechoslovakia) 58; S. Khosid (Almaty) 54; M. Chereninsky (Voronezh) 47, 48, 60a), 6); D. Shafer (Leningrad) 56; V. Shenkarb (Kyiv) 54; A. Shilo (Kivertsy) 54; A. Shikhakhmedov (Derbent) 54; I. Shlyakhova (Lobnya) 54; D. Shulbaev (Alma-Ata) 46—48, 52, 54, 57, 60a), 6); A. Shulevov (Kamensk Uralsky) 51.

Physics

Almost all readers who sent solutions to problems F. Azakshev (village of Zarat AzSSR) 51; K. Hakobyan (Yerevan) 52; E. Alexandrova (Glazov) 55; M. Alekseev (Obninsk) 52; E. Alisenderov (village Dash Salahli AzSSR) 52; A. Antonyan (Yerevan) 60; A. Arbatsky (Blagoveshchensk, Amur region) 50; A. Bakan (Kyiv) 51; S. Bavkun (Cherkesck) 51, 52, 62; Yu. Balashov (Moscow) 60, 61; A. Baruev (Ulan-Ude) 53, 57; A. Barzikin (p.
