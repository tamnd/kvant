---
id: 1972-7-resheniya-845630e7
issue: kvant_1972_7
year: 1972
number: "7"
title: Solutions to problems M108—M109; F129—F130
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 37
page_last: 41
page_labels: 35-38
tag: 9DZX
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9fda2d9d26800b328409a1e5284b18ef7150a47f5793aeea833c1eef49e97c36
prompt_sha256: draft-1
translated_from: content/ru/1972/07/articles/11_resheniya-845630e7.md
source_content_sha256: 54fdd95864349f504ff8db9b2a7f6232248e6ef2a2176d35b79eaf44283edd2d
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 35⟧

SOLUTIONS
In this issue we publish solutions to problems M108–M109.

M108

a) Prove that the line dividing the given triangle into two polygons of equal area and equal perimeter passes through the center of the circle inscribed in the triangle.

b) Prove a similar statement for an arbitrary polygon in which to inscribe a circle.

Let's solve the problem right away. 6). Let a certain straight line intersect the contour of a polygon circumscribed about a circle with center O at points P and Q, which bisect the perimeter of the polygon. Then the segments OP and OQ split this polygon into two equal-sized polygons (to verify this, it is enough to connect the point O with all the vertices of the polygon and notice that the heights of all the resulting triangles with vertex O are equal to the radius of the circle). But if the line PQ also divides the area of ​​the polygon into two equal parts, then the point O must lie on the segment PQ (an “extra” triangle OPQ is formed (see Fig. 1)).

The same reasoning allows us to prove that a more general fact (for a triangle it is given in the book “Tasks and Theorems in Geometry” 3. A. Skopets and V.A. Zharova, Uchredgiz, 1962, problem 565): a straight line intersecting a circumscribed polygon divides its area and perimeter in the same ratios moeda and molko moeda when it passes through the center of the circle.

We love geometric inequalities and it seems to us to investigate the question: how many lines are there that divide the area and perimeter of the triangle from sides a, b and c? Answer and indication of data on page 60. The maximum number of such lines is three, and they, as proven, always intersect at one point.

As for an n-gon with n>3, there can even be an infinite number of such lines, and if the polygon is not described, then they may not pass through one point (for example, in an equilibrium trapezoid with bases a and b, you can choose the length of the side side so that there will be a straight line parallel to the bases, which bisects both the area and the perimeter; in addition, all straight lines passing through the midline and intersecting the bases of the trapezoid have this property).

⟦folio 36⟧

It can be proven, based on the "continuity" messages, that at least one line bisecting both area and perimeter exists for any convex polygon (and in general for any bounded convex figure). First of all, it is clear that if you move a straight line perpendicular to the fixed direction $Ox$, then there will come a moment (uniform) when it bisects the area, and a moment when it bisects the perimeter. Let $x_S$ and $x_P$ be the coordinates of the corresponding points on the $Ox$ axis. Now fix the point $O$ and rotate the axis $Ox$ around it by an angle $\varphi$ ($0 < \varphi \leq \pi$) (Fig. 2). For each angle $\varphi$, that is, for each axis $Ox$, we can similarly determine the numbers $x_S$ ($\varphi$) and $x_P$ ($\varphi$). It is clear that each of the functions $x_S$ and $x_P$ depends on $\varphi$ “continuously”, and at $\varphi = 0$ and $\varphi = \pi$ each of them takes values ​​that are equal in absolute value, but opposite in sign (after all, the axis $Ox$ faces in opposite directions). Therefore, for some intermediate value of $\varphi = \varphi_0$, the values ​​of $x_S$ and $x_P$ must equal the other (Fig. 3). This is the main property of “continuity” that we obtain.

How to formalize such proofs strictly is described in detail in the book by N. Stiniod and W. Chinn “First Concepts of Topology,” one of the best books in the popular “Modern Mathematics” series (World, 1967).

Fig. 2. Red lines divide the area in half, blue lines - perimeter.

Fig. 3. Two continuous curves - red and blue - must intersect.

M109

a) At the vertex $A_1$ of the regular 12-gon $A_1A_2A_3\ldots A_{12}$ there is a minus sign, and at the rest there are plots. It is allowed to simultaneously change the sign to the opposite one at any six consecutive vertices of the polygon. Prove that after several such operations it is impossible to achieve a minus sign at the vertex $A_2$ and flats at the other vertices.

b) Prove the same statement if it is allowed to simultaneously change signs not at six, but at four consecutive vertices of the polygon.

b) Prove the same statement if it is allowed to simultaneously change signs at three consecutive vertices of a polygon.

Let's start with problem b). Divide all 12 vertices into three groups of four vertices each: the first group - vertices with numbers 1, 4, 7, 10, the second - 2, 5, 8, 11, the third - 3, 6, 9, 12 (Fig. 4, the vertices of each group form a square). It is clear that no matter what three consecutive vertices of the 12-gon we choose, exactly one of the selected vertices will fall into each of our three groups. Thus, a change in sign at three consecutive vertices will cause the number of minuses (and flats) in each group to change by one.

Now he will prove that from the arrangement of $A$ signs on figure 4 it is impossible to move to the arrangement $B$. The location $A$ in both the second and third groups has zero minuses. After the first sign, no matter where it occurs, there will be one minus in the second and third groups; then, after the second sign in each of these two groups there will be 0 or 2 minuses, then 1 or 3 minuses, then 0.2 or 4 minuses, then again 1 or 3 minuses in each, etc. Thus, in these two groups there will be either an even number of minuses or an odd number at the same time. But the location $B$ in the second group has 1 minus, in the third - 0. Therefore, we certainly cannot obtain it from $A$.

⟦folio 37⟧

Problems a) and 6) can be solved similarly. Think about which groups of vertices are convenient to consider in these cases. We will not write down the solutions to these problems separately, but will immediately try to figure out a more general question.

Let the vertices of a regular $n$-gon be arranged with pluses and minuses, and the cut is to change the sign of the simultaneous at any $k$ vertices standing in a row ($n$ and $k$ are given natural numbers, $k < n$); Which arrangements of signs can be obtained from this and which cannot?

Fig. 4.

Let us first consider a special case that directly generalizes problems a)—c) $n$ is divisible by $k$.

Let $n = kn_1$. Divide all $n$ vertices into $k$ groups so that each group includes $n_1$ vertices of a regular $n_1$-gon. We put each arrangement of pluses and minuses in accordance with the set $y = (y_1, y_2, \dots, y')$, where

$$y_i = \begin{cases} 0, & \text{ если в } i-\text{й группе четное число минусов,} \\ 1, & \text{ если в } i-\text{й группе нечетное число минусов.} \end{cases}$$

It is clear that changing the signs in any $k$ successive vertices causes a change in the number of minuses in each group by one, that is, from the arrangement that corresponded to the set $y$, we obtain the arrangement that corresponded to the *industrial set $y$, obtained from $y$ by replacing all zeros with one and one with zeros: Let us isovize two arrangements $x, x'$ flats and minuses are equivalent ($x \sim x'$) if their sets $y, y'$ are either equal or opposite *). (For example, on figure 4, where $n=12$, $k=3$ the location of $B$ is equivalent to $A$, and $\Gamma \sim \delta$.

Let us prove that one of the arrangements can be translated into another if and only if they are equivalent. In one direction, this has already been essentially proven: from the arrangement $X$ with the set $y$, when changing signs, arrangements with the sets $y, y, y, y$, etc., will be successively obtained, that is, if from $X$ one can obtain $X'$, then $X \sim X'$. Let us prove the opposite: if $X \sim X'$, then from the initial arrangement of signs $X$ one can obtain the arrangement $X'$. It is clear that we can get the signs we want in vertices with numbers 1, 2,..., $(n-k+1)$ by sequentially changing (if necessary) the signs at vertices from 1st to $k$, then from 2nd to $(k+1)$,... from $(n-k+1)$ to $n$. Thus we can obtain an arrangement $X''$ which is firstly the same as $X'$ in all vertices except perhaps $(k-1)$ of vertices $(n-k+2)$ through $n=10$, and secondly equivalent to $X'$ ($X'' \sim X'$ because both are equivalent $X$). But then the locations of $X''$ and $X'$ must coincide completely. Indeed, since $y_{1'} = y_1'$ (the signs of all vertices of the 1st group of locations $X''$ and $X'$ coincide) and $X'' \sim X'$, then $y_{1'} = y_1'$ for all $i=2, 3, \dots, k$, therefore, in vertices with numbers from $(n-k+2)$ to $n$ at $X''$ should have the same signs as $X'$.

Our statement has been proven (for $n=kn_1$). From the proof it is clear that all sets of all sets. (On this concept, see the article by M. M. Glukhov “The relation of equivalence and division of a set” in «Kvant» No. 2, 1972).

⟦folio 38⟧

If you understand this proof, then constructing the transition from $A$ to $B$ and from $B$ to $Γ$ on figure will not be difficult for you.

Before exploring the general case, it is useful to read the article by V. N. Vaguten *), especially the lemma on page 33 and consider some examples, say $n=12$, $k=8$; $n=12$, $k=9$ or even simpler $n=3$, $k=2$; $n=4$, $k=3$. You will find the end of the solution on page 60, but first try to find it yourself.

Nan more complete and original solutions to problems M106—M109 added by G. Grichenko, V. Korenyako and M. Illartsionov from Voronezh, E. Turkevich from Chernovtsy, A. Chernyak from Minsk, N. Chernov from Krivoy Rog, A. Sherstyuk from Nikolaev, M. Preezer from Tomsk, L. Khakin from Leningrad.

N. B. Vasiliev.

In this issue we publish solutions to problems F129—F130.

F129

The body is located at point $A$ inside a stationary hollow sphere (Fig. 5). In what case will it most likely reach the bottom point $B$ of the sphere: if it slides along the surface of the sphere? if it slides along straight line $AB$? The friction in both cases is negligible, the initial velocity of the body is zero and the distance $AB$ is much less than the radius of the sphere.

The movement of the body along the surface of the sphere is similar to the movement of a mathematical matrix with a suspension length equal to the radius of the sphere $R$. Since $AB \ll R$, the deviation of the body from the equilibrium position (point $B$) is small. Therefore, for the pernode of matrix oscillations, we can use the formula $T = 2\pi \sqrt{\frac{R}{g}}$. The time of movement of the body from point $A$ to point $B$ is equal to a quarter of the pernod of oscillations, that is

$$t_1 = \frac{\pi}{2} \sqrt{\frac{R}{g}}.$$

The movement of a body along an inclined plane is uniform. The acceleration $a$ is imparted to it by the component of gravity parallel to the inclined plane. If the angle of the inclined plane to the horizon is $\alpha$, this component is equal to $mg \sin \alpha$. Since $AB = \frac{at^2}{2}$

($t_2$ is the time of movement of the body along an inclined plane) and $AB = 2R \sin \alpha$, then

$$t_2 = \sqrt{\frac{2AB}{a}} = \sqrt{\frac{4R \sin \alpha}{g \sin \alpha}} = 2 \sqrt{\frac{R}{g}}.$$

We got $t_2 > t_1$, that is, the body will reach the point faster if it moves along the surface of the sphere.

F130

Inside the smooth sphere is a small charged ball. What size charge should be placed at the bottom point of the sphere in order for the ball to be held at its top point? The diameter of the sphere is $d$, the charge of the ball is $q$, and its mass is $m$.

The charge $Q$, which must be placed at the lower point of the sphere, must be such that the electric force acting on the upper ball is not less than the force of gravity of the ball $mg$.

*) See «Kvant» No. 6, 1972.

⟦folio none⟧

That is $\frac{qQ}{d^2} \geq mg$. Hence $Q \geq \frac{mgd^2}{q}$.

However, we still need to check whether the ball's equilibrium is stable. The distance is a small deviation of the ball from the equilibrium position (Fig. 6).

The equilibrium of the ball is stable if the projection of the force $F$ of the electron interaction of the balls on the tangent to the sphere is greater than or equal to the projection of the gravitational force on the same tangent.

$$\frac{qQ}{d^2} \sin \alpha \geq mg \sin 2\alpha.$$

(The $N$ reaction force is perpendicular to the surface of the sphere.)

Since the angle $\alpha$ of the ball’s deviation from the equilibrium position is small, then $\sin \alpha \approx \alpha$, $\sin 2\alpha \approx 2\alpha$ and $l \approx d$. That's why

$$2mg \alpha \leq \frac{qQ}{d^2} \alpha.$$

Therefore, for stable equilibrium of the ball at the top point of the sphere, the ball $Q \geq \frac{2mgd^2}{q}$ must be placed at the bottom point of the sphere.

The editors received 150 letters with solutions to problems F123—F130. The most difficult was problem F123, the easiest was problem F124.

Correct solutions to the problems were sent by: A. Aizikovsky (Kremenchug) F124, F125, F126; A. Alexandrov (Glazov UASSR) F129; T. Amanbaev (Novo-Kazalinsk station, Kzyl-Orda region, Kazakh SSR) F125; P. Ainenkov (village of Totskoye, Orenburg region) F124, F125; S. Araslanova (village N.-Ivkino, Kirov region) F125, F129; D. Arkhipov (Ryazan) F127; E. Akhmedov (Baku) F128; A. Baevsky (Gomel) F123, F124, F125, F126, F129, F130; V. Belov (Vologda) F124, F125, F126, F128, F129; L. Bradisky (Frunze) F125, F126, F128, F129; I. Vacker (Minsk) F128, F129; V. Vorontsov (village Ivnya, Belgorod region) F129; S. Galakhvardze (Tbilis) F124, F125, F126, F127; A. Grigoryan (Baku) F129; V. Daringov (village of Kinshga Bur. Autonomous Soviet Socialist Republic) F125; A. Dovzhikov (Leningrad) F129; E. Dolev (Moscow) F124, F125, F126, F129, F130; V. Dolmatov (TASHKENT) F125, F126; A. Edrenkin (Gorky) F129; A. Elkov (Moscow), F128; V. Zaitsev (Ostrogozhsk, Voronezh region) F129; K. Zarembo (Kharkov) F128, F129; N. Zykov (Saratov) F128, F129; A. Istomin (Podolsk, Moscow region) F125, F126; Ya. Itin (Rechnitsa, Gomel region) F125, F127; A. Karimov (Ufa) F128, F129; M. Kaul (Frunze) F125; M. Kaunelson (Magnitogorsk) F124; L. Knizherman (Moscow) F128, F129, F130; V. Kokosuy (Gomel) F129; A. Kokhman (Moscow) F129; V. Korotkhikh (Novokuznetsk) F125; S. Komko (Voronezh) F129; G. Levin (Kuibyshev) F128; O. Limonov (Timoshevsk, Krasnodar region) F123; V. Loevizisky (Rtishevo, Saratov region) F128, F129; A. Luchevoy (Grozny) F127; Yu. Lurie (Grozny) F128, F129; S. Lyagushkin (Dnepropetrovsk) F128, F129, F130; A. Mamula (village of Dybintsy, Boguslavsky district, Kivev region) F128; V. Mikhnev (Pyatgirsk) F129; R. Mukhamedov (Staraya Kulyatka village) F127; A. Nabamov (Evpatoria) F128; S. Pomashev (Ulyanovsk) F129; M. Premer (Tomsk) F130; L. Rudtser (Kharkov) F125, F129; O. Sahakyan (Yerevan) F125, F126, F127; L. Saftsulin (village of B. Saby, Sabinsky district of the Tatar Autonomous Soviet Socialist Republic) F124; A. Sboev (Medvedok settlement, Nolinsky district, Kivev region) F124, F126; P. Sergeeev Grozny) F123, F124, F126, F128, F129, F130; I. Sidorov (Moscow) F125, F126; G. Simonenkov (Kunas) F126, F127; L. Smushkeevich (Magnitogorsk) F123, F124, F125; M. Temkin (Minsk) F129; V. Terentyev (Pavlovo, Gorky region) F126; O. Trunov (Jalal-Abad Kyrgyz SSR) F125, F127; F. Takhvatulin (TASHKENT) F129, F130; N. Fedin (Omsk) F124, F125, F128, F129; M. Flerov (Moscow) F125, F130; D. Fushman (Chernivtsi) F125, F126, F127; L. Tsiferblam (Livov) F123; S. Chernikov (Semipalatinsk) F125, F127; Yu. Shashkov (Shigry, Kursk region) F129; I. Yurchenko (Kyiv) F129.

I. Sh. Slovodechkiy
