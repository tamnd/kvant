---
id: 1985-11-vavilov-ob-odnoy-formule-hristiana-gyuygensa-55332f13
issue: kvant_1985_11
year: 1985
number: "11"
title: About one formula of Christiaan Huygens
authors:
  - Вавилов В. В.
rubric: osnovnye-stati
page_first: 11
page_last: 16
page_labels: 9-14
tag: OSL9
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9f8f2dad42dd83f1dede105e136aa1115e0d5fb09c828ffb93f8728a39387888
prompt_sha256: draft-1
translated_from: content/ru/1985/11/articles/05_vavilov-ob-odnoy-formule-hristiana-gyuygensa-55332f13.md
source_content_sha256: 4ee31ac9ebe77a18086fde0f2c7c2228b07663217edfb5ec943b99b42b12068b
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 9⟧

About one formula of Christian Huygen

Candidate of Physical and Mathematical Sciences
V. V. VAVILOV

The length of a circle of radius 1/2 can be defined as the limit of the sequence of perimeter lengths of regular polygons inscribed in a given circle with an unlimited increase in the number of its sides. Defined in this way, the number is denoted by the symbol l. Similarly, the number l can be defined as the limit of the perimeters of regular polygons circumscribed about this circle (Fig. 1). More precisely, if by $p_n$ we denote the perimeter of the inscribed, and by $q_n$ the perimeter of the described regular $n$-gon, then the inequalities take place
$$p_n < \pi < q_n, \quad n \geqslant 3.$$
As $n$ increases, both sequences $p_n$ and $q_n$ monotically approach the number l (Fig. 2); when moving from $n$ to $n+1$ we get less error in the approximations that the numbers $p_n$ and $q_n$ give for the number l.
In his meaning of the phrase “Measurement of a circle,” Archimedes (287-212 BC) gave the following approximation for the number l:
$$3\frac{10}{71} < \pi < 3\frac{10}{70},$$
that is
$$3,14084507 < \pi < 3,14285714.$$
Archimedes obtained this result by calculating the perimeter of a regular inscribed 96-gon.
The long history of the number l is associated with many names of famous mathematicians. However, from the followers

⟦folio 10⟧

It was this basic inequality that allowed Huygens to go further than Archimedes.

 Below we will prove the results of Archimedes and H. Huygen and consider some related issues.

Proof of the main inequality

We will divide the proof of inequality (1) into several steps. We will consider the left side of this inequality to be known and therefore we will prove only the validity of the second inequality.

1°. If in some segment of the circle ACB we scan an equilateral triangle ABC and at points A, B and C tangents to the circle are drawn as shown in figure 4, then

$$S_{ABC} < 2S_{KLM}.$$

(2) Effective, from the correspondences $|KL| > |LC|$ and $|LC| = |AL|$ it follows $|AK| < 2|KL|$. Since triangles KLM and KAB are similar, their areas are proportional to the squares of the corresponding sides, it is true that

$$S_{KAB} / S_{KLM} = |KA|^2 / |KL|^2 < 4,$$

whence $S_{KAB} < 4S_{KLM}$.

On the other hand, equilateral triangles KAB and ABC have a common base AB, and therefore their areas are related in the same way as their altitudes, or (by Thales's theorem) as the lengths of the corresponding sides. Hence,

$$\frac{S_{ABC}}{S_{KAB}} = \frac{|AL|}{|AK|},$$

and, since $|AL| < (1/2)|AK|$, we get $S_{ABC} < (1/2)S_{KAB}$.

From here and from the previous inequality for areas we obtain (2).

2°. If we denote by $S_{cerm}$ the area of ​​segment ACB (see Fig. 4), then

$$S_{cerm} \leq \frac{2}{3} S_{ABK}.$$

(3)

To prove this inequality, we will use the following message. Let us denote (see Fig. 5) by $S_0$ and $A_0$ the areas of triangles ABC and KLM, respectively. Let us now consider the arc AC, divide it in half by the point $C_1$ and construct triangles of areas $S_2$ and $A_2$ in exactly the same way. Point $C_3$—the midpoint of arc AC$^2$—generates in a similar way triangles of areas $S_3$ and $A_3$. Continuing this process, we obtain two sequences $\{S_n\}$ and $\{A_n\}$ of positive numbers - the areas of the corresponding triangles. According to what was proved in 1° - see (2), we have the following:

$$S_0 < 2A_0, \quad S_1 < 2A_1, \quad S_2 < 2A_2, \quad S_3 < 2A_3, \dots, \quad S_n < 2A_n.$$

It is clear that (Fig. 6)

$$S_0 + 2S_1 + 2^2S_2 + 2^3S_3 + \dots + 2^nS_n + \dots = S_{cerm}$$

⟦folio 11⟧

And
$$A_0 + 2A_1 + 2^2A_2 + 2^3A_3 + \dots + 2^nA_n + \dots = S_{ABK} - S_{\text{сегм}}.$$
From the given chain of inequalities and the last two correspondences it follows that *)
$$S_{\text{сегм}} \leq 2(S_{ABK} - S_{\text{сегм}}),$$
that is, statement (3).
3°. The following geometric lemma of X. Heugen is also of independent interest.
Lemma. On figure 7: O is the center of the circle, lines AE and CD are tangent to the circle, AB is an arbitrary section intersecting the line CD, l_AC is the length of the arc AC. Then the following inequality is valid:
$$l_{\text{AC}} \leq \frac{2}{3} |CD| + \frac{1}{3} |AF|.$$

By the property of tangents drawn from one point to a circle, |AE| = |EC|; Therefore, triangle ACE is equilateral and angles EAC and ECA are equal. It follows that triangle AED is also equilateral (since $CAD = 90^\circ$, $DAE = 90^\circ - EAC$, $ADE = 90^\circ - ECA$) and thus |AE| = |ED| = |CE|. From (3) it follows that $S_{\text{сегм}} \leq (2/3)S_{AEC}$, where $S_{\text{сегм}}$ is the area of ​​the circle segment, shaded

*) It is not difficult to prove that if the sequences $\{a_n\}$ and $\{b_n\}$ have a limit and $a_n < b_n$, $n=1, 2, \dots$, then $\lim_{n \to \infty} a_n \leq \lim_{n \to \infty} b_n$.

on figure 7. Adding the area $S_{AOC}$ of triangle OAC to both sides of this inequality, we get
$$S_{\text{сегт}} \leq \frac{2}{3} S_{AEC} + S_{OAC},$$
where $S_{\text{сегт}}$ is the area of ​​the OAC sector, from where
$$S_{\text{сегт}} \leq \frac{2}{3} S_{OAC} + \frac{1}{3} S_{OAC},$$
where $S_{OAC}$ is the area of ​​the quadrilateral OAEC. Because
$$S_{OAC} = 2 \cdot S_{OEC} = 2 \cdot \frac{1}{2} |OC| \cdot \frac{1}{2} |CD| =
\frac{1}{2} |OC| \cdot |DC|,
S_{OAC} = \frac{1}{2} |OC| \cdot |AF|,
S_{\text{сегт}} = \frac{1}{2} |OC| \cdot l_{AC},$$
the last inequality implies the desired correspondence (4).
4°. To complete the proof of inequality (1), we make the following construction (Fig. 8): let $AA_1$ be the side of a regularly inscribed $n$-gon, and $LL_1$ be the side of a regularly inscribed polygon with the same number of sides; draw a straight line AB and from point A drop the perpendicular AK to the tangent LL_1.

Since $AOC = 2ABC$ (one of the angles is central, and the second rests on the same arc), we see that AD is a bicector in triangle LAK, and by the bisector theorem we have $|AL| / |LD| = |AK| / |KD|$.

But $(AK) \perp (KL)$, therefore $|AK| < |AL|$ and from the previous proportion we get $|KD| < |LD|$. Since $|AF| = |KC|$, we get $|KD| = |CD|$

⟦folio 12⟧

| $n$ | $p_n$ | $q_n$ |
| :--- | :--- | :--- |
| 3 | 2,59807621 | 5,19615242 |
| 6 | 3,00000000 | 3,46410161 |
| 12 | 3,10582854 | 3,21539030 |
| 24 | 3,13262861 | 3,15965994 |
| 48 | 3,13935020 | 3,14608621 |
| 96 | 3,14103195 | 3,14271459 |
| 192 | 3,14145247 | 3,14187304 |
| 384 | 3,14155760 | 3,14166274 |
| 768 | 3,14158389 | 3,14161017 |
| 1536 | 3,14159046 | 3,14159703 |
| 3072 | 3,14159210 | 3,14159374 |

$-|AF|$. In addition, $|LD|=|CL|-$
$-|CD|$ and therefore
$|CD|-|AF|<|CL|-|CD|,$
$2|CD|<|AF|+|CL|,$
$2|CD|+|AF|<2|AF|+|CL|$.

Using now (4), we obtain
$$l_{AC} < \frac{2}{3} |AF| + \frac{1}{3} |CL|.$$
Similarly, we can write that
$$l_{A1C} < \frac{2}{3} |A1F| + \frac{1}{3} |CL1|$$
or finally
$$l_{AC} + l_{A1C} < \frac{2}{3} |AA1| + \frac{1}{3} |LL1|.$$

Multiplying the resulting inequality by $n$, we obtain inequality (1).

Further exploration of the underlying inequality

We have established that the number lies in the first third of the integral $p_n$, $q_n$ for all $n \geqslant 3$. In order to clarify the location of the number l in this new integral, consider the ratio of the lengths of the integrals $p_n$, $\pi$ for $p$, $q_n$ [. Calculations show *] (see tables 1, 2) that this is the ratio of the length, that is, the values ​​of the fractions
$$(q_n-\pi)/(\pi-p_n), n=3, 6, 12, 24,$$
are quite close to 2. Based on these calculations, we can assume with a high degree of confidence that in reality there is a correspondence

*) For those who want to check the calculation on a calculator, we present the approximation of equality: $\pi \approx 3,14159265$.

$$\lim_{n \to \infty} \frac{q_n-\pi}{\pi-p_n} = 2.$$ (5)

To prove the correspondence of (5), we note that (Fig. 9))

$$p_n=n \cdot \sin \frac{\pi}{n}, q_n=n \cdot \tg \frac{\pi}{n}, n \geqslant 3,$$
and therefore
$$\frac{q_n-\pi}{\pi-p_n} = \frac{1}{\cos \frac{\pi}{n}} \cdot \frac{n \sin \frac{\pi}{n}-\pi \cos \frac{\pi}{n}}{\pi-n \sin \frac{\pi}{n}}.$$
To analyze the resulting expression we will need inequalities *)
$$x-\frac{x^3}{6} < \sin x < x-\frac{x^3}{6} + \frac{x^5}{120}, x > 0.$$ (6)

To prove the left inequality in (6), we set
$$f(x)=\sin x-x+\frac{x^3}{6}.$$

Then we have
$$g_1(x)=f'(x)=\cos x-1+\frac{x^2}{2},$$
$$g_2(x)=g'_1(x)=-\sin x+x.$$

*) Inequality (6) significantly improves the well-known inequality sin $x<x$ for $x>0$; see on this matter: «Kvant», No. 5, 1979, p. 5.

⟦folio 13⟧

Since sin x < x for x > 0, we get $g_2(x) > 0$ for x > 0. Thus, the function $g_1(x)$ returns for x > 0. But $g_1(0) = 0$ and, therefore, $g_1(x) > 0$ for x > 0. The function $g_1(x)$ is arbitrary for the function $f(x)$, for which also $f(0) = 0$. But for x > 0 we have $g_1(x) > 0$, so the function $f(x)$ also returns and therefore takes only positive values, that is, $f(x) > 0$ for x > 0, as stated.

The rules for partial inequality (6), as well as inequalities (prove them yourself!) are established in a similar way.

$$1 - \frac{x^2}{2} < \cos x < 1 - \frac{x^2}{2} + \frac{x^4}{24}, \quad x > 0. \quad (7)$$

The following approximate formulas follow from inequalities (6) and (7):

$$\sin \frac{\pi}{n} \approx \frac{\pi}{n} - \frac{\pi^3}{6n^3},$$

$$\cos \frac{\pi}{n} \approx 1 - \frac{\pi^2}{2n^2}.$$

Hence,

$$\frac{q_n - \pi}{\pi - p_n} \approx 2 \cdot \left(1 - \frac{\pi^2}{2n^2}\right)^{-1},$$

which completes the proof of correspondence (5), since $\frac{\pi^2}{2n^2}$ tends to zero as $n \to \infty$.

Equality (5) allows us to draw the following qualitative conclusion: the number $\pi$, being for any $n \geqslant 3$ in the interval $]p_n, \frac{2}{3}p_n + \frac{1}{3}q_n[$, for all sufficiently large values ​​of $n$, is close to the right end of this interval than to the left.

Goygenas formula and its effectiveness

Archimedes used the approximate formula to calculate the number $\pi$

$$\pi \approx p_n, \quad n \geqslant 3.$$

In his work, Geugens, in particular, obtained another approximate formula

$$\pi \approx \frac{2}{3}p_n + \frac{1}{3}q_n, \quad n \geqslant 3,$$

that is, I took the right-hand side of inequality (1) as an approximation for the number $\pi$.

The greater efficiency of the Goigenas formula compared to the Archimedes formula can be detected by direct calculations on a microcalculator, comparing the results of such calculations summarized in tables 1, 2 and 3 (the exact digits of the number $\pi$ are highlighted in color on these tables). Note that calculations will also be carried out - a fascinating and difficult task.

It is possible to compare the effectiveness of the formulas of Archimedes and Geugenas by another method, without arbitrary specific calculations for $p_n$ and $q_n$. You can use so-called prior estimates for the accuracy of these formulas, that is, such inequalities that allow you to estimate the differences $\pi - p_n$ and $\frac{2}{3}p_n + \frac{1}{3}q_n - \pi$ for all $n \geqslant 3$ in advance, without calculating the perimeters. The value of such prior estimates also lies in the fact that they allow us to accurately estimate the number $n$ for which we need to find accuracy. Using inequalities (6) and (7) and arbitrary simple empirical calculations, it is not difficult to obtain (we leave this as an exercise to the reader!) the following empirical estimates:

$$\frac{5}{n^2} < \pi - p_n < \frac{6}{n^2}, \quad n \geqslant 3, \quad (8)$$

And

$$\frac{2}{3}p_n + \frac{1}{3}q_n - \pi < \frac{64}{n^4}, \quad n \geqslant 3. \quad (9)$$

Directly from these inequalities

⟦folio 14⟧

we notice that the “speed” with which the difference $\frac{2}{3} p_n + \frac{1}{3} q_n - \pi$ tends to zero is greater than the “speed” with which the difference $\pi - p_n$ tends to zero at $n \to \infty$.

To compare these “speeds,” we will find those values ​​of $n$ that will certainly provide us with an accuracy in calculating the number $\pi$, for example, equal to $10^{-2}$. Since $\pi - p_n < \frac{6}{n^2}$, to calculate using Archimedes’ formula with this accuracy it is enough to take $n$ such that $6/n^2 < 10^{-2}$, that is, $n \geq 25$. Using Goigenas’ formula, we just need to choose $n$ such that $64/n^4 < 10^{-2}$, that is, $n \geq 9$.

As can be seen from the analyzed example, as well as from inequalities (8) and (9), the Goigenas formula quickly leads to the specified accuracy.

Two tasks

We place here material that can be the beginning of a small mathematical study.

Problem 1. Let $AC$ be a chord, $|BB_1| = 2R$ the diameter of a circle. $O$ is the center of the circle, $(BB_1) \perp (AC)$, $B$ are the midpoints of the $AC$ arc, $E$ and $F$ are the midpoints of the $AB$ and $BC$ arcs, respectively (Fig. 10). Prove that

a) $|AB|^2 = |BD| \cdot |BB_1|$, $|BE|^2 = |BG| \times |BB_1|$;

b) $|BD| < 4 \cdot |BG|$;

c) $|AC| < 2 \cdot |EF|$;

d) $S_{ABC} < 4(S_{ABE} + S_{BFC})$;

e) $\pi R^2 > \frac{4}{3} S_{2n} - \frac{1}{3} S_n$;

where $S_n$ is the area of ​​a regular $n$-gon in a circle ($S_{2n}$ is the corresponding $2n$-gon);

g) $2\pi R > \frac{4}{3} p_{2n} - \frac{1}{3} p_n$,

where $p_n$ is the perimeter of a regular $n$-gon in a circle ($p_{2n}$ is the corresponding $2n$-gon);

task 2. Prove that all the lines below the previous one exist and find them:

a) $n^2(\pi - p_n)$;

b) $n^4\left(\frac{2}{3} p_n + \frac{1}{3} q_n - \pi\right)$;

b) $\lim_{n \to \infty} \frac{p_n^2 - p_{n-1}p_{n+1}}{2p_n - p_{n-1} - p_{n+1}}$;

r) $n^4\left(\pi - \frac{4}{3} p_{2n} + \frac{1}{3} p_n\right)$;

d) $\lim_{n \to \infty} \frac{\pi R^2 - S_n(n)}{S_q(n) - \pi R^2}$,

where $R$ is the radius of the circle; $S_p(n), S_q(n)$ are the areas of regular hanging and circumscribed polygons.

In conclusion, we note that the observation of H. Heugen that the number $n$, equal to the length of a circle of radius $1/2$, is twice as large to the perimeter of a regular $n$-gon suspended in this circle than to the perimeter of a regular $n$-gon circumscribed around this circle, was recently generalized to the case of arbitrary convex figures bounded by smooth (without kinks) curves. Namely, the following statements hold.

Let $L$ denote the length of a convex closed curve without kinks, $P_n$ the perimeter of a $n$-gon with a maximum perimeter suspended in a given curve, and $Q_n$ the perimeter described around a given curve with a minimum perimeter (they exist!). Then the correspondence of the statements is true

$$\lim_{n \to \infty} \frac{Q_n - L}{L - P_n} = 2.$$

The proof of this statement and many other interesting results related to it can be found in the book [4].

Literature

1. Rudno F. On the cadarature of the cruise (Archimedes, Heugens, Legendre, Lambert), Mathesis, 1911.
2. Veselovsky I. N. ChristIAN Geugens. - M.: Uchredgiz, 1959.
3. Kipman F. History of the number $\pi$, - M.: Nauka, 1971.
4. Toth L. F. Locations on a plane, on a sphere and in space, - M.: Fizmatgiz, 1958.
