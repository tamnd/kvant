---
id: 1973-8-resheniya-zadach-m174-m178-5f2eb56b
issue: kvant_1973_8
year: 1973
number: "8"
title: Solutions to problems M174—M178
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 64
page_last: 68
page_labels: 62-66
tag: UG4F
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9593a7c9b30b6b45a3c1e0b2924c073dfffd0a6003277aca23381cb5b602243e
prompt_sha256: draft-1
translated_from: content/ru/1973/08/articles/13_resheniya-zadach-m174-m178-5f2eb56b.md
source_content_sha256: 6f5d94e5c650aaef7ffd41b4a3cada658c15d63231a5b34f3eb80a1672e6fea9
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 62⟧

Problem solutions
M174—M178

M174. See article by N. F. Sharyzin on p. 42.

M175. a) Each side of a regular triangle is divided into m equal parts, and straight lines parallel to the sides are drawn through the division points, cutting the triangle into m² small triangles. Among the vertices of the resulting triangles, N vertices must be marked so that for each two marked vertices A and B the segment AB is not parallel to any of the sides. What is the most possible value of N (given m)?
Let us divide each edge of the triangle into m equal parts and draw planes parallel to the grams through the division points. Among the vertices of the resulting polyboundaries, we mark N vertices so that no two marked vertices lie on a line parallel to one of the boundaries. What is the most possible N?
b) Among the integer solutions of the equation

$$x_1 + x_2 + \dots + x_k = m,$$

satisfying the conditions m 0 ≤ x_i ≤ m (for all i=1,2,...,k), it is necessary to select N solutions so that in each two of the selected solutions no unknown x_i belongs to the same value. What is the most possible value of N? (Problems a) and b) are part of the case of problem b) corresponding to k=3 and k=4.)

First of all, let's check that problem a) is part of the case of problem b) with k=3 and k=4.

Reception for 1 is the distance between adjacent parallel lines cutting the triangle (Fig. 1). Each point of the triangle is associated with 3 numbers: x₁, x₂ and x₃, expressing (on the selected scale) the distance from this point to the side of the triangle (Fig. 2).

It is easy to show that the sum x₁ + x₂ + x₃ is the same for all points of the triangle. Indeed, let us denote by 2a the length of the side of the triangle; then ax₁, ax₂ and ax₃ are the areas of triangles OA₂A₃, OA₁A₃ and OA₁A₂ (Fig. 2); hence a (x₁ + x₂ + x₃) is the area ΔA₁A₂A₃, that is, x₁ + x₂ + x₃ does not depend on the choice of point O. On the chosen scale, x₁ + x₂ + x₃ = m (where m is the number of segments into which each side of the triangle is divided).

We matched each point of the triangle with 3 numbers: x₁, x₂ and x₃. In this case, the vertices of small triangles are associated with non-negative integer numbers (Fig. 3).

In problem a) it is required that for each two marked vertices A and B the segment AB is not parallel to any of the sides ΔA₁A₂A₃. In problem b), in no two of the chosen solutions, no unknown x_i should belong to the same value. Both requirements (the second for k=3) mean, of course, the same thing.

Thus, problem a) is indeed a special case of problem b) for k=3.

Similarly, it is verified that problem 6) is equivalent to problem b) for k=4.

So, it remains to solve problem b).

Let's reformulate it:

Suppose that in a rectangular table of k columns and n rows it is possible to arrange non-negative integers in such a way that the sum of the numbers in any row is equal to m and no number is repeated in any column. Let k and m be fixed. What is the most possible N that n can then take?

The new formulation is, of course, equivalent to the original one, but at the same time allows for a simpler and shorter presentation of the solution.

⟦folio 63⟧

Let us prove that $N \leqslant \left[ \frac{2m}{k} \right] + 1$, where $\left[ \frac{2m}{k} \right]$ means the integer part of the number $\frac{2m}{k}$ (the largest integer not exceeding $\frac{2m}{k}$).

The total numbers in the column are $N$, they are non-repeating and non-negative. This means that their sum is no less than

$$0 + 1 + \cdots + (N - 1) = \frac{N(N - 1)}{2}.$$

Columns in the table $k$. This means that the sum of the numbers in the entire table is no less than $\frac{kN(N - 1)}{2}$.

On the other hand, in each row the sum of the numbers is $m$, hence the sum of the numbers in the entire table is $Nm$.

Igak, $Nm \geqslant \frac{kN(N - 1)}{2}$. Therefore, $m \geqslant \frac{k(N - 1)}{2}$ and $\frac{2m}{k} \geqslant N - 1$. Since $(N - 1)$ is a required integer, then $\left[ \frac{2m}{k} \right] \geqslant N - 1$. Thus, $N \leqslant \left[ \frac{2m}{k} \right] + 1$.

Can we say that $N = \left[ \frac{2m}{k} \right] + 1$?

For $k = 1$ this is obviously not the case: $N = 1$, but $\left[ \frac{2m}{k} \right] + 1 = 2m + 1$. But it turns out that the case $k = 1$ is the only exception: for $k \geqslant 2$

$$N = \left[ \frac{2m}{k} \right] + 1.$$

To prove this, we construct, for any integers $k$ and $m$ ($k \geqslant 2, m \geqslant 0$), tables $k \times N$ that satisfy all the conditions of the problem.

Let first $k$ be an arbitrary number: $k = 2r, r \geqslant 1$. If $m = rl$, where $l$ is any non-negative integer, then $N = l + 1$ (see Table 1).

⟦folio 64⟧

If $m = rl + q$, where $0 \leq q < r$, then in the entire number of the last column of Table 1 you need to add $q$ (see Table 2); $N$ is equal to $l + 1$. Thus, for even $k$ the tables are built for any $m$.

When constructing a table for odd $k > l$, we highlight the case $k = 3$.

For $k = 3$, if $m = 3l$ or $m = 3l + 1$, then $N = 2l + 1$ (Tables 3 and 4), and if $m = 3l - 1$, then $N = 2l$ (Table 5).

Note also e. Fig. 3 corresponds to table. 3 at $k = 3$, $m = 6$.

Now let $k = 3 + 2r$ be an arbitrary odd number greater than three, and $m$ be any non-negative integer. Let us denote by $p$ the remainder of the division of $m$ by $k$ and by distance 2 the case: 1) $0 \leq p \leq r + 1$, 2) $r + 2 \leq p \leq 2r + 2$.

In the first case, $m = kl + q$, $0 \leq q = p \leq r + 1$, $N = 2l + 1$, and the corresponding table is formed by adding to the table. 3 such $2r$ columns, which are obtained if in the table. 2 replace $l$ with $2l$.

In the second case $m = k(l - 1) + r + 2 + q$, $0 \leq q \leq r$, $N = 2l$, and the corresponding table is formed by adding to the table. 5 such $2r$ columns, which are obtained if in the table. 2 replace $l$ with $2l - 1$.

M. L. Gerver

M176. To which side of the triangle $ABC$ is the point of intersection of its altitudes closest, if $A < B < C$? And to which peak?

Let us denote the heights by $AK$, $BM$, $CP$, and the point of their intersection by $O$.

The distances from $O$ to the side are $OK$, $OM$, $OP$.

Let's assume that $\Rightarrow C \neq 90^\circ$. Then $OK < OM < OP$.

Let's prove the left inequality (the right one is proven similarly). Indeed, $\frac{OM}{OC} = \frac{AP}{AC} = \cos \theta A$, $\frac{OK}{OC} = \frac{BP}{BC} = \cos \theta B$.

Since $\Rightarrow A < B$, then $\cos \theta A > \cos \theta B$, hence $OM > OK$, which is what was required. The distances from $O$ to the vertices are arranged in magnitude as follows: $OA > OB > OC$.

Let us prove the left inequality (the right one can be proved analogously).

$\frac{OA}{OP} = \frac{1}{\sin \theta OAP} = \frac{1}{\cos \theta B}$

$\frac{OB}{OP} = \frac{1}{\sin \theta OBP} = \frac{1}{\cos \theta A}$, from where $OA > OB$. The above solution is suitable for all triangles except rectangular ones.

In the case where $C = 90^\circ$, both proofs fail.

Find the answer for this case yourself (it is very important).

M177. Find all solutions to the equation

$\sqrt[n]{x^n - a^n} + \sqrt[n]{2a^n - x^n} = a$,

food $a$ is a given real number, $n$ is a natural number greater than one.

Let us first consider the special case $a = 0$. We get:

$\sqrt[n]{x^n} + \sqrt[n]{-x^n} = 0$.

If $n$ is even, then the only solution is $x = 0$ (since otherwise $x^n$ and $-x^n$ have different symbols and one of the roots is meaningless). If $n$ is odd, then any $x$ will be a solution.

Let now $a \neq 0$. Denoting $\sqrt[n]{x^n - a^n}$ by $y$, and $a - y$ by $z$, we obtain the system:

$$\begin{align*}
y + z &= a, \\
y^n + z^n &= a^n
\end{align*}$$

Let

$$\begin{align*}
y &= a, \\
z &= 0
\end{align*}$$

or $y = 0, z = a$.

In these cases, both equalities are satisfied. Let's see what it gives. Let's calculate $x$:

$$x^n = 2a^n$$ or $x^n = a^n$.

These equalities are satisfied when

$$x = \begin{cases}
a \sqrt[n]{2}, & \text{и } x = \begin{cases}
a, \text{если } n \text{-нечетное, } \pm a, \text{если } n \text{-четное, }
\end{cases}
\end{cases}$$

respectively. Substituting these values ​​of $x$ into the original equation, we obtain in general cases the same thing:

$$\sqrt[n]{a^n} = a$$.

This is true:

for all $a$, if $n$ is odd, for $a \geq 0$, if $n$ is even.

Let us now prove that for $a \neq 0, y \neq 0, z \neq 0$ system (1) cannot be satisfied. It is enough to consider only the case when $a > 0, y \geq z$. Indeed, if $y, z, a$ is its solution, and $a < 0$, then $-y, -z, -a$ is also its solution. Further, if we interchange the values ​​of $y, z$ in the solution, we will again obtain a solution. This means that if there is a solution for $a \neq 0$, then there is a solution for $a > 0$ such that $y \geq z$.

So let $a > 0, y \geq z$. Two cases apart.

⟦folio 65⟧

a) $z > 0$. Then
$$y^n + z^n = (y + z)^n,$$
(2)
whence $z^n = (y + z)^n - y^n = (y + z - y) \times [(y + z)^{n-1} + \dots + y^{n-1}]$. But $z^n < z(y + z)^{n-1}$, so equality (2) is impossible.

6) $z < 0$. Let's put $z = -w$.
When $n$ is even, system (1) takes the form
$$y - w = a,$$
$$y^n + w^n = a^n$$
or
$$a + w = y,$$
$$a^n + w^n = y^n$$
which similarly serve (a).
So here is the final answer.
If $n$ is odd, then for all $a \neq 0$
$x_1 = a\sqrt{2}, x_2 = a$; for $a = 0$ any $x$ is a solution.
If $n$ is even, then for $a > 0$ $x_{1,2} = \pm a\sqrt{2}, x_{3,4} = \pm a$, for $a = 0$ $x = 0$, and for $a < 0$ there is no solution.

Most of the errors in letters sent by readers are due to the fact that the indicated answer is not correct for all values ​​of the parameters $a$ and $n$, otherwise the answer is indicated correctly, but there is no proof that there are no other solutions.

A. L. Toom

M178. Let us drop from any point $P$ the bissertes of triangle ABC perpendicular $PA_1, PB_1, PC_1$ to its sides BC, CA and AB, respectively. Let $R$ be the intersection point of lines $PA_1$ and $B_1C_1$. Let us prove that the line $AR$ divides side BC in half.

Let us draw a straight line through the point $R$ parallel to side BC. Let it intersect sides $AC$ and $AB$ at points $B_2$ and $C_2$. We will prove that $R$ is the midpoint of the segment $B_2C_2$: in this and only in this case the line $AR$ bisects BC. Since $PR \perp B_2C_2$, to do this we need to prove that the triangle $B_2PC_2$ is equiangular. Let us prove the equality of angles $C_2B_2P$ and $B_2C_2P$. A circle can be described around the quadrilateral $RC_2C_1P$ (this follows from the fact that $C_2RP = C_2C_1P = 90^\circ$), which means $RC_2P = RC_1P$. But the quadrilateral $AC_1PB_1$ ($\Rightarrow AC_1P = \Rightarrow AB_1P = 90^\circ$) is also inscribed, hence $B_2C_2P = PC_1B_1 = PAB_1$). Similar reasoning for quadrilaterals $B_2B_1RP$ and $B_1AC_1P$ shows that $C_2B_2P = PAC_1$. But since $AP$ is a bissertier of $A$, we demand that the angles $C_2B_2P$ and $B_2C_2P$ are equal. Solution problem.

H. F. Sharyn

⟦folio 66⟧

2, 8; L. Ruditser (Kharkov) 0, 2, 3; S. Sanktkovsky (Minsk) 4, 8; M. Sapir (Sverdlovsk) 0, 2, 3; A. Sboev (Medvedok village, Kirov region) 4; S. Semenov (Voronezh) 0; R. Sirota (Kharkov) 0, 3, 8, 9a), 6), c); S. Sokov (village Sokovki, Slobodskoy) 8; V. Slenoy (Frunze) 8; V. Slenenko (Chelyabinsk) 0, 4, 5, 8, 9a), 6), c); A. Slesarenko (Rubtsovsk) 0, 3, 4, 8; A. Slinkin (Moscow) 0, 2, 8; V. Solodushkin (Stepnogorsk) 3; P. Sukhov (Saratov) 3; Yu. Smetsko (Chernivtsi) 0; S. Tabachnikov (Moscow) 0; A. Tatsev (Baku) 0; A. Tinkov (Simferopol) 2; I. Tonoyan (Yerevan) 2; E. Turkevin (Chernivtsi) 0, 2—4, 8; A. Tulane (Kirovograd) 7, 8; V. Uryshev (Magnitogorsk) 8; V. Fedorov (Moscow region) 8; V. Filin (Kaspiysk) 0; V. Khlebopros (Kyiv) 0; S. Tserkovny (Leningrad) 2; 4, 8; I. Tsukerman (Leningrad) 2; V. Circlevi (Balti) 2; N. Chamurltsev (Tbilis) 0; S. Cheremshantse (Leningrad) 9a), 6); N. Chernsov (Krivoy Rog) 8; V. Chernyakin (Poltava region) 8; E. Chesnokov (Moscow) 2; K. Schwarzan (Chisinau) 0; Yu. Shmelev (Yaroslavl) 0, 2, 4; I. Shuleev (Moscow) 8; V. Shuryshin (Gorky) 3; I. Sherbakov (Pervomaisk, Nikolaev region) 2; N. Sherbina (Dnepropetrovsk) 0, 2—5, 8; A. Shekhorsky (village Stariki, Zhytomyr region) 2, 4, 8.

Yu. P. Lysov

Almost all readers who sent solutions to problems F188—F192 successfully completed problems F188 and F190. The remaining problems were correctly solved by the following readers (the bold number after the last name is the last digit of the solved problem number): S. Akmertsev (Magnitogorsk) 1; M. Abdulkhakov (Angarsk) 2; O. Voinova (village Kosh-Tegirmen Kigg. SSR) 9-1; S. Garkusha (Tashkent) 9; V. Grabsky (Leninakan) 9; N. Golovko (Proskhladny) 2; A. Davydov (Magnitogorsk) 1; S. Davtyan (Oktembergan, Armenian SSR) 1; Yu. Dvinin (Zaporozhye) 2; N. Demchuk (Myttish, Moscow region) 1; V. Zhelezny (Leningrad) 9, 1; V. Nenamiev (Volgograd) 9, 1; V. Karpenko (Kyiv) 9; V. Karpinsky (Sverdlovsk) 9, 1; Y. Kodan (Glazov) 1; V. Kolosov (Kyiv) 2; S. Kornilov (Grozny) 9, 1; I. Kuchik (Yaroslavl) 9, 1; A. Liyakomin (Dnepropetrovsk) 9; Z. Mayzlin (Kyiv) 2; G. Mamedov (Baku) 1; N. Mironov (Vyka) 9, 1; A. Nikolaev (Moscow) 9, 2; V. Novienko (village Masalli, Azerbaijan SSR) 1; G. Ozannitsan (village of V. Artashat Arm. SSR) 9; V. Orlov (Moscow) 9; A. Papin (Gomel) 9, 2; V. Pankov (Minsk) 2; I. Pashin (Saratov) 9; Ya. Pevzer (Leningrad) 9, 2; V. Prosmokshin (Riga) 9, 1; A. Resce (Rostov-on-Don) 2; L. Ruditser (Kharkov) 9; Y. Saibelan (Kyiv) 2; A. Sboev (Medvedok village, Kirov region) 9; S. Svilolunov (Ufa) 1; Y. Simkin (Moscow) 9, 1, 2; Yu. Smolentsev (Essentuki) 9, 1; S. Surovce (Moscow) 9, 1; V. Tatarinov (Znoby-Novgorodskoe village, Sumy region) 2; O. Teryaev (Dnepropetrovsk) 1, 2;

V. Usachev (village of Arkhangelskoye, Arkhangelsk district) 2; N. Fedin (Omsk) 9, 2; A. Fridman (Moscow) 9; S. Khomenko (Podolsk) 9, 1; V. Tsirklev (Balti Moldova SSR) 9; V. Chernishov (Penza region) 1; V. Shendrik (Alma-Ata) 1; V. Shishchin (Izhevsk Udm. ASSR) 1; A. Shekhorsky (village of Stariki, Korostensky district) 9; S. Shukin (Dnepropetrovsk) 2; S. Yakushev (Ufa) 9.

S. G. Semenchinsky

Answer to the crossword puzzle placed in No. 7
Horizontally
3. Lava. 4. Piri. 6. Entropy. 8. Cameron. 13. Disruption. 15. Bar. 17. Snow. 19. Rainbow. 20. Error. 21. Number. 22. Clairo. 23. Continuum. 25. Diagnosis. 26. Topologist. 27. Sand. 31. Angstrom. 32. Pressure. 37. Dirac. 39. Warmth. 41. Pythagoras. 43. Antinomy. 45. Mode. 46. ​​Sketch. 47. Record. 48. Decay. 49. Prize. 50. Vin. 51. Diamond. 56. Avogadro. 57. Electrode. 58. Kant. 59. GIRD.
Povertkili
1. Quartz. 2. Number. 3. Lenitz. 5. Summary. 7. Forecast. 9. Route. 10. DISCLOSURES. 11. Mantissa. 12. Analogy. 13. Slin. 14. Ladoga. 16. Jump. 18. Hertz. 23. Constant. 24. Modulation. 27. Train. 28. Quark. 29. Jung. 30. Biyu. 33. Intuition. 34. Franklin. 35. Gyroscope. 36. Glider. 38. Radian. 40. Aneroid. 41. Nutrition. 42. Tepp. 44. Limbo. 52. Sound. 53. Fire. 54. Low tide. 55. Probe.
