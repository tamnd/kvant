---
id: 1979-4-dubrovskiy-ploschad-poverhnosti-po-minkovskomu-09b81ac0
issue: kvant_1979_4
year: 1979
number: "4"
title: Surface area according to Minkowski
authors:
  - Дубровский В. Н.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 35
page_last: 38
page_labels: 33-36
tag: JNA8
lang: en
source: kvant_digital
extraction: vision
content_sha256: b5dc53a39222bc373e27dd01a9e57f6a5adefe8d8700ca1527e0ae75bda8c6b3
prompt_sha256: draft-1
translated_from: content/ru/1979/04/articles/13_dubrovskiy-ploschad-poverhnosti-po-minkovskomu-09b81ac0.md
source_content_sha256: 98f55a6e39e0e0e1b508ee05f4cecd4e995031ad8b6848f186d8c44c7a8ee803
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 33⟧

Surface area according to Minkowski

The length of a road is equal to its area divided by its width.
(From a lecture for schoolchildren)

In a previous note on surface area («Kvant», 1978, No. 5), we talked about how not to define it. We showed there that neither development nor approximation of polyhedral surfaces is suitable for this purpose.

This note will propose a correct method for determining surface area, invented by the outstanding German physicist and mathematician G. Minkowski (1864-1909). Its definition is general and simple. It allows you to easily calculate the area of ​​spaces. In “Geometry 10” this definition is used to find the area of ​​a sphere (§ 69) and the surface area of ​​a cylinder, cone and spherical segment (appendix to Chapter VI).

The idea of ​​Minkowski's definition is very clear. Let us imagine a layer of constant thickness “enveloping” the surfaces. It is intuitively clear that its volume $V(\delta)$ (2δ is the thickness of the layer) is approximately equal to $2\delta \cdot S$, where $S$ is the area of ​​the surface under consideration. Having calculated the values ​​of $V(\delta)/2\delta$, we will find an approximation of the value $S$, and the smaller the value $\delta$, the better the approximation will be.

Let's translate this idea into the language of mathematics. The mathematical equivalent of a “layer of constant thickness” is the concept of a neighborhood of a figure *). Let's define this in terms of nyatcha. Let $\Phi$ be an arbitrary figure in space, $\delta$ be a positive number. The set $\Phi_\delta$ of points $P$ of space distant from $\Phi$ by a distance not exceeding $\delta$, $\rho(P \Phi) \leq \delta$ is called the (closed *)) δ-neighborhood of the figure $\Phi$.

To make the definition clear, we need to define the concept of distance from a point to a figure. The distance $\rho(P, \Phi)$ from the point $P$ to the figure $\Phi$ also means the number $d$, which means that any ball with a center $P$ and a radius less than $d$ does not have common points with $\Phi$, but any ball with a center $P$ and a radius greater than $d$ does.

However, the δ-neighborhood of a figure can be defined without the concept of distance to $\Phi$. It turns out that this definition is equivalent to the following: the δ-neighborhood of a figure $\Phi$ is the set $\Phi_\delta$ of points $P$ of space such that every ball with center $P$ and radius greater than $d$ has common points with $\Phi$. Think it through.

If in the definition of the distance from a point to a figure we replace the words “space” and “ball” with “plane” and “circle”, then we get the definition of the δ-neighborhood of a figure on a plane. Where not otherwise stated, we will consider spatial neighborhoods.

Exercises
1. a) Find the plane and spatial δ-neighborhood of the segment. Prove that the area of ​​the first and the volume of the second are equal, respectively, $2\delta d + \pi\delta^2$ and $\pi\delta^2 d + \frac{4}{3}\pi\delta^3$, where $d$ is the length of the segment.
6) Solve the same problem for a circle of radius $R > \delta$ (in this case the answers are: $4\pi R$ and $2\pi^2 R\delta^2$).
2. Find the δ-neighborhood of a regular hexagon in space. Prove that $V(\delta)/2\delta$, where $V(\delta)$ is the volume, at $\delta \rightarrow 0$ tends to the area of ​​the hexagon.

Let us now give the basic definition for this note: the areal surface $\Pi$ is called the limit

$$S(\Pi) = \lim_{\delta \to 0} \frac{V(\Pi_\delta)}{2\delta},$$

*) Since we will consider only closed neighborhoods, the appended “closed” will be omitted in what follows.

⟦folio 34⟧

where $V(\Pi_\delta)$ is the volume of its δ-neighborhood.
A word of caution. Of course, limit (1) may not exist. It can be shown that for all “good” surfaces it exists (in the simplest cases we will calculate it). However, one should not think that from its existence for some figure $\Pi$ it follows that $\Pi$ is a surface in the generally accepted sense. In addition, for a Minkowski plane the equality $S(\Pi_1 \cup \Pi_2) = S(\Pi_1) + S(\Pi_2)$ (at $\Pi_1 \cap \Pi_2 = \emptyset$) is not always true; Accordingly, the example is considered in problem 4. However, with “good” surfaces such inconveniences do not follow.

Examples of calculating areas

It is, of course, possible to calculate the area of ​​surfaces and directly use the definition given above only in the simplest cases *).

We will find the areas of a sphere, a torus (the surface obtained by expressing a circle around a line that does not intersect it), the lateral surfaces of a cylinder and a cone. The halves of the axial sections of the δ-neighborhoods of these surfaces are shown in Figures 1, 2, 3a, 4a.

Exercises

3. Prove that the δ-neighborhood of the surface obtained by expressing a circle around a straight line that does not intersect it, the lateral surfaces of a cylinder and a cone. Halves of the axial sections of the δ-neighborhoods of this curve around the straight line l.

4. Prove that the bodies that arose during the expression of the yellow figures shown in Figures 1, 2, 3a, 4a are δ-neighborhoods corresponding to the surface.

1. Sphere. Obviously, the volume of the δ-neighborhood of a sphere $\Sigma = \Sigma(R)$ of radius $R$ is equal to the difference in the volumes of balls of radii $R + \delta$ and $R - \delta$ (Fig. 1):

$$V(\Sigma_\delta) = \frac{4}{3}\pi[(R + \delta)^3 - (R - \delta)^3] = 2\delta \cdot \frac{4}{3}\pi(3R^2 + \delta^2).$$

Dividing the last expression by 2δ and passing to the limit at $\delta \rightarrow 0$, we find that $S(\Sigma(R)) = 4\pi R^2$.

2. Thor. Let us consider the torus $T = T(R, r)$ obtained by expressing a circle of radius $r$ around a straight line located at a distance from its center using certain integral formulas.

*) In more complex cases, the surface area is found using certain integral formulas.

⟦folio 35⟧

standing $R > r$ (Fig. 2). It is clear that the body bounded by it is a $r$-neighborhood of a circle of radius $R$, the volume of which, according to the result of Exercise 16), is equal to $2\pi^2 R r^2$. Using this formula, it is easy to find the volume of the $\delta$-neighborhood of a torus (see Fig. 2)—it is equal to the radius $(r + \delta)$-neighborhood and $(r - \delta)$-neighborhood of a circle of radius $R$:

$$V(T_\delta) = 2\pi^2 R(r + \delta)^2 - 2\pi^2 R(r - \delta)^2 = 2\delta \cdot 4\pi^2 R r.$$

Therefore, $S(T(R, r)) = 4\pi^2 R r$.

From figure 3a and 4a it is clear that finding the volumes of $\delta$-neighborhoods of the lateral surfaces of a cylinder and especially a cone is not as simple as for a sphere and torus. Calculations of the essential will be simplified if these neighborhoods are slightly “corrected” (Fig. 36 and 46). We will carry out the calculations, use the “amendments”, and then prove their validity.

3. Ts i li et al. Let us denote by $C = C(R, H)$ the lateral surface of a cylinder of radius $R$ and height $H$. The volume of its “corrected” $\delta$-neighborhood $C'_\delta$ (Fig. 36) is equal to the difference in the volumes of cylinders of radii $R + \delta$ and $R - \delta$ with the same height $H$:

$$V(C'_\delta) = \pi H \left[ (R + \delta)^2 - (R - \delta)^2 \right] = 2\delta \cdot 2\pi R H,$$

because

$$S(C(R, H)) = \lim_{\delta \to 0} \frac{V(C'_\delta)}{2\delta} = 2\pi R H.$$

4. Cone. Let $R$ be the radius of the base of the cone, $\alpha$ the angle between its axis and the generatrix, and $K = K(R, \alpha)$ its lateral surface. Then the volume of the body $K'_\delta$ (Fig. 46) is equal to the difference between the volumes of the cone $R + \frac{\delta}{\cos \alpha}$ and $R - \frac{\delta}{\cos \alpha}$ and the same angles $\alpha$. It's easy to see that

$$V(K'_\delta) = \frac{1}{3} \pi \text{ctg} \alpha \left( R + \frac{\delta}{\cos \alpha} \right)^3 - \frac{1}{3} \pi \text{ctg} \alpha \left( R - \frac{\delta}{\cos \alpha} \right) = 2\delta \frac{\pi}{\sin \alpha} \left( R^2 + \frac{\delta^2}{3 \cos^2 \alpha} \right).$$

Therefore, $S(K(R, \alpha)) = \frac{\pi R^2}{\sin \alpha}$.

If together with the angle $\alpha$ the length $l$ of the generating cone is given, then, since $l = \frac{R}{\sin \alpha}$, for the plane the formula $S(K) = \pi R l$.

Let us now prove the validity of replacing the neighborhoods $C_\delta$ and $K_\delta$ with $C'_\delta$ and $K'_\delta$. It is clear that replacing the neighborhood $\Pi_\delta$ in formula (1) with some body $\Pi'_\delta$ does not affect the result if and only if the quantities $v(\delta) = \frac{V(\Pi_\delta) - V(\Pi'_\delta)}{2\delta}$ tend to zero at $\delta \to 0$. The differences in volumes $V(C'_\delta)$ and $V(C'_\delta)$, $V(K_\delta)$ and $V(K'_\delta)$ according to the model do not obviously exceed the volumes of bodies obtained by rotating the rectangles $Q_1$ and $Q_2$ in Figures 5a and 5b, respectively. Having found these volumes (note that for this we can use formula (2)), we find that in the case of a cylinder $|v(\delta)| \leq 4\pi R \delta$, and in the case of a cone $|v(\delta)| \leq \left( \frac{4\pi R}{\cos \alpha} + \frac{\pi \delta}{\sin \alpha} \right)\delta$. Therefore, in general cases $\lim_{\delta \to 0} v(\delta) = 0$.

Generalizations

Let for some set $\Phi$ there be an end and a positive limit $\lim_{\delta \to 0} \frac{V(\Phi_\delta)}{2\delta}$;

then, obviously, when replacing the denominator $2\delta$ by $c\delta^n$ this limit will vanish at $n < 1$ and to infinity at $n > 1$. In the definition of meaning, this property is specific to the surface. It is easy to understand that for bodies such a boundary value will already be $n = 0$, and for lines - $n = 2$.

In particular, in the latter case, the following definitions are accepted

⟦folio 36⟧

definition: the length of the line $L$ according to Minkowski (in space) is called the limit $\lim_{\delta \to 0} \frac{V(L_\delta)}{\pi \delta^2}$.

The intuitive justification for this definition is that the section of the neighborhood $L_\delta$, redistributing the lines $L$, is a circle of radius $\delta$ (area $\pi \delta^2$), so the volume $L_\delta$ must be equal to the product of $\pi \delta^2$ and the length of the line $L$. Using the result of control 1, check that Minkowski’s definition gives the required values ​​for the lengths of the segment and circle.

Less meaningful, but fully meaningful, is the consideration of the value $\lim_{\delta \to 0} \frac{V(\Phi_\delta)}{c \delta^n}$ for $n=0$ and $n=3$, where $c$ are properly chosen constants (see Problem 7).

Similar definitions can be given on the plane, where the most interesting case is $n=1$: the quantities $\lim_{\delta \to 0} \frac{S(L_\delta)}{2\delta}$, where $S(L_\delta)$ is the area of ​​the (flat) $\delta$-neighborhood of the curve $L$, are naturally taken as the length of the line $L$ (cf. epigraph).

Further generalizations concern $n$-dimensional spaces for $n>3$ and we, of course, will not dwell on them.

3 adachs and

1. Show that the $\delta$-neighborhood of the figure $\Phi$ is not always the union of all balls of radius $\delta$ with centers at points of this figure.

2. Give an example of two different figures $\Phi$ and $\Phi'$ such that $\Phi_\delta = \Phi_\delta'$: a) for some $\delta$; b) for all $\delta$.

3. Prove that the volume of the $\delta$-neighborhood of a convex $n$-gon is equal to $2\delta \cdot S + \pi \delta^2 \cdot P + \frac{4}{3} \pi \delta^3$, where $S$ is its area and $P$ is its semiperimeter.

4. Let $Q$ be a square lying in the plane $Oxy$, $Q_1$ the set of its points at which both coordinates $x$ and $y$ are located, $Q_2$ its remaining points. Prove that all these sets have Minkowski area, and $S(Q) = S(Q_1) = S(Q_2)$, so $S(Q_1 \cup Q_2) < S(Q_1) + S(Q_2)$, although the sets $Q_1$ and $Q_2$ do not intersect.

5. Find the surface area, we obtain by expressing other circles around the chord subtending it.

6. Find the surface area of ​​a body that is the intersection of two (sufficiently long) cylinders of radius $R$, the axes of which pass through a common point and are mutually perpendicular.

7. Select the constants $c_1$ and $c_2$ so that the limit a) $\lim_{\delta \to 0} \frac{V(\Phi_\delta)}{c_1}$ b) $\lim_{\delta \to 0} \frac{V(\Phi_\delta)}{c_2 \delta^3}$ have a meaningful geometric meaning. For which figure $\Phi$ are they positive?

List of readers who submitted correct solutions...

(For the beginning, see p. 32)

V. Berkum (Dnepropetrovsk) 18, 19; A. Boldyrev (Alma-Ata) 19; V. Bolotnikov (Kharkov) 10, 12, 14-17, 19, 22; G. Borisov (Komsomolsky settlement, Tomen region) 11, 12, 15, 17; A. Brodin (Kyiv) 11, 12; O. Bultsenin (Pavlodar) 18; M. Valeiko (Kyiv) 9, 10; O. Vasiliev (urmary settlement, Chuvash Autonomous Soviet Socialist Republic) 9; S. Vasiliev (Kalinin) 10; A. Velko (Sugar Plant village, Minsk region) 18; D. Voldko (Dolgoprudny) 18, 19, 22; F. Gabasov (p/o Nasibash Bashk ASSR) 18; M. Gavrilov (Chernogolovka village, Moscow region) 9-14, 16, 19; M. Goltsman (Dnepropetrovsk) 10, 11, 15, 20; I. Gopits (Novosibirsk) 9, 10, 14, 15; I. Gruzbere (Perm) 9, 13; E. Davidov (Poplevno village, Ryazan region) 13; I. Danilovsky (Gorky) 19; V. Jaloyan (Urtsadzor village, Armenian SSR) 15; V. Didukh (Lviv) 10; A. Dremin (Chernogolovka village, Moscow region) 11, 15, 18, 22; M. Ermolaev (Kostroma) 16; V. Zhilin (village of Khabary, Altai region) 15, 18; Yu. Zhuk (Moscow) 13, 15; V. Zhukov (Abaza) 19, 20, 22; K. Zhukov (Moscow) 13, 15; D. Zakharov (Moscow) 18; A. Zemskov (Ukhta) 18; E. Zudin (Alexandrov) 10, 11, 13-17, 22; E. Ivenko (Vinnitsa) 18; K. Ilyin (Vilnius) 18; S. Kalashnikov (Ryazan) 10; A. Kaplan (Sumgant) 18; V. Kelman (Moscow) 19; O. Kirilenko (Balashina) 22; A. Klyukov (Chelyabinsk) 13; V. Kovtunenko (Kyiv) 9, 10; E. Kozan (Dnepropetrovsk) 10, 15, 16; M. Kokov (village of Bateh KVASSR) 9; V. Komov (Alexandrov) 10, 11, 13, 14, 16-19, 22; A. Korobeinikov (Balashov) 10; A. Kosterov (Semiluki) 20; O. Kravets (Voronezh) 19; R. Kristul (Bobrisk) 16; E. Kuzmin (Cherenovets) 9, 18, 19; A. Kuprin (Moscow) 9-12, 18-20, 22; V. Kuryan (Rostov-on-Don) 11-13, 15, 17, 19, 20; V. Lashkin (Kyiv) 12, 15, 18, 22; A. Leonovich (Lida) 16; V. Linkov (Kaluga) 10; D. Lyudmirsky (Kyiv) 10, 17-19, 22; Yu. Makarov (p/o Chagoda, Vologda region) 18; S. Malamanov (Leningrad) 15, 18; I. Manitsev (Slutsk) 18; A. Matyukas (Couns) 15, 16, 19; L. Marukhlenko (Staraya Kupavna village, Moscow region) 12; S. Medvedev (Moscow) 10, 11; V. Mikulov (Pavlodar) 20; A. Motselner (Sverdlovsk) 20; A. Molotovichkov (Teykovo) 16; S. Murachtsev (Makhachka) 10;

(For the end see page 51)
