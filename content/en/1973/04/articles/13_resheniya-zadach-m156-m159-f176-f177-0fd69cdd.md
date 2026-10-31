---
id: 1973-4-resheniya-zadach-m156-m159-f176-f177-0fd69cdd
issue: kvant_1973_4
year: 1973
number: "4"
title: Solutions to problems M156—M159; F176—F177
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 48
page_last: 53
page_labels: 46, 47, 48, 49, 51
tag: S30U
lang: en
source: kvant_digital
extraction: vision
content_sha256: 300dad6a3f3d9f747c3db3e1abf91aebd1efb2c2d58b2980f6550af59ebe7746
prompt_sha256: draft-1
translated_from: content/ru/1973/04/articles/13_resheniya-zadach-m156-m159-f176-f177-0fd69cdd.md
source_content_sha256: 34d02eb2ea6502f331296a1cca5c1ea2f6b35fc722d8ddb48b42b10f8e058f8f
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

Problem solutions

M156-M159; F176-F177

M156. In rectangle ABCD, point M is the midpoint of side AD, N is the midpoint of side BC. On the continuation of the segment DC, point D is taken to be point P. Let us denote the point of intersection of lines PM and AC by Q. Prove that QNM = MNP.

The problem has many simple geometric solutions. Here's one of them.

Let O be the center of the rectangle (see Fig. 1) (the point of intersection of MN and AC), K the point of intersection of QN with the perpendicular to the segment MN at its midpoint O. Then, as is easy to see, QM/MP = QO/OC = QK/KN, and therefore MK||PN. But the triangle MKN is equilateral: by construction, KO has both the height and the median. Postural QNM = KMN = MNP.

It is not difficult to solve the problem using calculations. For example, you can use the coordinate method. If we introduce a coordinate system as shown in figure 2, then the $(x_0, y_0)$ coordinates of point Q satisfy two equations:

$(p - 2b)x - ay = -2ab$ (equation of line MP) and $bx + ay = ab$ (equation of line CA).

Multiply the second equation by 2 and add it to the first. We get (for $x = x_0, y = y_0$) $px_0 + ay_0 = 0$. Thus, the slope of the straight line NQ is equal to $\frac{y_0}{x_0} = -\frac{p}{a}$,

Fig. 1. Fig. 2.

M157. The sum of n positive numbers $x_1, x_2, x_3, \dots, x_n$ is equal to 1. Let S be the largest number

$$\frac{x_1}{1+x_1}, \frac{x_2}{1+x_1+x_2}, \dots, \frac{x_n}{1+x_1+x_2+\dots+x_n}.$$

Find the smallest possible value of S. At what values ​​of $x_1, x_2, \dots, x_n$ is it achieved?

Suppose that the positive numbers $a_1, a_2, \dots, a_n$ are such that $a_1 + a_2 + \dots + a_n = 1$ and

$$\frac{a_1}{1+a_1} = \frac{a_2}{1+a_1+a_2} = \dots = \frac{a_n}{1+a_1+a_2+\dots+a_n}.$$

(We will see below that such a set $a_1, a_2, \dots, a_n$ actually exists.) Let us show that for $x_1 = a_1, x_2 = a_2, \dots, x_n = a_n$ the value S takes on the smallest possible value. Let $b_1, b_2, \dots, b_n$ be another set of positive numbers whose sum is equal to 1. Note that if $x_k$ is increased, and all previous $(x_1, x_2, \dots, x_k-1)$ are not increased, then the quantities

$$\frac{x_k}{1+x_1+\dots+x_{k-1}+x_k} = \frac{1}{\frac{1}{x_k}+\frac{x_1}{x_k}+\dots+\frac{x_{k-1}}{x_k}+1} = \frac{1}{1+x_1+\dots+x_{k-1}+x_k} + 1$$

will increase.

Pozny, if $b_1 > a_1$, then $\frac{b_1}{1+b_1} > \frac{a_1}{1+a_1}$; if $b_1 \leq a_1, b_2 > a_2$, then $\frac{b_2}{1+b_1+b_2} > \frac{a_2}{1+a_1+a_2} = \frac{a_1}{1+a_1}$; if $b_1 \leq a_1, b_2 \leq a_2, b_3 > a_3$, then $\frac{b_3}{1+b_1+b_2+b_3} > \frac{a_3}{1+a_1+a_2+a_3} = \frac{a_1}{1+a_1+a_2+a_3}$, etc. Since the set of numbers $b_1, b_2, \dots, b_n$ is different from the set $a_1, a_2, \dots, a_n$, and the sum of the numbers in the common sets

⟦folio 47⟧

rah is the same, then $b_k > a_k$ for some $k$. Let $k$ be the smallest index with this property, that is, $b_1 \leq a_1, b_2 \leq a_2, \dots, b_{k-1} \leq a_{k-1}, b_k > a_k$, then

$$\frac{b_k}{1+a_1+\dots+a_k} > \frac{a_k}{1+a_1+\dots+a_k} = \frac{a_1}{1+a_1}.$$

Thus, the largest of the numbers

$$\frac{b_1}{1+b_1}, \frac{b_2}{1+b_1+b_2}, \dots, \frac{b_n}{1+b_1+\dots+b_n}$$ greater than $\frac{a_1}{1+a_1}$

the largest of the numbers $\frac{a_1}{1+a_1}, \frac{a_2}{1+a_1+a_2}, \dots, \frac{a_n}{1+a_1+\dots+a_n}$.

It remains to solve the system of equations in positive numbers

$$\begin{cases} x_1+x_2+\dots+x_n=1, \\ \frac{x_1}{1+x_1} = \frac{x_2}{1+x_1+x_2} = \dots, \\ \dots = \frac{x_n}{1+x_1+x_2+\dots+x_n}. \end{cases}$$

The equation $\frac{x_1}{1+x_1} = \frac{x_k}{1+x_1+\dots+x_k}$ (for positive $x_1, x_2, \dots, x_k$) is transformed to the form $x_k = (1+x_1+\dots+x_{k-1})x_1$, so this system is equivalent to the system

$$\begin{cases} x_2 = (1+x_1)x_1, \\ x_3 = (1+x_1+x_2)x_1, \\ \dots, \\ x_n = (1+x_1+\dots+x_{n-1})x_1, \\ x_1+x_2+\dots+x_n=1, \end{cases}$$

which in turn is equivalent to the system

$$\begin{cases} x_2 = (1+x_1)x_1, \\ x_3 = (1+x_1)^2x_1, \\ \dots, \\ x_n = (1+x_1)^{n-1}x_1, \\ x_1+x_2+\dots+x_n=1, \end{cases}$$

that is, the numbers $x_1, x_2, \dots, x_n$ form a geometric progression with value $(1+x_1)$ and sum $(1+x_1)^n-1$.

1. Teler can easily find a solution to the system:

$$a_1 = \sqrt[n]{2}-1, a_2 = \sqrt[n]{2}\left(\sqrt[n]{2}-1\right), a_3 = \sqrt[n]{2^2}\left(\sqrt[n]{2}-1\right), \dots, a_n = \sqrt[n]{2^{n-1}}\left(\sqrt[n]{2}-1\right).$$

The required value of $S$ is

$$\frac{\sqrt[n]{2}-1}{\sqrt[n]{2}} = 1 - \frac{1}{\sqrt[n]{2}}.$$

M158. The triad table is constructed according to the following rule: the natural number $a > 1$ is written in the top line, and then under each number $k$ there follows $k^2$, and on the right - the number $k+1$. For example, with $a = 2$ the table is obtained:

Prove that in each row of the table all numbers are different.

Let's assume that some rows of the table contain the same numbers. Let $n$ be the number of the topmost of these lines, $p$ and $q$ be equal numbers in the line numbered $n$. Since there are no equal numbers in the previous line, then $p$ and $q$ are obtained from the numbers in the previous line by different actions: one by squaring, the other by adding 1. Let $p = r^2$, $q = s+1$, so that $s = r^2-1$. The numbers $r$ and $s$ are located in the $(n-1)$-line. Let's consider the path along which the number $s$ was obtained from the number $a$. Let us assume that along this path we encountered squaring. Since $s < r^2$, the largest number we can square would be $r-1$. But $s-(r-1)^2 = 2r-2$. This means that the number $s$ from the number $(r-1)^2$ could only be obtained by adding 2$r-2$ steps. Thus, the number $s$ was obtained from the number $a$ in no less than $2r-1$ steps, so that $n-2 \geq 2r-1$. But all the numbers obtained from the number $a$ in that number of steps are not less than $a+2r-1 > r$, while the number $r$, located in the same line as $s$, is obtained from $a$ in the same number of steps as $s$. Thus, when obtaining the number $s$ from the number $a$ there was no squaring. The same can be said about the number $q = s+1$. Therefore, $q$ is the smallest rightmost number in its row, which contradicts the equality $q = p$.

The problem can be summarized as follows.

Let $f$ be a function defined on the set of natural numbers and taking values. Suppose $f(n+1)-f(n)>n+1$ for every natural number $n$. Therefore, a triangular table according to the same scheme as in the given one, but applying each time

⟦folio 48⟧

function $f$ together with squaring:

Then in each row of the table all the numbers are different.

Let us give one interesting corollary problem M158.

Let an infinite sequence of positive numbers $a_1, a_2, a_3, \dots$ be such that for every natural number $n$
$a_n < a_{n+1} + a_n^2$,
so $a_2 < a_3 + a_4, a_3 < a_4 + a_9, a_4 < a_5 + a_{16}$, etc. Then from these numbers you can choose several, the sum of which is greater than 1000. The number 1000 here can be replaced by any other number. (As they say, row $a_1 + a_2 + a_3 + \dots + a_n + \dots$ diverges.)

Condition (*) is satisfied, in particular, by the sequence $a_n = 1/n$, so from this corollary one can obtain another proof of the signs of the theorem on the divergence of the harmonic series $1 + \frac{1}{2} + \frac{1}{3} + \frac{1}{4} + \dots$: the sum of distinct numbers, the inverses of natural numbers, can be increased by a larger ring.

M159. Is it possible to consider the numbers 0, 1, 2. in the cells of a sheet of checkered paper of size $100 \times 100$ in such a way that in each rectangle $3 \times 4$, the sides of which go along the rows of cells, there would be at zero what ones and five two?

Let's assume that we managed to fill out a sheet of checkered paper as required. Let us note that the first number in the two rectangles shaded at figure $3$ is equal to zeros, equal to ones and equal to two, since they are complemented by the same figure to the rectangle $3 \times 4$. For the same reason, there are an equal number of zeros, an equal number of ones, and an equal number of twos in the rectangle, shaded at figure $4$. Let us now prove a series of statements about the location of zeros, ones and twos.

1. The rectangle $1 \times 3$ has at most one zero.

Indeed, if there is more than one zero in the red rectangle $1 \times 3$ on figure $5$, then there is more than one zero in each of the two red rectangles $1 \times 3$ and $1 \times 4$. At the same time, both empty rectangles belong to one rectangle $3 \times 4$, which must contain three zeros.

2. The rectangle $1 \times 4$ has at most one zero.

If there are two zeros in the red rectangle $1 \times 4$ on figure $6$, then they are located exactly as shown in figure. There should be two zeros in the green rectangle, therefore, one zero in each of the green rectangles. But then there are no zeros in the two rectangles $1 \times 4$ located between the red and light rectangles (otherwise there would be a rectangle $3 \times 4$ with more than three zeros). Therefore, there are only two zeros in the circled rectangle $3 \times 4$.

3. There is at least one zero in the rectangle $1 \times 4$.

If there are no zeros in the red rectangle $1 \times 4$ on figure $7$, then there are none in the light rectangle. Therefore, two rectangles $1 \times 4$ must have three zeros between them. At the same time, each of these rectangles contains no more than one zero.

Thus, in each rectangle $1 \times 4$ equals one zero.

4. Rectangle $1 \times 4$ contains no more than two ones.

If there are more than two units in the red rectangle $1 \times 4$ on figure $8$, then there are more than two units in the light rectangle $1 \times 4$ and at least two in the green rectangle $1 \times 3$. But then there is a rectangle $3 \times 4$ containing more than four ones.

⟦folio 49⟧

5. There are at most two boards in rectangle $1 \times 4$.
If there are more than two boards in the red rectangle $1 \times 4$ on figure 8, then there are more than two boards in the head and at least two in the green rectangle. The rectangle $1 \times 4$, located above the head rectangle, has at least one two, since it contains at most two ones and one zero. Therefore, there are more than five boards in the circled rectangle $3 \times 4$.

6. There is at most one unit in the rectangle $1 \times 3$.
If there are two units in the red rectangle $1 \times 3$ on figure 9, then there are two units each in the head rectangles $1 \times 4$ and $1 \times 3$. Since there is a one in the green rectangle (it contains at most two boards and one zero), then the circled rectangle $3 \times 4$ has more than four ones.

7. There is at least one unit in the rectangle $1 \times 3$.
If there is not a single one in the red rectangle $1 \times 3$ on figure 10, then since there is at most one unit in each of the head rectangles, there are only three ones in the rectangle $3 \times 4$.

Thus, in each rectangle, $1 \times 3$ is equal to one unit.

Let's take some zero. There is a unit next to it, since otherwise we would have a rectangle $1 \times 3$ without units. Since there should be one zero in the rectangle $1 \times 4$, and one unit in the rectangle $1 \times 3$, the next two cells are occupied by twos: $0 \mid 1 \mid 2 \mid 2$.

The cell next to the twos must contain both a zero and a one, since otherwise it will find, respectively, either a rectangle $1 \times 4$ without a zero, or a rectangle $1 \times 3$ without ones.

We finally got the required contradiction.

All of the above arguments are valid if the red rectangle with which we started each time is not too close to the border of the cell sheet. But the sheet size ($100 \times 100$) is quite enough for this. Try to find out for which smallest square sheet the statement of the problem is true.

Yu. I. Ionin

Correct solutions to some of the problems M151—M159 were added (the last digit of the solved problem numbers is indicated after the last name): S. Abramov (Moscow) 1; O. Adanina (Moscow) 2; A. Baraov (Urvansky district of the Kabardino-Balkarian Autonomous Soviet Socialist Republic) 3; O. Beelaryan (Sisan Armenian USSR) 1, 6; O. Belolinetsky (Kirichach) 1; V. Benkhan (Kalinin) 1; A. Blinov (Moscow) 6; A. Blokh (Kharkov) 1—4, 6, 7; A. Valkov (Tashkent) 1, 6; S. Vasiliev (Ufa) 1, 6; G. Visotskaya (Krasnoisk) 1; L. and I. Gotman (Arzamas) 6; A. Gritsoryan (Baku) 1—4, 6, 7; S. Gritsoryan (Yerevan) 1, 2; E. Gurvits (Tashkent) 6; E. Gusev (Pavlograd, Dnepropetrovsk region) 1, 4, 6; K. Danilenko (Volgograd) 1, 6; Z. Dyachenko (Andrushevka, Zhytomyr region) 1; R. Yedoryan (Hrazdan) 1; A. Zhdanov (Slavyanskaya-Kuban) 1; V. Zarubin (Summer Holidays of the Moscow Region) 1, 6; Z. Zeifman (Orreev MASSR) 1; L. Zelikov (Odessa) 1, 2; S. Zenovich (Tashkent) 1, 6; A. Izrailevich (Sverdlovsk) 1; V. Karasev (Yaroslavl) 1; V. Kvasnitsky (Korkino village, Chelyabinsk region) 6; V. Kovtunets (Shostakov village, Rivne region) 1, 7; V. Kolosov (Kyiv) 6; I. Komolev (Firsanovka, Moscow region) 6; M. Levin (Vitebsk) 6; A. Litovchenko (Belokorovich, Zhytomyr region) 1; M. Lomakin (village of Kersh-Vorki, Tambov region) 1, 6; G. Lutincer (Chernivtsi) 1; E. Mazur (Derbent) 1; A. Makariev (Lviv) 1, 2, 4, 6, 7; P. Manelov (Tbilisi) 6; B. Maryanovsky (Vinnitsa) 1, 2, 4; I. Medzhibovsky (Moscow) 1; E. Mett (Leningrad) 1; O. Myasikova (Uman) 1; G. Nadiryan (Yerevan) 1; S. Nuzhny (Kuibyshev) 1; A. Okrue (Donetsk village, Kirovsk) 6; V. Palatnik (Baku) 6, 8; V. Panarin (Krasnoisk) 1; P. Paramonov (Moscow) 1-4; A. Razulyaev (Klin) 1, 3, 8; A. Reznikov (Kyiv) 1; I. Rivlis (Tiraspol) 6; R. Rozhkov (Ryazan) 6; L. Rudtser (Kharkov) 1; M. Sapir (Sverdlovsk) 1, 2, 4; V. Sats (Kyiv) 1; Y. Simkin (Moscow) 1, 6; R. Siroma (Kharkov) 1, 2, 6; S. Sokov (village of Sokovki, Slovodsk region) 1;

⟦folio 51⟧

ohno shown on figure in red. However, to cut cheese or other sticky foods, you just have to apply pressure on the knife. The friction force between the cheese and the knife is high, making it difficult to move the knife.

F177. The frequency of vibration of a string depends on its length, tension and on the positive density - the mass of a unit of string. Determine the type of these dependencies.

From physical considerations (by analogy with the oscillations of a magnet), it is clear that the dependence of the oscillation frequency of the string $v$ on its length $l$, tension force $F$ and positive density $\rho$ can be represented in the following form:

$$v \sim l^\alpha F^\beta \rho^\gamma,$$

where $\alpha$, $\beta$ and $\gamma$ are dimensionless constants. To solve the problem, we will use the method of dimensions*, according to which $\alpha$, $\beta$ and $\gamma$ must be such that the equality holds

$$[v] = [l^\alpha F^\beta \rho^\gamma] = [l]^\alpha [F]^\beta [\rho]^\gamma.$$

In the SI system

$$[v] = c^{-1}, \quad [l] = m,$$

$$[F] = \frac{\kappa_2 \cdot m}{c^2}, \quad [\rho] = \frac{\kappa_2}{m}.$$

Then

$$c^{-1} = m^\alpha \left( \frac{\kappa_2 \cdot m}{c^2} \right)^\beta \left( \frac{\kappa_2}{m} \right)^\gamma.$$

Let's put together the same units on the right side:

$$c^{-1} = m^{\alpha+\beta-\gamma} \kappa_2^{\beta+\gamma} c^{-2\beta}.$$

This expression is valid if the equalities are satisfied

$$-2\beta = -1,$$

$$\beta + \gamma = 0,$$

$$\alpha + \beta - \gamma = 0.$$

From here

$$\alpha = -1, \quad \beta = \frac{1}{2} \quad \gamma = -\frac{1}{2}.$$

Then

$$v \sim l^{-1} F^{\frac{1}{2}} \rho^{-\frac{1}{2}}.$$

I. Sh. Slobodechkiy

*) See, for example, the brochure by B. Yu. Kogan “Dimension of a physical quantity”, M., “Nauka”, 1968.
