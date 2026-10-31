---
id: 1971-10-sorkin-shkundina-olimpiadu-provodit-elektronnaya-vyichislitelnaya-mashina-1898a162
issue: kvant_1971_10
year: 1971
number: "10"
title: The Olympics are conducted by an electronic computer
authors:
  - Соркин Ю. И.
  - Шкундина Н. Б.
rubric: informatsiya
rubric_sub: Информация
page_first: 60
page_last: 64
page_labels: 58-62
tag: O7TJ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2f7d376d25c5df6fd76a63a29a8510a5206ecbab5702da4add6b9615ba6bfe8f
prompt_sha256: draft-1
translated_from: content/ru/1971/10/articles/17_sorkin-shkundina-olimpiadu-provodit-elektronnaya-vyichislitelnaya-mashina-1898a162.md
source_content_sha256: d92357caa469f9d6c0982c03e5af43a773538b8a1e16df91a8d674cc6002877e
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 58⟧

THE OLYMPICS IS CONDUCTED BY AN ELECTRONIC COMPUTING MACHINE

Yu. I. Sorkin,
N. B. Shkundina

In January - April of this year, for the first time, the Moscow Institute of Economics and Statistics held a mathematical Olympiad for high school students, taking into account electronic computers. The Olympics were held in two rounds. The second round was carried out using Minsk-22 machines; only schoolchildren who successfully completed the first round were allowed to participate in it.

The first round was held in absentia. All interested schoolchildren from Moscow and surrounding areas of the Moscow region took part in it. To solve the fifth problem of the first type, a period of one month was given (that is, until February 15).

First round tasks

1. A cube with an edge and a midplane at the corners so that each face remains a regular polygon. Find the volume of the resulting body.
2. Does the equation $b^2x^2 + (b^2 + c^2 - a^2)x + c^2 = 0$, where a, b and c are the side lengths of a certain triangle, have a valid solution?
3. The sum of several consecutive natural numbers is 1000. Find all such sequences.
4. Prove that for an obtuse triangle the inequality $\cos^2 A + \cos^2 B + \cos^2 C > 1$ holds.

⟦folio 59⟧

5. Determine the angle of a triangle in which the median, bisector and altitude divide the angle into quadruples.

Analysis of the problems of the first round

1. It is clear that each of the eight objects surrounding the cube at the corners of the body is a regular triangular primid with right angles between the lateral edges (Fig. 1). If

Fig. 1.

denote the side of the base of the primid by $b$, then $AD = \frac{b\sqrt{3}}{2}, OD = \frac{b\sqrt{3}}{6}, CD = \frac{b}{2}$, and then, by the Pythagorean theorem, the height of the primid is $EO = \frac{b\sqrt{6}}{6}$. The area of ​​the base is $\frac{b^2\sqrt{3}}{4}$. Therefore, the volume of such a primid is equal to $\frac{b^3\sqrt{2}}{24}$, and the volume of a body obtained from a cube among eight such primids is equal to

$$a^3 - \frac{b^3\sqrt{2}}{3}.$$

Since, according to the conditions of the problem, regular polygons should remain from the faces of the cube, then the solution is two. Can be octagons or squares (Fig. 2 $a, 6$).

In the first case, $b = a(\sqrt{2} - 1)$, and then from (1) after transformation we obtain $V = \frac{7a^3(\sqrt{2} - 1)}{3}$.

In the second case, $b = \frac{a\sqrt{2}}{2}$, and then from (1) we find $V = \frac{5a^3}{6}$.

Note that only 20% of schoolchildren found both solutions to the problem. The remaining findings are only one solution. In this case, there was no pre-option for any one of the two polygons - which received an approximately equal number of heads.

2. Let us show that the discriminant $D$ of this quadratic equation

Fig. 2a.

Fig. 26.

⟦folio 60⟧

negative Really,
$$D = (b^2 + c^2 - a^2)^2 - 4b^2c^2 = (b^2 + c^2 - a^2 - 2bc)(b^2 + c^2 - a^2 + 2bc) = [(b - c)^2 - a^2] \times [(b + c)^2 - a^2]$$
but since $a, b$ and $c$ are side lengths of the triangle, then $|b - c| < a$ and $b + c > a$, that is, corresponding to $(b - c)^2 - a^2 < 0$ and $(b + c)^2 - a^2 > 0$, that is, $D < 0$.

3. Let the required sequence have the form
$$k + 1, k + 2, \dots, n - 1, n$$
Then its sum can be represented as the difference between the sums of segments of the natural series from 1 to $n$ and from 1 to $k$, that is
$$\frac{(n + 1)n}{2} - \frac{(k + 1)k}{2} = 1000$$
or $n^2 + n - k^2 - k = 2000$.
Let us decompose the left side of this equality into two factors, and the right side into prime factors:
$$(n + k + 1)(n - k) = 2^4 \cdot 5^3$$
Note that both factors $n + k + 1$ and $n - k$ on the left side of this equality cannot be even, since their sum $2n + 1$ is odd. In addition, the first factor is greater than the second. Thus we come to a set of four systems:
$$\begin{cases} n + k + 1 = 2000, \\ n - k = 1, \end{cases} \quad \begin{cases} n + k + 1 = 400, \\ n - k = 5, \end{cases} \quad \begin{cases} n + k + 1 = 80, \\ n - k = 25, \end{cases} \quad \begin{cases} n + k + 1 = 125, \\ n - k = 16. \end{cases}$$
The first of these systems gives a trival "sequence" consisting of the singular number 1000. The remaining systems give the sequence:
198, 199, 200, 201, 202;
28, 29, ..., 51, 52;
54, 55, ..., 69, 70.

4. Let the angle $C$ be used to define the types. Then $0 < B < \frac{\pi}{2} - A$, and therefore
$$\cos B > \cos \left( \frac{\pi}{2} - A \right) = \sin A > 0$$
and therefore $\cos^2 B > \sin^2 A$.

Then $\cos^2 A + \cos^2 B > \cos^2 A + \sin^2 A = 1$, that is, $\cos^2 A + \cos^2 B > 1$, and thus even more so
$$\cos^2 A + \cos^2 B + \cos^2 C > 1$$
Q.E.D.

5. The overwhelming number of Odimpad participants solved this problem

Fig. 3.
Introduction to the consideration of the auxiliary circle (see «Kvant» No. 1, 1971). However, this problem allows for a shorter solution (Galina Averbukh, $10^6$ class of school No. 200, Alexey Vodovozov, $10^a$ class of school No. 569).

Let in the triangle $ABC$ (Fig. 3) the median $BD$, the bisserris $BE$ and the altitude $BF$ divide the angle $B$ into four equal parts, each of which is denoted $\alpha$. Then
$$AF = h \ tg 3\alpha; DF = h \ tg 2\alpha$$
and $FC = h \ tg \alpha$.
Next
$$AD = AF - DF = h \ (tg 3\alpha - tg 2\alpha)$$
$$DC = DF + FC = h \ (tg 2\alpha + tg \alpha)$$
but by condition $AD = DC$, that is
$$tg 3\alpha - tg 2\alpha = tg 2\alpha + tg \alpha$$
or
$$2 \ tg 2\alpha = tg 3\alpha - tg \alpha$$
$$\frac{2 \sin 2\alpha}{\cos 2\alpha} = \frac{\sin 2\alpha}{\cos 3\alpha \cos \alpha}$$

Since $\sin 2\alpha \neq 0$, then $2 \cos 3\alpha \cos \alpha = \cos 2\alpha$ or
$$\cos 2\alpha + \cos 4\alpha = \cos 2\alpha$$
that is, $\cos 4\alpha = 0$.
It follows that the angle $B$ belongs to.

⟦folio 61⟧

Second round

Forty children who successfully passed the first round gathered at MESI on April 25 to continue the “competition.”

In the second round, one of the “members” of the Olympic organizing committee was the Minsk-22 electronic embroidery machine. This “member” had the main job. Several thousand tasks were stored in the machine memory. Each problem was equipped with a special code indicating the section of mathematics to which this problem belongs and the degree of difficulty (all problems were from different sections of mathematics with the same total difficulty).

The machine for each Olympic participant was called Varnan.

After the deadline (four hours of 45 minutes) the work was separated into a machine for inspection*). The machine compared the resulting solutions to the problem with the properties, and those who solved all five problems correctly were announced as winners. The machine completed all this work while the Olympiad participants were getting acquainted with the institute.

Six tenth grade students of Moscow schools were presented with MESI certificates and memorable gifts:

*Elena Savina, Victor Zak, Sergey Mapenov, Mark Ritzel, Alexander Rozin, Leonid Terekhov.

Carrying out the Mathematical Olympiad by machine was the final stage of the work on conducting meeting exams in mathematics and physics using a computer. This great work is being carried out under the leadership of the rector of MESI, prof. M. A. Koroleva, prof. I. G. Venetsky and Doctor of Technical Sciences A. G. Morozov.

*) All problems had numerical answers.

1. A cylinder is described around a cube so that the diagonal of the cube is the axis of the cylinder. Find the area of ​​the lateral surface of the cylinder if the diagonal cross-sectional area of ​​the cube is $18 - 6\sqrt{2}$.

2. Solve the equation
$$\lg^2 3 + \lg^2 2 = \lg^2 3x + \lg^2 2x.$$

3. The section divides the triangular pyramid into two polyhedra. How does the volume of these polyhedra relate if the edges are divided by this section in a ratio of 1:2; 1:2; 1:3, counting from the top?

4. Find the rational root of the equation
$$\frac{2}{\sqrt{x}} + x\bar{x} = 3.$$

5. Solve the equation
$$5^{3x} + 9 \cdot 5^x + 27 (5^{-3x} + 5^{-x}) = 64.$$

6. The base of the pyramid $SABCD$ is a rhombus with diagonals $AC=a; BD=b$. The side edge $SA$ is perpendicular to the plane of the base and is equal to $q$. Through the point $A$ and the middle $K$ of the edge $SC$ a plane is drawn parallel to the diagonal of the base $BD$. Determine the cross-sectional area.

7. Find the smallest root of the equation
$$\sqrt[4]{97-x} + \sqrt[4]{x-15} = 4.$$

8. Solve inequality
$$x^{\log_2 x}-4 < 32.$$

9. The cone and the cylinder have a common base, and the apex of the cone is at the center of the other base of the cylinder. What is the sine of the angle between the axis of the cone and its core, if it is known that the total surface of the cylinder is related to the total surface of the cone as seven to four?

10. Find the smallest root of the equation
$$\sqrt[3]{x^2+14x+24} - \sqrt[3]{x^2-5x+14} = \sqrt[3]{x+2}.$$

⟦folio 62⟧

To the article “Systems of algebraic equations”

1. (3, 1, -2); (-5, -3, 0).
2. (2, -1/2, 4); (-2, 1/2, -4);
   ($\sqrt{2}/2, \sqrt{2}, 2\sqrt{2}$);
   ($-1\sqrt{2}/2, -\sqrt{2}, -2\sqrt{2}$).
3. (1, 0, -1/2); (-1, 0, 1/2);
   $(i/\sqrt{3}, -2i/\sqrt{3}, i/2\sqrt{3})$;
   $(-i/\sqrt{3}, 2i/\sqrt{3}, -i/2\sqrt{3})$.
4. (0, 0, 0); (1, 2, 5); (-1, 2, -5);
   (-1, -2, 5).
5. (0, 0, 0); $(-1/2, -1, 2)$
6. (0, 0, 0); (-1, 2, 3).
7. (0, 0, 0); $(-3/4, 1/2, -2/4, 1/2)$.
   $(3/4, 3/4, 7/4, 3/4)$.
   $-\frac{5}{4}, \frac{3}{4}, \frac{3}{4}$.

To the article “Chess and mathematics notes” (see «Kvant» No. 9)

1. Mark out all squares of the board (except for the central one, which the knights cannot reach) in the order in which the knight traverses them (Fig. 1 a) and consider the auxiliary figure 1 b.

Fig. 1 a.
Fig. 1 b.

2. Take a floor 2 fields wide that runs along the edge of the board. Make sure that the horse can pass through all the squares of this stripe, stepping on each of them once (you can start from any square of this stripe). Divide the entire board into such stripes and start your path from the central field.

3. $m^2n^2 - 9mn + 12m + 12n - 16$. With $m = n = 8$ we get 3696.

4. Let us denote the required number of fields by $N(n)$. It is easy to check directly that $N(0) = 1$, $N(1) = 8$, $N(2) = 33$. With $n = 3$ the knight can end up on all the white squares of the eighth knight with squares on each side shown on figure 2 (the initial square is in the center). Prove the method of mathematical induction that for any $n \geq 3$ the required fields fill without gap all single-link fields corresponding to the eighth end of the fields, we obtain: $N(n) = 17n^2 + 4n + 1$ for $n \geq 3$.

5. The numbers $m$ and $n$ must be coprime, and at least one of them must be odd.

To note «Kvant» for younger students

(«Kvant» No. 9, 1971, 3rd cover page)

1. It is forbidden. Although the scales are balanced, nevertheless, loads of equal mass placed on the scales will create different moments relative to the yoke axis.

2. In the evening it is dark and therefore a person’s pupils are dilated. But the lens of the eye is not a perfect lens. The images produced by different parts of the lens are mixed relative to each other due to aberration. The more part of the lens “works”, the blurrier the image.

3. Having immersed the tip of the bulb balloon in a container of water and broken it, use a ruler to change the volume of water. Then, fill the balloon completely with water and change the volume of the balloon. Using that $p_1V_1 = p_2V_2$, it is now easy to find the pressure in the cylinder.

4. Immerse the balloon in the lake up the house, use a ruler to change the remaining volume of air. Then proceed in the same way as in task 3.

5. Due to multiple reflections of light at the boundaries of the crystals.
