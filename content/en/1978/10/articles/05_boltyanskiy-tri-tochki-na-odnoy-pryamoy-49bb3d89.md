---
id: 1978-10-boltyanskiy-tri-tochki-na-odnoy-pryamoy-49bb3d89
issue: kvant_1978_10
year: 1978
number: "10"
title: Three points on one line
authors:
  - Болтянский В. Г.
rubric: osnovnye-stati
page_first: 16
page_last: 21
page_labels: 14, 15, 16, 18, 19
tag: 9WHD
lang: en
source: kvant_digital
extraction: vision
content_sha256: 22ef4c8a3a41a6a73927e0a04c2363c526455b81f6f657af373224a411e03ef4
prompt_sha256: draft-1
translated_from: content/ru/1978/10/articles/05_boltyanskiy-tri-tochki-na-odnoy-pryamoy-49bb3d89.md
source_content_sha256: fd135da9482f19db1fea38c1339363d60507a75044a0b972c16e857d47adf74c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 14⟧

In this article we will look at several problems for which it is useful to use vectors. Basically, these are problems in which you need to prove that some three points lie on the same line, or from the fact that some three points lie on the same line, derive certain consequences. The main thing for solving such problems is a well-known theorem. Point C in both cases belongs to line AB when the vectors $\overrightarrow{AB}$ and $\overrightarrow{AC}$ are collinear (i.e., there is a number $k \in R$ such that $\overrightarrow{AC} = k\overrightarrow{AB}$).

Thus, to establish that three points A, B and C belong to one line, it is enough to make sure that there is a number $k$ for which $\overrightarrow{AC} = k\overrightarrow{AB}$. The number $k$ in correspondence with $\overrightarrow{AC} = k\overrightarrow{AB}$ has (at $A \neq B$) a simple geometric meaning: $|k| = \frac{|\overrightarrow{AC}|}{|\overrightarrow{AB}|}$, and $k > 0$ if point C belongs to ray AB, and $k < 0$ if it belongs to the opposite ray.

If, for example, C is the midpoint of the segment AB (Fig. 1), then $\overrightarrow{AC} = \frac{1}{2}\overrightarrow{AB}$; from here for any point Q

$$\overrightarrow{QC} = \frac{1}{2}\overrightarrow{QA} + \frac{1}{2}\overrightarrow{QB}.$$

If, further, $B$ is the midpoint of side MN of the triangle AMN, and $C$ is the center of gravity (the point of intersection of the medians) of this triangle, then the length of the segment AC is $\frac{2}{3}$ the length of the segment AB (Fig. 2): $\overrightarrow{AC} = \frac{2}{3}\overrightarrow{AB}$; since for any point Q the equality $\overrightarrow{QB} = \frac{1}{2}\overrightarrow{QM} + \frac{1}{2}\overrightarrow{QN}$ holds, we can conclude that

$$\overrightarrow{QC} = \frac{1}{3}\overrightarrow{QA} + \frac{1}{3}\overrightarrow{QM} + \frac{1}{3}\overrightarrow{QN}.$$

Finally, one more remark: if the vectors $\vec{a}$ and $\vec{b}$ are non-collinear, then from the correspondence

$$\vec{ka} + \vec{lb} = \vec{ma} + \vec{nb}$$

it follows that $k = m$ and $l = n$. Indeed, this equality can be rewritten in the form

$$(k - m)\vec{a} = (n - l)\vec{b};$$

if now $k \neq m$, then $\vec{a} = \frac{n - l}{k - m}\vec{b}$, which contradicts the non-collinearity of the vectors $\vec{a}$ and $\vec{b}$. Thus, $k = m$ and, similarly, $l = n$.

That's all the “theoretical” approximation. Now let's look at four examples.

Example 1. It is well known that the midpoints of the bases of a trapezoid and the intersection point of its diagonals are located on the same straight line. Let us now prove in some cases the “inverse” theorem: if the point A of the intersection of the diagonal

⟦folio 15⟧

Fig. 2.

nickname MNPQ and middle B, With its pro-
Since opposite sides MN and PQ lie on the same straight line, then MNPQ is a trapezoid or parallelogram (Fig. 3).

Proof. Let's put $\vec{a} = \vec{AM}$, $\vec{b} = \vec{AN}$. Then $\vec{AP} = k\vec{a}$ (since points A, M, P lie on the same line) and, in the same way, $\vec{AQ} = l\vec{b}$. Since B is the midpoint of the segment MN,

$$\vec{AB} = \frac{1}{2}\vec{AM} + \frac{1}{2}\vec{AN} = \frac{1}{2}\vec{a} + \frac{1}{2}\vec{b}.$$

Exactly the same

$$\vec{AC} = \frac{1}{2}\vec{AP} + \frac{1}{2}\vec{AQ} = \frac{k}{2}\vec{a} + \frac{l}{2}\vec{b}.$$

By condition, points A, B, C lie on the same line, and therefore there is a number m such that $\vec{AC} = m\vec{AB}$, that is

$$m\left(\frac{1}{2}\vec{a} + \frac{1}{2}\vec{b}\right) = \frac{k}{2}\vec{a} + \frac{l}{2}\vec{b}.$$

Due to the non-linearity of the vectors $\vec{a}$ and $\vec{b}$, it follows that $m = k = l$.

Finally, we have

$$\vec{MN} = \vec{b} - \vec{a}, \vec{PQ} = l\vec{b} - k\vec{a} = k(\vec{b} - \vec{a}),$$

that is, $\vec{PQ} = k\vec{MN}$. Therefore, $(PQ) \parallel (MN)$, that is, $MNPQ$, is a trapezoid or parallelogram.

Sweeping. On figure 3 points A, M, N, P, Q are located so that the numbers k and l are negative. However, the solution did not use nitle. Therefore, the above reasoning is applicable without any changes to the case when the numbers k and l are positive. This case was chosen in figure 4. Thus, we have “for free” received a proof of the following theorem: if the point A, at which the extensions of the sides NQ and MP of the trap MNQP intersect, and the midpoints B, C of the sides MN and PQ are located on the same straight line, then the pole MNQP is a trapezoid. We also invite the reader to see that the above arguments proceed (almost unchanged) in reverse order. This gives a vector proof of the corresponding “direct” theorems: in any trapezoid, the midpoints of the bases and the point of intersection of the diagonals lie on the same straight line; in any trapezoid, the midpoints of the bases and the intersection point of the extensions of the lateral sides lie on the same straight line (in other words, all four indicating points are located on the same straight line).

Example 2. On the ON side of the parallelogram AMNO and on its di-

⟦folio 16⟧

Fig. 4.

aeonals OM also take points B and C, which are $\overrightarrow{OB} = \frac{1}{n} \overrightarrow{ON}$ and $\overrightarrow{OC} = \frac{1}{n+1} \overrightarrow{OM}$ (Fig. 5). Prove that points A, B, C lie on the same line.

Solution. Let's put $\overrightarrow{AB} = \vec{a}$, $\overrightarrow{ON} = \vec{b}$. Then

$$\overrightarrow{AC} = \overrightarrow{AO} + \overrightarrow{OC} = \overrightarrow{AO} + \frac{1}{n+1} \overrightarrow{OM};$$

$$\overrightarrow{AO} = \overrightarrow{AB} - \overrightarrow{OB} = \vec{a} - \frac{1}{n} \vec{b};$$

$$\overrightarrow{OM} = \overrightarrow{ON} - \overrightarrow{AO} = \vec{b} - \left( \vec{a} - \frac{1}{n} \vec{b} \right) = \frac{n+1}{n} \vec{b} - \vec{a},$$

that is

$$\overrightarrow{AC} = \left( \vec{a} - \frac{1}{n} \vec{b} \right) + \frac{1}{n+1} \left( \frac{n+1}{n} \vec{b} - \vec{a} \right) = \frac{n}{n+1} \vec{a},$$

or $\overrightarrow{AC} = \frac{n}{n+1} \overrightarrow{AB}$. It follows from this that points A, B, C lie on the same line.

Notes. Nowhere in the solution was it used that the number $n$ is a natural number. The above reasoning shows that here $n$ can be any real number other than 0 and -1 (in the signifiers of fractions there are expressions $n$ and $n+1$).

figure 5 shows case $n = 4$ (point B cuts off a quarter of the side ON, and point C cuts off a fifth of the diagonal OM). If we put $n = -m-1$, then we will have $\frac{1}{n} = -\frac{1}{m+1}, \frac{1}{n+1} = -\frac{1}{m}$, i.e.

$$\overrightarrow{OB} = -\frac{1}{m+1} \overrightarrow{ON}, \overrightarrow{OC} = -\frac{1}{m} \overrightarrow{OM}.$$

figure 6 shows the case where $m = 3$ (on the continuation of the ON side, a quarter of the side is deviated from the point O, and on the continuation of the diagonal, the third quarter MNP). On lines MN, NP, PM take points A, B and C:

$$\overrightarrow{MA} = \alpha \overrightarrow{AN}, \overrightarrow{NB} = \beta \overrightarrow{BP},$$

$$\overrightarrow{PC} = \gamma \overrightarrow{CM}.$$

Prove that if $\alpha \beta \gamma = -1$, then points A, B, C lie on the same line (Menelaus’ theorem).

Proof. Let's put $\overrightarrow{AN} = \vec{a}, \overrightarrow{BP} = \vec{b}, \overrightarrow{CM} = \vec{c}$.

Then

$$\overrightarrow{MA} = \alpha \vec{a}, \overrightarrow{NB} = \beta \vec{b}, \overrightarrow{PC} = \gamma \vec{c}.$$

The vectors $\overrightarrow{AB}$ and $\overrightarrow{AC}$ are easy to express

⟦folio 18⟧

Fig. 8.

Since $\overrightarrow{AB} = \overrightarrow{AO} - \overrightarrow{BO}$ and $\overrightarrow{AB} = \overrightarrow{CB} - \overrightarrow{CA}$, we get
$$\overrightarrow{b} - \overrightarrow{a} = x(\beta \overrightarrow{b} - \overrightarrow{a}) - y(\alpha \overrightarrow{a} - \overrightarrow{b}),$$
that is
$$(x + \alpha y - 1)\overrightarrow{a} - (y + \beta x - 1)\overrightarrow{b} = 0.$$

Due to the non-collinearity of the vectors $\overrightarrow{a}$ and $\overrightarrow{b}$, the coefficients on the left side of the last equality must be equal to zero, that is
$$\begin{cases} x + \alpha y = 1, \\ \beta x + y = 1. \end{cases}$$

Solving this system of equations, we find the answer:
$$x = \frac{1 - \alpha}{1 - \alpha\beta}, \quad y = \frac{1 - \beta}{1 - \alpha\beta}.$$

Task and

1. The points $A, B, C, M$ and $N$, which do not lie on the same line, are located so that the rays $AM$ and $BN$ are parallel and oppositely directed; $|AC| = p, |BC| = q, |AB| = p + q$. For what correspondence between the lengths of the segments $AM$ and $BN$ are the points $M, N$ and $C$ located on the same line?

2. The lines $a$ and $b$ are parallel. On the line $a$ we take arbitrary points $A_1, A_2, A_3$, on the line $b$ we take arbitrary points $B_1, B_2, B_3$. On the segments $A_1B_1, A_2B_2, A_3B_3$ we also take points $C_1, C_2, C_3$, which are $|A_1C_1| = \alpha |A_1B_1|, |A_2C_2| = \alpha |A_2B_2|, |A_3C_3| = \alpha |A_3B_3|$. Prove that the points $C_1, C_2, C_3$ are located on the same line.

3. The points $M, N, P$ are symmetrical to the point $O$ relative to the side of the triangle $ABC$. Prove that the points $O$ and the centers of triangles $ABC$ and $MNP$ lie on the same line.

4. Points $A, B, C$ are the centers of triangles $OMN, ONP, OMP$. Prove that the centers of the triangles are $BCD, ACD, ABD, ABC$. Prove that the segments $AA_1, BB_1, CC_1, DD_1$ intersect at one point $M$, and the point $M$ cuts off the fourth segment from each of these segments. Follow the drawings for planar and spatial layers.

⟦folio 19⟧

10. Fig. 10.

11. Prove that if the point of intersection of the midlines of a quadrilateral ABCD belongs to diagonal AC, then diagonal BD bisects diagonal AC. Is the converse theorem true?

12. Given triangle MNP. Points A, B, C are also taken on the lines MN, NP, PM, which is $\overrightarrow{MA} = \alpha \overrightarrow{AN}, \overrightarrow{NB} = \beta \overrightarrow{BP}, \overrightarrow{PC} = \gamma \overrightarrow{CM}$. Prove that if $\alpha \beta \gamma = 1$, then the lines MB, NC and PA intersect at one point (Ceva's theorem).

13. The segments $A_1A_4$ and $D_1D_4$ (arbitrarily located in space) are divided into three congestive parts of each point $A_2$, $A_3$ and, respectively, $D_2$, $D_3$ (Fig. 10). Points $B_i$ and $C_i$ divide the segment $A_iD_i$ into three congested parts ($i = 1, 2, 3, 4$). Prove that points $B_1, B_2, B_3, B_4$ lie on the same line and points $C_1, C_2, C_3, C_4$ lie on the same line.

14. On the segments $A_1C_1$ and $A_2C_2$ (arbitrarily located in space), points $B_1$ and $B_2$ are taken such that $|A_1B_1| = \alpha |A_1C_1|$, $|A_2B_2| = \alpha |A_2C_2|$. On the segments $A_1A_2, B_1B_2, C_1C_2$ we take points $M, N, P$ (Fig. 11) such that $|A_1M| = \beta |A_1A_2|$, $|B_1N| = \beta |B_1B_2|$, $|C_1P| = \beta |C_1C_2|$. Prove that the points $M, N, P$ lie on the same line.

15. Two material points move uniformly (with non-zero velocities) along two straight lines $a$ and $b$. The straight line connecting the moving points always passes through the fixed point $O$. Prove that $a \parallel b$.

16. Two material points move in space rectilinearly and uniformly with speeds $v_1$ and $v_2$. The positions of the moving points at time $t$ are denoted by $A_t$ and $B_t$, and by $C_t$ we also denote the point of the segment $A_tB_t$, which is $|A_tC_t| : |A_tB_t| = \alpha (0 < \alpha < 1)$. Prove that point $C_t$ also moves uniformly and rectilinearly. At what speed?

17. An airplane carrying a bright point source of light moves uniformly and linearly over a flat surface with a speed of $v_1$, and a second airplane moves uniformly and linearly with a velocity of $v_2$. At some moments the plane, the second plane and the shadow of the second plane are located, respectively, at points $A, B, C$ (Fig. 12), and $|BC| = \alpha |AC| (0 < \alpha < 1)$. At what correspondence between the speeds of the planes does the shadow of the second plane also move uniformly and rectilinearly?

18. Three material points move in space uniformly and rectilinearly, each with its own speed. The positions of the moving points at time $t$ are denoted by $A_t, B_t, C_t$. Prove that the center of gravity of triangle $A_tB_tC_t$ also moves uniformly and rectilinearly.
