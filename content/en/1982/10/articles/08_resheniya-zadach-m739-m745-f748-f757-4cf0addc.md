---
id: 1982-10-resheniya-zadach-m739-m745-f748-f757-4cf0addc
issue: kvant_1982_10
year: 1982
number: "10"
title: Solutions to problems M739—M745; F748—F757
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 31
page_last: 44
page_labels: 29, 30, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42
tag: S02R
lang: en
source: kvant_digital
extraction: vision
content_sha256: cd51b596f2deafa604e76d6c88c16a3916967b4a2fda32a3d1d4fbaca2de919f
prompt_sha256: draft-1
translated_from: content/ru/1982/10/articles/08_resheniya-zadach-m739-m745-f748-f757-4cf0addc.md
source_content_sha256: 2f4dc73101d6bbfd7f97fa4a581b28148d2c9e055d27398e33b7c997a88c5e87
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 29⟧

Problem solutions

M739 — M745; F748 — F757

M739. Prove that for any value of $x$ for which the left-hand side makes sense, the equalities hold

$$\begin{align*}
tg x + tg \left( x + \frac{\pi}{3} \right) + \\
+ tg \left( x + \frac{2\pi}{3} \right) &: \begin{align*}
tg x \times \\
\times tg \left( x + \frac{\pi}{3} \right) \times \\
\times tg \left( x + \frac{2\pi}{3} \right) \end{align*}
= -3;
\end{align*}$$

$$\begin{align*}
tg x + tg \left( x + \frac{\pi}{n} \right) + \dots \\
\dots + tg \left( x + \frac{(n-1)\pi}{n} \right) &: \begin{align*}
tg x \cdot tg \left( x + \frac{\pi}{n} \right) \times \dots \\
\dots \times tg \left( x + \frac{(n-1)\pi}{n} \right) \end{align*}
= c_n
\end{align*}$$

food $n$ is an odd number, $n > 0$, $c_n$ is a constant (depending on $n$).
c) Find $c_n$ for every odd $n$.

a) Put $tg x = z$, $tg(\pi/3) = \sqrt{3} = t$, then $tg(2\pi/3) = -t$. Using the formula for the tangent of the sum, we obtain (at $zt \neq \pm 1$)

$$\begin{align*}
tg x + tg \left( x + \frac{\pi}{3} \right) + tg \left( x + \frac{2\pi}{3} \right) &= \frac{z + \frac{z+t}{1-zt} + \frac{z-t}{1+zt}}{z \cdot \frac{z+t}{1-zt} \cdot \frac{z-t}{1+zt}} = \\
&= \frac{z (1-z^2 t^2) + 2z + 2zt^2}{z (z^2-t^2)} = \frac{-3z^3 + 9z}{z^3 - 3z} = -3.
\end{align*}$$

6) Using the reduction formulas $tg(x+\pi) = -tg(\pi-x) = tg x$ and oddness $n$, it is easy to verify that both the numerator and denominator of the fraction

$$f(x) = \frac{tg x + tg \left( x + \frac{\pi}{n} \right) + \dots + tg \left( x + \frac{n-1}{n}\pi \right)}{tg x \cdot tg \left( x + \frac{\pi}{n} \right) \cdot \dots \cdot tg \left( x + \frac{n-1}{n}\pi \right)} = c_n$$

turn to 0 at the same points in the interval [0; $\pi$ [: 0, $\frac{\pi}{n}$, $\frac{2\pi}{n}$, ..., $\frac{n-1}{n}$ $\pi$ (and lose their meaning - “turn to infinity” - also at the same points $\frac{\pi}{2n}$, $\frac{3\pi}{2n}$, ..., $\frac{2n-1}{2n}$ $\pi$, which we further exclude from consideration). Let's put $tg x = z$, $tg \pi/k = t_k$ ($k=0, 1, \dots, n-1$). The numerator and denominator of the fraction $f(x)$ can be represented by replacing $tg(x+\pi/k/n)$ with $(z+t_k)/(1-zt_k)$ as ratios of polynomials from $z$:

$$z + \frac{z+t_1}{1-zt_1} + \dots + \frac{z+t_{n-1}}{1-zt_{n-1}} = \frac{S_1(z)}{R(z)},$$

$$z \cdot \frac{z+t_1}{1-zt_1} \cdot \dots \cdot \frac{z+t_{n-1}}{1-zt_{n-1}} = \frac{S_2(z)}{R(z)},$$

where $R(z) = (1-zt_1) \dots (1-zt_{n-1})$, and both polynomials $S_1(z)$ and $S_2(z)$ have degrees $n$ and the same roots $t_0=0$, $t_1$, $t_2$, ..., $t_{n-1}$. The fact that the fraction $f(x)$, that is, $S_1(z)/S_2(z)$, is a constant follows immediately from the following lemma:

Lemma. If a polynomial $az^n + bz^{n-1} + \dots + d = p(z)$ of degree $n$ has $n$ distinct roots $z_0$, $z_1$, ..., $z_{n-1}$, then it is only effectively equal to $a(z-z_0)(z-z_1) \dots (z-z_{n-1})$.

The proof of the lemma can be verified by induction on the degree $n$ of the polynomial $p(z)$. For $n=1$ it is obvious: $az+b=a(z-z_0)$, where $z_0=-b/a$. Let $p(z)$ be a polynomial of degree $n+1$ with leading coefficient $a$ and roots $z_0$, $z_1$, ..., $z_{n-1}$. Then $p(z)=p(z)-p(z_n)=az^n+bz^{n-1}+\dots+d-(az_n^n+bz^{n-1}+\dots+d)=a(z^n-z_n^n)+b(z^{n-1}-z_n^n)+\dots=(z-z_n)^q(z)$, where $q(z)$ is a neotorious polynomial of degree with leading coefficient $a$ and roots $z_0$, $z_1$, ..., $z_{n-1}$. By the induction hypothesis $p(z)=(z-z_0)\cdot a(z-z_0)(z-z_1)$. $\dots(z-z_{n-1})=a(z-z_0)(z-z_1)\dots(z-z_{n-1})$, that is, the statement of the lemma is also true for a polynomial of degree $n+1$. (The proof used the identity

$$z^k-a^k=(z-a)(z^{k-1}+z^{k-2}a+\dots+z a^{k-2}+a^{k-1}),$$

from which it is clear that $z^k-a^k$ is divisible by $z-a$.

c) Find the constant $c_n$ for any (odd) $n$ of significant difficulty. Answer: $c_n=(-1)^{\frac{n-1}{2}}n$, i.e. $c_3=-3$, $c_5=5$, $c_7=-7$, etc. All the solutions we have mentioned use messages related to the roots of polynomials.

⟦folio 30⟧

The constant $c_n$ can be obtained as the ratio of the leading coefficients of the polynomials $S_1(z)$ and $S_2(z)$. For the first, the leading coefficient is $t_1 t_2 \dots t_{n-1}$, for the second it is 1, therefore $c_n = t_1 t_2 \dots t_{n-1}$. It is not difficult to find the sign of the product $t_1 t_2 \dots t_{n-1}$: among the tangents $t_k = \text{tg} \pi k/n$ is equal to $(n-1)/2$ negative (and $t_{n-k} = -t_k$). A number of readers have noticed that the product $|t_1 t_2 \dots t_{n-1}|$ can be expressed as a ratio $Q'_n(0)/P_{n-1}(0)$, where $Q_n(x)$ and $P_{n-1}(x)$ are the Chebyshev polynomials defined by the conditions $Q_n(2 \cos \varphi) = 2 \cos n\varphi$, $P_{n-1}(2 \cos \varphi) = \frac{\sin n\varphi}{\sin \varphi}$ (see the article by N. Vasiliev and A. Zelevinsky in «Kvant», 1982, No. 4, p. 17*).

Let's give a similar, but more direct reasoning.

Note that $\text{tg} nx$ vanishes at the points 0, $\frac{\pi}{n}, \frac{2\pi}{n}, \dots, \frac{n-1}{n}$ and can be expressed as the ratio $s_n(z)/r_n(z)$ of two polynomials in $\text{tg} x = z$; by induction, based on the formula

$$\sum_{k=0}^{m} \text{tg}^2 \frac{k\pi}{2m+1} = \frac{m(2m-1)}{3};$$

$$\sum_{k=0}^{m-1} \text{tg} \frac{(4k+1)\pi}{4m} = m;$$

$$\sum_{k=0}^{2m-1} \text{tg} \left(x + \frac{k\pi}{2m}\right) = -\frac{2m}{\text{tg} 2mx};$$

$$\sum_{k=0}^{2m} \text{tg} \left(x + \frac{k\pi}{2m+1}\right) = (2m+1) \cdot \text{tg} (2m+1)x;$$

$$\sum_{k=0}^{2m} \text{tg} \left(x + \frac{k\pi}{2m+1}\right) = (-1)^m \cdot \text{tg} (2m+1)x;$$

$$\sum_{k=0}^{n-1} \sin \left(x + \frac{k\pi}{n}\right) = \frac{1}{2^{n-1}} \sin nx.$$

The constant $c_n$ can be obtained as the ratio of the leading coefficients of the polynomials $S_1(z)$ and $S_2(z)$. For the first, the leading coefficient is $t_1 t_2 \dots t_{n-1}$, for the second it is 1, therefore $c_n = t_1 t_2 \dots t_{n-1}$. It is not difficult to find the sign of the product $t_1 t_2 \dots t_{n-1}$: among the tangents $t_k = \text{tg} \pi k/n$ is equal to $(n-1)/2$ negative (and $t_{n-k} = -t_k$). A number of readers have noticed that the product $|t_1 t_2 \dots t_{n-1}|$ can be expressed as a ratio $Q'_n(0)/P_{n-1}(0)$, where $Q_n(x)$ and $P_{n-1}(x)$ are the Chebyshev polynomials defined by the conditions $Q_n(2 \cos \varphi) = 2 \cos n\varphi$, $P_{n-1}(2 \cos \varphi) = \frac{\sin n\varphi}{\sin \varphi}$ (see the article by N. Vasiliev and A. Zelevinsky in «Kvant», 1982, No. 4, p. 17*).

In this case, the polynomial $s_n(z)$ must have $n$ roots $t_0=0, t_1, \dots, t_{n-1}$ and therefore, by the lemma, is equal to

$$s_n = e_n z (z-t_1) \dots (z-t_{n-1}) = e_n z^n + \dots + e_n t_1 \dots t_{n-1} z.$$

Let's compare (1) and (2), we get that $t_1 t_2 \dots t_{n-1} = e_n n$.

Let's give another way to find $c_n$. Let us substitute the value $x = \pi/4n$ into the identity $f(x) = c_n$. Using the reduction formulas $\text{tg} \left(\frac{\pi}{2} - x\right) = \text{tg} \left(\frac{3\pi}{2} - x\right) = 1/\text{tg} x$, it is not difficult to show that the product of the tangents of the angles $\frac{\pi}{4n}, \frac{5\pi}{4n}, \dots, \frac{(4n-3)\pi}{4n}$, which is in the denominator, is equal to $(-1)^{\frac{n-1}{2}}$.

You can find the sum in the numerator based on the fact that for all these angles $\text{tg} nx = 1$, and use formula (1) (essentially, it is to find this sum after the problem M100 - see «Kvant», 1972, No. 12; a number of correspondences between trionometric functions of this kind and interesting consequences from them are analyzed in the book by A. M. Yaglom and I. M. Yaglom “Non-Zelematrine Problems in Elementary Presentation” (Moscow, GTTI, 1954), problems 130-145).

V. Alekseev, A. Egorov

**M740. Seryozha poured some millet into a cylindrical pan and asked his neighbor Aunt Lida: “How much water do you need to pour in order to get tasty porridge?” - “It’s very simple,” answer-**

a), 6). We will assume that the millet fills some part of the pan without voids, like a liquid.

Let the radius of a cylindrical pan be $R$, and let so much millet be poured in that it rises to a height of $H$

*) Moreover, $Q'_n(x) = nP_{n-1}(x) = |t_1 \dots t_{n-1}| \cdot P_{n-1}(x)$ with all $x$.

⟦folio 32⟧

M742. On a) a circle, b) a sphere of radius 1 there are n points. Prove that the sum of the squares of the pairwise distances between them is not greater than $n^2$.

M743. There are N cities in the country. a) There is direct communication between any two cities by plane or ship. Prove that by using only one type of transport, you can get from any city to any other (perhaps with transfers). b) There is direct communication between any two cities by plane, train or ship. Prove that you can choose at least N/2 cities and one of three modes of transport so that, using one of them, you can get from any chosen city to any other chosen city. c) Give an example proving that in statement b) it is impossible to replace the number N/2 with a greater generality.

Fig. 1.

a), b) Let $O$ be the center of a given circle (sphere), $X_1, X_2, \dots, X_n$ be the given points, $\vec{x}_i = \vec{O}X_i$ ($i=1, 2, \dots, n$), $s$ be the sum of the squares of pairwise distances between points. Then, since $|X_iX_j|^2 = (\vec{x}_j - \vec{x}_i)^2$,

$$2s = (\vec{x}_1 - \vec{x}_1)^2 + (\vec{x}_1 - \vec{x}_2)^2 + \dots + (\vec{x}_1 - \vec{x}_n)^2 +$$

$$+ (\vec{x}_2 - \vec{x}_1)^2 + (\vec{x}_2 - \vec{x}_2)^2 + \dots + (\vec{x}_2 - \vec{x}_n)^2 + \dots +$$

$$+ (\vec{x}_n - \vec{x}_1)^2 + (\vec{x}_n - \vec{x}_2)^2 + \dots + (\vec{x}_n - \vec{x}_n)^2 =$$

$$= 2n(\vec{x}_1^2 + \vec{x}_2^2 + \dots + \vec{x}_n^2) -$$

$$-2[(\vec{x}_1\vec{x}_1 + \vec{x}_1\vec{x}_2 + \dots + \vec{x}_1\vec{x}_n) + (\vec{x}_2\vec{x}_1 + \vec{x}_2\vec{x}_2 + \dots +$$

$$\dots + \vec{x}_2\vec{x}_n) + \dots + (\vec{x}_n\vec{x}_1 + \vec{x}_n\vec{x}_2 + \dots + \vec{x}_n\vec{x}_n)] =$$

$$= 2n(\vec{x}_1^2 + \vec{x}_2^2 + \dots + \vec{x}_n^2) - 2\vec{x} \cdot \vec{x},$$

where $\vec{x} = \vec{x}_1 + \vec{x}_2 + \dots + \vec{x}_n$. Therefore $s = n^2 - |\vec{x}|^2 \leq n^2$, and equality is achieved if and only if $\vec{x}_1 + \vec{x}_2 + \dots + \vec{x}_n = \vec{0}$.

The resulting formula for the sum of squares of pairwise distances between points $X_i$ is a very particular Lagrange formula for the so-called “moment of inertia” of a system of exact masses. More information about the moment of inertia, the Lagrange formula and their application in geometry can be read in the articles by M. Balk and N. Grigoriev “Mechanics helps geometry” («Kvant», 1973, No. 11) and Z. Skopets “The distance between the centers of two systems of points” («Kvant», 1975, No. 3).

V. Prasolov

♦

a) The statement can be easily proven by induction on $N$. For two cities it is obvious. Let us prove it for $N+1$ cities, assuming that it is true for $N$ cities.

Let $\Gamma$ be one of the $N+1$ cities, then the remaining $N$ cities are connected by one mode of transport, for example by water, by the induction hypothesis. If at least one of these $N$ cities has a direct connection with the city $\Gamma$, then everything is clear. Otherwise, these cities are connected by plane with the city $\Gamma$, and therefore with any other of them (with a transfer at $\Gamma$).

b) Let us reformulate the problem as follows:

Given $N$ points, each two of which are connected by red, black or black segments. We will say that some of these points form a red (blue or black) connection if they can be bypassed by looking only at the red (blue or black) segments. It is easy to prove that it is possible to choose a connective containing more points than $A$, and also that $C \cup D$ is a black connective. Since the number of points in the connectives $A = A_0 \cup C$ and $B = B_0 \cup C$ is not less than in the connective $C \cup D$, the set $A_0$ and $B_0$ are not empty. Thus, all data $N$ points are divided into two bundles $A_0 \cup B_0$ and $C \cup D$. However, of these must contain at least $N/2$ points, and this contradicts the fact that the number of points in the maximum connective $A$ is less than $N/2$.

The resulting contradiction proves 6).

⟦folio 33⟧

c) Let us construct an example of a set of $N=4k$ points with segments of three colors connecting them, in which the number of points in the maximum connection is exactly $N/2$. (For $N=4k+r$ with $r=1$, 2, 3, the construction is similar, but the maximum size of the connection will be equal to $[N/2]+1$, and it can be proven that in these cases a connection of this size can be found in the set.)

Let's divide all the points into 4 groups $A_0, B_0, C$ and $D$ with $k$ points in each. Let us connect by black segments all points of the set $A_0$ with all points $B_0$ and all points $C$ with all points $D$. Similarly, we connect the points of the set $A_0$ and $C$, $B_0$ and $D$ with red segments, $A_0$ and $D$, $B_0$ and $C$ with blue segments (at figure 2 the case $k=2$ is depicted). Within each of the four groups, segments can be drawn arbitrarily - any two points of any of the set $A_0, B_0, C$ and $D$ are already connected by broken lines of each of the three colors.

It is easy to see that with such a coloring of the segments, any two of the four groups form a connective with the maximum point number equal to $2k=N/2$.

L. Kurlyandchik

**M744***. A similar triangle $A_1B_1C_1$ is inscribed into triangle $ABC$ (the vertices $\hat{A}_1, \hat{B}_1, \hat{C}_1$ of portions equal in size to $\hat{A}, \hat{B}, \hat{C}$ lie on the segments BC, CA and AB, respectively). Let $A_0, B_0, C_0$ be the intersection points of lines $BB_1$ and $CC_1, AA_1$ and $CC_1, BB_1$ and $AA_1$. Prove that the six circles circumscribed about triangles $ABC_0, BCA_0, ACB_0, A_1B_1C_0, A_1C_1B_0, B_1C_1A_0$ intersect at one point.

**Fig. 1.**

**Fig. 2.**

The most natural solution to the problem is based on the fact that all 6 circles under consideration pass through the fixed point of the similarity transformation that transforms $\Delta ABC$ into a similar one $\Delta A_1B_1C_1$. It is important for us that there is only one such transformation. (Indeed, suppose there are two similarity transformations, $\Pi$ and $\Pi_1$, that take $\Delta ABC$ to $\Delta A_1B_1C_1$. Then the similarity transformation $F=\Pi^{-1}\circ \Pi$ leaves the points $A$, $B$ and $C$ in place (e.g. $F(A)=\Pi^{-1}(\Pi(A))=\Pi^{-1}(A_1)=A$). It follows that that $F$ is an intersection and, moreover, an identity transformation. Therefore, the transformation $\Pi^{-1}$ is the inverse of $\Pi$, that is, $\Pi=\Pi_1$.

Let us now divide the circles under consideration into three pairs: $ABC_0$ and $A_1B_1C_0, BCA_0$ and $B_1C_1A_0, CAB_0$ and $C_1A_1B_0$. Take any of these pairs, for example, circles $S$ and $S_1$, circumscribed about triangles $ABC_0$ and $A_1B_1C_0$. They have a common point $C_0$; let $O$ be their second common point (see Fig. 1; if they touch, put $O=C_0$). We will show that there is a similarity transformation that leaves the point $O$ in place, and only it, and a transformation of $\Delta ABC$ to $\Delta A_1B_1C_1$. Since the pairs of circles $S$ and $S_1$ can be replaced by either of the other two pairs, and the same similarity transformation should be obtained, all three pairs of circles must have a common point, which is what we need.

So, let for now $O \neq C_0$; Let us denote the centers of circles $S$ and $S_1$ by $Q$ and $Q_1$. Performing a sequential rotation $R_0^\circ$ around the point $O$ by an angle $\varphi=QOQ_1$ in accordance with the direction (counterclockwise in the figures) and preparing $H_0^\circ$ with the center $O$ and the coefficient $k=|OQ_1|:|OQ|$, we obtain a similarity transformation $\Pi=H_0^\circ \circ R_0^\circ$, transforming the point $Q$ into $Q_1$. In this case, point $O$ (and only it) remains in place, and circle $S$ turns into a circle with center $Q_1$, passing through point $O: \Pi(S)=S_1$. Let us prove that $\Pi$ is the transformation we need, that is, $\Pi(\Delta ABC)=\Delta A_1B_1C_1$.

Note that the points $A$ and $A_1$ are located on opposite sides of the line $OC_0$, and therefore lie on the “outer” two $OC_0$ circles $S$ and $S_1$ (Fig. 2). Consequently, the angle $OAC_0$ is equal in magnitude to the flow of the central angle $\theta QC_0$, that is, $\theta AA_1=\theta QQ_1$, and, similarly, $\theta A_1A=OQ_1Q$. Thus, $\Delta OAA_1 \sim \Delta OQQ_1$. On the other hand, $\Delta OQQ_1 \sim \Delta OAA'$, where $A'=\Pi(A)$, since by definition the transformations are $\Pi, AOA'=\varphi=QOQ_1$ and $|OA'|=k=|OQ_1|:|OQ|$. So, triangles $OAA_1$ and $OAA'$ are similar and have a common side $OA$, so the points $A_1$ and $A'$ are either the same or symmetrical with respect to $(OA)$, and since they lie on the circle $S_1, A_1=A'=\Pi(A)$.

⟦folio 34⟧

M745. a) Given a sequence of numbers ($d_n$) such that $|d_n| \leq 1$ ($n=1, 2, \dots$). Prove that it is possible to choose a sequence ($s_n$) from the numbers $+1$ and $-1$ such that for all $n$
$$|d_1s_1 + d_2s_2 + \dots + d_ns_n| \leq 1.$$
6) Given a sequence of three numbers ($a_n, b_n, c_n$) such that $|a_n| \leq 1, |b_n| \leq 1, |c_n| \leq 1$ and $a_n + b_n + c_n = 0$ ($n=1, 2, \dots$). Based on it, a new sequence of three ($x_n, y_n, z_n$) is constructed, in which $x_0 = y_0 = z_0 = 0$, and each triple ($x_n, y_n, z_n$) at $n \geq 1$ is obtained from the previous one ($x_{n-1}, y_{n-1}, z_{n-1}$) by adding to $x_{n-1}$ one of the numbers $a_n, b_n, c_n$ of our choice, to $y_{n-1}$ - another, to $z_{n-1}$ - a third. Is it always possible to ensure that all numbers $x_n, y_n, z_n$ are no greater than 1 in absolute value or at least limited by some content?
c) Find out similar questions for a sequence of four numbers.

Fig. 1.

A similar proof is given that $B_1 = \Pi(B)$. Finally, let $C' = \Pi(C)$. As above, from the similarity of triangles $A_1B_1C' = \Pi(\triangle ABC)$, $ABC$ and $A_1B_1C_1$ it follows that points $C_1$ and $C'$ either coincide or are symmetrical with respect to ($A_1B_1$). But the points $C$ and $O$ lie on the same side of $(AB)$, so their images $C'$ and $O$ must lie on the same side of $(A_1B_1)$, and therefore $\Pi(C) = C_1^*$).

If circles $S$ and $S_1$ touch, then, as is easy to see, as a transformation $\Pi$ we should take the one with center $O = C_0$. In this case, triangles $ABC$ and $A_1B_1C_1$ are being prepared, is it possible to sew when $A_1, B_1$ and $C_1$ are the midpoints of the side of the triangle $ABC$, and $A_0 = B_0 = C_0$ is the intersection point of its medians.

D. Izak, V. Dubrovsky

♦
a) Set $u_n = s_1d_1 + \dots + s_nd_n$. Numbers $s_1, s_2, \dots$ can be selected in turn as follows: $s_1$ - arbitrary; let $s_1, s_2, \dots, s_n$ already be chosen so that $|u_k| \leq 1$ for all $k = 1, \dots, n$, then $s_{n+1}$ is taken equal to $-1$ if the numbers $u_n$ and $d_{n+1}$ have the same signs, and $+1$ if they are different. The completely obvious message that we are using here will be useful in the future, so we formulate it in the form of a lemma:

Lemma. If two numbers have different signs and each modulo does not exceed $M$, then their sum modulo does not exceed $M$.

This lemma applies to the numbers $u_n$ and $s_{n+1}d_{n+1}$ (in this case $M = 1$).

6) We will call a triple of numbers normal if their sum is 0 and each does not exceed modulo 1. Let us prove that we can “add” triples ($a_n, b_n, c_n$) one by one, rearranging the numbers in them so that the triple ($x_n, y_n, z_n$) is normal for any $n$. To do this, it is enough to replace that if the triples $(x, y, z)$ and $(a, b, c)$ are normal, and $x \geq y \geq z$ and $a \leq b \leq c$, then the triple $(x+a, y+b, z+c)$ is also normal. In fact, since $ax \leq 0$ and $cz \leq 0$, for the sum of extreme numbers the inequalities $|a+x| \leq 1$ and $|c+z| \leq 1$ are satisfied by the lemma (for $M = 1$), and the average numbers modulo are not more than 1/2 (if $x \leq y \leq z$, then $x+2y \leq x+y+z=0$, therefore $y \leq -x/2 \leq 1/2$; similarly it is proved that $y \geq -1/2$ and that $|b| \leq 1/2$).

Problem 6) has a red geometric interpretation. Between triplets of numbers with a sum of 0 and points on the plane, a correspondence can be established using a “coordinate system” on the plane, consisting of three axes $Ox, Oy$ and $Oz$, making angles with each other of magnitude $120^\circ$; in this case, each point $P$ corresponds to the coordinates $x, y$ and $z$ of its projections onto these axes (see Fig. 1). Since the sum of the unit vectors $e_x, e_y$ and $e_z$ is 0, $x+y+z = OP \cdot e_x + OP \cdot e_y + OP \cdot e_z = OP \cdot (e_x + e_y + e_z = 0)$. Conditions $|x| \leq 1$, $|y| \leq 1$ and $|z| \leq 1$ define three stripes of width 2, perpendicular to the axes; their intersection is the hexagon shown in Fig. 1.

Now we can submit our solution. The permutation of two numbers in a triple, that is, two coordinates, corresponds to the symmetry of the hexagon relative to the axes $Ox, Oy, Oz$, and the two “oppositely ordered” triplets $(x, y, z), x \geq y \geq z$, and $(a, b, c), a \leq b \leq c$ are two vectors lying in opposite directions - red and blue - of the quadrilateral (see Fig. 1). Their sum always lies inside the hexagon, therefore, if we translate by symmetries

*) It would be possible to establish the coincidence of the points $A'$ and $A_1$, $C'$ and $C_1$, based on the clearly obvious message that the directions of traversal of the vertices of triangles $OAA'$ and $OAA_1$, as well as triangles $A_1B_1C_1$ and $A_1B_1C_1$, must be the same. However, if you also carry out a strict deconstruction, without reference to the drawing, and even just accurately determining the “direction of traversal” it is quite difficult.

⟦folio 35⟧

vector $(a_n, b_n, c_n)$ into a quadrilateral opposite to where the vector $(x_{n-1}, y_{n-1}, z_{n-1})$ lies, before adding them, we will always be able to stay inside the hexagon.

Let us also note that with a proper choice of the coordinate system $OXYZ$ in space, the same hexagon will be a section of the cube $\{|X| \leq 1, |Y| \leq 1, |Z| \leq 1\}$ by the plane $X+Y+Z=0$ (see Fig. 2). In this case, the coordinates of any point on the hexagon plane in the system $Oxyz$ and $OXYZ$ will coincide.

c) Here it is no longer possible to assert that all numbers will be modulo no more than 1, as the example of two quadrilaterals $(1; 1; -1; -1)$ and $(1/3; 1/3; 1/3; -1)$ shows: among their pairwise sums the number 4/3=1+1/3 inevitably appeared. However, during the operation of adding “rearranged” quadrilaterals, obtain numbers that do not exceed a certain constant; To prove this, it is convenient to replace the conditions that the numbers do not exceed modulo 1 with others that would be preserved under such an operation. Here is one such condition:

(*) all numbers four and pairwise differ from each other by no more than 2 (that is, the difference between the largest and the smallest is no more than 2). Let us prove that if two quadruples $x_1 \geq x_2 \geq x_3 \geq x_4$ and $a_1 \leq a_2 \leq a_3 \leq a_4$ satisfy this condition, then the quadruples $(x_1+a_1, x_2+a_2, x_3+a_3, x_4+a_4)$ also satisfy it. Let $1 \leq j < k \leq 4$. then the difference $(x_j+a_j) - (x_k+a_k) = (x_j-x_k) + (a_j-a_k)$ modulo does not exceed 2, since the numbers $x_j-x_k$ and $a_j-a_k$ have different signs and do not modulo 2 (lemma from part a) for $M=2$. So, we have proven that it is possible to add four numbers (each time, perhaps, rearranging them) so that the conditions (*) are preserved. It remains to note that in four numbers with a sum of 0 that satisfies this condition, the largest modulo number does not exceed 3/2; in fact, let, for example, $x_1>3/2$, then $x_k \geq \frac{3}{2} - \frac{1}{2} - \frac{1}{2} - \frac{1}{2} = 0$; it is similarly proven that the numbers $x_j$ cannot be less than - 3/2.

For $m$-numbers with $m \geq 5$ the situation is the same as for four: $m$-numbers obtained from a given sequence of sets of $m$ numbers, modulo no more than 1, suitable by permutation of numbers in sets and addition, will satisfy conditions (*); Moreover, if the sum of each set is 0, then all numbers modulo will not exceed 2-2/m.

figure 3 shows the geometric interpretation of problem c). Instead of three axes on the plane going from the center of a regular triangle to its vertices, you need to take 4 axes in space directed to the vertices of a regular tetrahedra from its center. Since the sum of the united vectors of these axes is equal to 0, each point in space is assigned four numbers with a zero sum, composed of the coordinates of the projections of this point on the $Ox_1, Ox_2, Ox_3, Ox_4$ axis. Condition $|x_i| \leq 1$ identifies in space a layer of thickness 2, enclosed between planes perpendicular to the axis $Ox_i$; the intersection of four such layers is an octahedron (Fig. 3, a). Condition (*) defines in space a “rhombohedron”—a 12-hedron, all of whose faces are rhombuses (Fig. 3, b)*.

Try to give a geometric interpretation of the solution to problem c).

N. Vasiliev

*) This polyhedron is replaced by the fact that its identical copies can be used to cover the entire space without gaps (see, for example, the book by G. Steinhaus “Mathematical Kaleidoscope” (Moscow, “Nauka”, 1981, p. 95). It is curious that the centers of the cells of such filling simultaneously serve as the centers of the balls that form the densest sieve packing, which was mentioned in the list for the solution problem M740.

⟦folio 36⟧

F748. A small cube (Fig. 1) slides along a helical iron with a rectangular profile, cut on the inner surface of an endlessly long hollow cylinder. The radius of the base of the cylinder is R, the shaft of the screw is h, and the sliding friction coefficient is μ. Find the steady speed of the cube. (The size of the cube and the depth of the iron are much less than R.)

Fig. 1.

To solve the problem, it is convenient to “unfold” the cylinder. The trajectory of the cube on the scan is straight, inclined at an angle α to the horizontal (Fig. 2).

The cube moves at a steady speed when the sum of the projections of the forces acting on the cube onto the direction of the inclined line is zero. Let's write down these conditions:

$$mg \sin \alpha - \mu mg \cos \alpha - \mu \frac{mv_{\perp}^2}{R} = 0.$$

Here $mg \sin \alpha$ is the projection of the gravity force, $\mu mg \cos \alpha$ is the projection of the friction force on the “bottom” of the iron, $\mu \frac{mv_{\perp}^2}{R}$ is the projection of the friction force on the side wall of the iron (this force is equal to μN, where N is the normal reaction force from the side wall, imparting to the cube the centripetal acceleration $\frac{v_{\perp}^2}{R} = \frac{v^2 \cos^2 \alpha}{R}$, that is, $N = \frac{mv^2 \cos^2 \alpha}{R}$). From expression (*), taking into account that sin α = $\frac{2\pi R}{\sqrt{4\pi^2 R^2 + h^2}}$ and cos α = $\frac{2\pi R}{\sqrt{4\pi^2 R^2 + h^2}}$, we find the steady speed of the cube:

$$v = \sqrt{Rg \sqrt{1 + \left(\frac{h}{2\pi R}\right)^2 \left(\frac{h}{2\pi R}\mu - 1\right)}}.$$

(From the resulting expression it is clear that the cube will move along the iron under the condition μ < $\frac{h}{2\pi R}$.)

R. Enfijan

F749. A massive disk is being repaired around a vertical axis with an angular velocity Ω. A disk of radius r of mass m is lowered onto it from above, the axis of which is directed vertically (Fig. 1). The distance between the axes of the disks is d (d > r). The friction coefficient between the surfaces of the disks is μ. Determine the steady angular velocity of the small disk. What moment of force must be applied to the axis of the large disk so that its healing speed remains unchanged? There is no friction in the axes.

Let's see how the small disk will move immediately after contact with the large one.

Let us select two identical small sections of a small disk, located on the same diameter symmetrically relative to the center of the disk. On figure 2 points A1 and A2 are the centers of mass of such sections. At the moment of contact of the disks (when the small disk is still finished), the velocities $\vec{v}_1$ and $\vec{v}_2$ of those points of the large disk that are in contact with points A1 and A2 of the small disk are directed as shown in figure 2 (|\vec{v}_1| = |\vec{v}_2| = Ω |OA_1| = Ω |OA_2|). It is clear that along the vectors $\vec{v}_1$ and $\vec{v}_2$ the friction forces $\vec{F}_1$ and $\vec{F}_2$ will be directed at the moment of contact, acting from the side of the large disk in the area A1 and A2 of the small disk (|\vec{F}_1| = |\vec{F}_2|). Since the forces $\vec{F}_1$ relative to the axis of the small disk (l1 at figure 2) are less than the force $\vec{F}_2$ (l2 at figure 2), the total moment of force $\vec{F}_1$ and $\vec{F}_2$ will twist the small disk in the direction of the large disk.

⟦folio 37⟧

Having examined similar pairs of sections of the small disk, we come to the conclusion that immediately after touching, the small disk begins to twist in the direction of rotation of the large disk.

Let at some instant of time the angular velocity of the small disk become equal to $\omega$. The speeds of sections $A_1$ and $A_2$ will be equal to the correspondence of $\vec{v}_1$ and $\vec{v}_2$ and $|\vec{v}_1| = |\vec{v}_2| = \omega r$, where $r = |O'A_1| = |O'A_2|$ (Fig. 3). Strong frictions $F_1'$ and $F_2'$ acting on these areas will be directed along vectors $(\vec{v}_1 - \vec{v}_1')$ (relative speed of the point of the large disk touching point $A_1$) and $(\vec{v}_2 - \vec{v}_2')$ (relative speed of the point of the large disk touching point $A_2$). It is clear that the moment of the pair of forces $F_1'$ and $F_2'$ will spin the small disk (that is, the angular velocity of the disk will change) if $|\vec{v}'| = |\vec{v}'| < \frac{B_1 B_2}{2} = \Omega r$ (see Fig. 3; for convenience of comparison, the vectors “related” to point $A_2$ are intersected at point $A_1$).

Thus, while $\omega < \Omega$, there is a non-zero moment of friction forces that spins the small disk. At $\omega = \Omega$, the relative velocities of sections $A_1$ and $A_2$ are directed perpendicular to the segment $OO'$ (along the segment $A_1 C$ at figure 3), and the moment of friction forces relative to the axis of the small disk is zero. Consequently, in the future the small disk will rotate at the set angular speed $\Omega$.

At $\omega = \Omega$, all friction forces acting on different identical sections of the small disk will be equal in abscylotic magnitude and directed in the same way - perpendicular to the segment $OO'$. According to Newton's III law, the resultant of all frictional forces acting on the larger disk will be applied to the point of the large disk touching the center $O'$ of the small disk and is equal to $\mu m g$. To compensate for the braking moment of this force, a moment of force must be applied to the axis of the large disk

$$M = \mu m g.$$

S. Krotov

F750*. When the direction to the element E changes, the current through it changes as shown in figure 1. How will the direction of E change over time if it is included in the circuit shown in figure 2 (the circuit parameters are indicated in figure)? What minimum resistance can a resistor be connected in parallel to element E so that the direction does not remain constant?

The editors apologize for the inaccurate figure given in the conditions of the problem in «Kvant» No. 4 of this year (Fig. 4 on p. 26).

Let's consider the behavior of the circuit from the moment it is turned on. At the moment of switching on, the current through the coil and element E is zero; in this case, the direction to the element is also zero, and the entire direction of the battery is applied to the coil. The current through the coil (and through the element) begins to increase. When it reaches the value $I_1 = 5$ mA, a jump in direction to the element occurs - with a fixed current of 5 mA (tok through the coil cannot change abruptly), the direction on it instantly increases to $U_1 = 0,8$ V (see Fig. 1). In this case, the direction to the coil changes sign ($U_1 > \varepsilon$) and, therefore, the current begins to decrease. Similarly, when the current decreases to a value of $I_2 = 0,5$ mA, there will be a jump in the direction to the element again - it will decrease to almost $U_2 \approx 0$, and everything starts all over again.

Let's calculate the approximate time $\tau_1$ for the current to rise from $I_0 = 0$ to $I_1 = 5$ mA and the time $\tau_2$ for the current to decrease from $I_1 = 5$ mA to $I_2 = 0,5$ mA. Since the direction to the element changes little when the current increases from 0 to $I_1$, we will assume that the average direction to the coil for time $\tau_1$ is equal to

$$U_{\kappa 1} \approx 0,2 - 0,1/2 = 0,15 \text{ B}.$$

Similarly, the average direction on the coil during time $\tau_2$ will be considered equal to

$$U_{\kappa 2} \approx \frac{0,8 + 0,6}{2} - 0,2 = 0,5 \text{ B}.$$

⟦folio 38⟧

As the current increases
$$LI' = U_{к1}, \quad I' = \frac{\Delta I}{\tau_1} = \frac{I_1 - I_0}{\tau_1} = \frac{I_1}{\tau_1}.$$
From here we find $\tau_1$:
$$\tau_1 = \frac{LI_1}{U_{к1}} = \frac{10 \cdot 10^{-3} \cdot 5 \cdot 10^{-3}}{15 \cdot 10^{-2}} \approx 0.33 \cdot 10^{-3} \text{ c}.$$
As the current decreases
$$LI' = U_{к2}, \quad |I'| = \frac{|I_2 - I_1|}{\tau_2},$$
where
$$\tau_2 = \frac{L(I_1 - I_2)}{U_{к2}} = \frac{10 \cdot 10^{-3} \cdot 4,5 \cdot 10^{-3}}{5 \cdot 10^{-1}} = 9 \cdot 10^{-5} \text{ c}.$$
The graph of the change in voltage on the element E over time is shown in figure 3.

Let's connect a resistor in parallel to the element. In order for the voltage on the element not to remain constant (that is, for oscillations to exist), it is necessary that the “total” current-voltage characteristic (element + resistor) contain at least a small section in which the voltage drops with increasing current (strictly speaking, at point $U = \mathcal{E}$). Having constructed the characteristic for the resistor ($I = U/R$) and the “total” characteristic (do this yourself), we will find the minimum resistance at which the voltage on the element does not remain constant: $R_{\min} \approx 100 \text{ Om}$.

(Note that the dependence $I(U)$, as on figure 1, has a widely used device - a tunnel diode. The circuit on figure 2 is the general circuit of a pulse generator based on a tunnel diode.)

3. Rafaylov

F751. A thin hoop of radius $R$ (Fig. 1) is placed on a very rough cylinder of radius $r$, located horizontally. Find the period of vibration of the hoop in the vertical plane.

Fig. 1.

Fig. 2.

Let the hoop be deviated from the equilibrium position so that the radius vector of the point $A$—the point at which in the equilibrium position the hoop touched the cylinder (Fig. 2)—makes a small angle $\varphi_0$ with the vertical. The energy possessed by the hoop at the moment of maximum deflection is equal to
$$E_0 = Mg(R - r)(1 - \cos \varphi_0)$$
where $M$ is the mass of the hoop. If you let go of the hoop, it begins to oscillate. In this case, at any moment of time, the total energy of the hoop will be equal to $E_0$.

If the angle of deviation of the radius vector $OA$ from the vertical is equal to $\varphi$, then the potential energy of the hoop is equal to $E_\pi = Mg(R - r)(1 - \cos \varphi)$, and its kinetic energy is equal to $E_\kappa = 2 \cdot \frac{M}{2} ((R - r)\varphi')^2$ (we taught that the kinetic energy of a hoop, the speed of the center of which is equal to $(R - r)\varphi'$, where $\varphi'$ is the rate of change of the angle $\varphi$, is the sum of the energy of movement of the center hoop and equal to it (since there is no slipping) rotation energy around the center). Thus, the total energy of the hoop is
$$E = E_\pi + E_\kappa = Mg(R - r)(1 - \cos \varphi) + M((R - r)\varphi')^2.$$
According to the law of conservation of energy $E = E_0$, that is
$$Mg(R - r)(1 - \cos \varphi) + M((R - r)\varphi')^2 = Mg(R - r)(1 - \cos \varphi_0).$$
Let us equate the derivatives of the left and right sides of this equality:
$$g(R - r)\sin \varphi \cdot \varphi' + 2(R - r)^2\varphi' \varphi'' = 0,$$
or, since angle $\varphi$ is small and sin $\varphi \approx \varphi$,
$$\varphi'' = -\frac{g}{2(R - r)}\varphi.$$

⟦folio 39⟧

This expression describes harmonic vibrations whose frequency is $\omega = \sqrt{g/2(R-r)}$.
Thus, the period of oscillation of the hoop is equal to

$$T = 2\pi \sqrt{\frac{2(R-r)}{g}}.$$

K. Serdeeev

F752. At a distance of $L_1 = 5$ m from a thin collecting line with a focal length of $F = 10$ cm there is a uniformly illuminated vertical plane $\Pi$. Between the lines and the plane at a distance of $L_2 = 1$ m from the line there is a vertical plane of the vibration cavity plane $l = 5$ cm, in which a hole with a diameter of $d = 1$ cm is made (the center of the hole is on the main optical axis of the line). What will the path look like on screen E, placing a line to the right of it in the focal plane? (The inside walls of the hole do not reflect light.)

An unusual “diaphragm” that is not closely adjacent to the lens significantly affects the image - it turns out to be an unevenly illuminated spot. The size of the bright area in the center of the spot is determined by two factors: the diameter of the completely unobstructed area of ​​the wall (plane $\Pi$) - it is equal to the diameter $d$ of the hole - and the fact that the screen is not located in the plane of the sharp image - this plane is located at a distance from the line

$$f = \frac{L_1F}{L_1-F} = \frac{500 \cdot 10}{500-10} \approx 10,2 \text{ см.}$$

Without taking into account the second factor (image - in the focal plane) spot size

$$d_1 = d \frac{F}{L_1} = 1 \cdot \frac{10}{500} = 0,02 \text{ см} = 0,2 \text{ мм.}$$

Due to the second factor, the image is “smeared”; the degree of “smearing” depends on the line diameter $D$. Technique for estimating $D = 2$ see then the image of a wall point on the screen in the focal plane together with the point will be a circle with a diameter

$$d_2 = D \frac{F'-F}{F'} = 2 \frac{10,2-10}{10} = 0,04 \text{ см} = 0,4 \text{ мм.}$$

Thus, the diameter of the bright spot in the center of the image will be approximately 0.6 mm.

If the line were of a large diameter, then the total size of the spot would be determined by the distance from the axis of the line to those points that are still visible through the diferm. It is clear that the inlet and outlet openings of the dihedder completely block the rays from a point on the wall located at distances greater than

$$r \approx (L_1-L_2) \frac{d}{l} = (500-100) \frac{1}{5} = 80 \text{ см.}$$

Then the spot would have a diameter

$$d_3 \approx 2r \frac{F}{L_1} = 2 \cdot 80 \cdot \frac{10}{500} = 3,2 \text{ см,}$$

and its illumination would decrease from a maximum in the central circle to zero towards the edges (the farther from the axis, the more the portion of the light flux is blocked by the diferm, and the angle of incidence of the rays increases).

In order for the above to be true, you need to have a lens with a diameter of $D' \approx 2r \cdot \frac{L_2}{L_1-L_2} = 40 \text{ см.}$. Since in reality the lens has a significant diameter, the size of the large spot is determined by the diameter of the line and the size of the entrance hole of the diaphragm. The lens receives rays from those points that lie inside a circle of radius $r_1 \approx \frac{L_1-L_2}{L_2} \left( \frac{D}{2} + \frac{d}{2} \right)$. For $D = 2$ cm $r_1 \approx 6$ cm, and the maximum diameter of the spot on the screen is

$$d_4 = 2r_1 \frac{F}{L_1} \approx 2 \cdot 6 \cdot \frac{10}{500} \approx 0,24 \text{ см} = 2,4 \text{ мм.}$$

A. Zilberman

F753. figure 1 shows the dependence of the power source voltage on the current

⟦folio 40⟧

erzik. Find the maximum power that can be obtained from the voltage. At what resistance is the voltage? Why might such a power source come across, and how can such dependence $U(I)$ be practically implemented?

Fig. 1.

Fig. 2

EMF and internal resistances, which “work” only in certain ranges of values ​​$U$ and $I$. From the graph we determine:

on section $I - \mathcal{E}_1 = U_1(0) = 6$ B,

$$r_1 = \frac{6 \text{ B}}{0,3 \text{ A}} = 20 \text{ Om};$$

on section $II - \mathcal{E}_{II} = U_{II}(0) = 3$ B,

$$r_{II} = \frac{3 \text{ B}}{0,6 \text{ A}} = 5 \text{ Om}.$$

The power released to the voltage with resistance $R$ is equal to

$$W_R = I^2 R = \frac{\mathcal{E}_2^2 R}{(R + r)^2}.$$

From the condition $W'_R = 0$ we find at what $R$ $W_R$ the maximum:

$$W'_R = \frac{\mathcal{E}_2^2}{(R + r)^2} - \frac{2 \mathcal{E}_2^2 R}{(R + r)^3} = 0,$$ or $1 - \frac{2R}{R + r} = 0,$

where we get $R = r$.

So, in sections $I$ and $II$ the maximum powers are allocated to voltages whose resistances are equal to the corresponding

$$R_1 = r_1 = 20 \text{ Om}, \quad R_{II} = r_{II} = 5 \text{ Om}.$$

Matching points in the chain must be equal

$$I_1 = \frac{\mathcal{E}_1}{R_1 + r_1} = 0,15 \text{ A}, \quad I_{II} = \frac{\mathcal{E}_{II}}{R_{II} + r_{II}} = 0,3 \text{ A}.$$

Both work points fall on the corresponding sections, and, therefore, on each of them the maximum power in voltage is actually provided.

Corresponding maximum powers are equal

$$W_1 = I_1^2 R_1 = 0,45 \text{ Вт}, \quad W_{II} = I_{II}^2 R_{II} = 0,45 \text{ Вт}.$$

At figure 2 there is a simple circuit that ensures the dependence $U(I)$ in the circuit is the same as at figure 1 (we consider the diode ideal). It is interesting to note that with significant changes in the value of the resistance voltage, the power to voltage remains almost unchanged. This can be very convenient for calorimetric wholesalers. Think for yourself what the curve of $U$ versus $I$ should be so that the voltage power does not depend on the value $R_H$.

A. Zilberman

F754. The ant runs from the anthill in a straight line so that its speed is inversely proportional to the distance to the center of the anthill. At the moment when the ant is at point $A$ at a distance of $l_1 = 1$ m from the center of the anthill, its speed is $v_1 = 2$ cm/s. How long will it take the ant to run from point $A$ to point $B$, which is located at a distance of $l_2 = 2$ m from the center of the anthill?

The ant's speed does not change linearly over time. Therefore, the average speed on different sections of the path is different, and we cannot use the known formulas for the average speed to solve.

Using the ant's path, we divide from point $A$ to point $B$ into small sections passing in equal time intervals $\Delta t$. Then $\Delta t = \frac{\Delta l}{v_{cp}(\Delta l)}$, where $v_{cp}(\Delta l)$ is the average speed on this segment $\Delta l$. This formula suggests an idea for solving the problem: naissum is a graph of the dependence of the quantity $\frac{1}{v_{cp}(\Delta l)}$ on $l$ on the path from point $A$ to point $B$. This graph is a straight line segment (see figure). The fruit protected at figure under this segment is numerically equal to the exclusive time. Let's calculate it:

$$S = \frac{1/v_1 + 1/v_2}{2} \left(l_2 - l_1\right) = \left(\frac{1}{2v_1} + \frac{1}{2v_1} \frac{l_2}{l_1}\right) \left(l_2 - l_1\right) = \frac{l_2^2 - l_1^2}{2v_1 l_1}$$

⟦folio 41⟧

(since $\frac{1}{v_2} = \frac{1}{v_1} \frac{l_2}{l_1}$).

Thus, the ant will run from point $A$ to point $B$ in time

$$T = \frac{4-1}{2 \cdot 2 \cdot 10^{-2} \cdot 1} = 75 \text{ с}.$$

S. Krotov

F755. The satellite is a light rigid sphere of radius $R = 1$ m and mass $M = 1$ kg, filled with air at a pressure of $p = 10^{-3}$ atm and temperature $T = 300$ K. However, over time, two clans open in the wall of the sphere, located from each other at a distance equal to the radius of the sphere. Clan areas $S_1 = 10^{-4} \text{ cm}^2$ and $S_2 = 2 \cdot 10^{-4} \text{ cm}^2$. Calculate the magnitude of the satellite’s deviation from the trajectory line during the time $\tau = 100$ s.

Before the clans open, the pressure inside the sphere is $p$. It is the result of the control of molecules from the wall, and each molecule imparted an impulse $2mv_\perp$ to the wall, where $v_\perp$ is the absolute value of the projection of the molecule’s velocity perpendicular to the wall. After the opening of the clan, each molecule carries only the implus $mv_\perp$ across the “surface” of the response. Consequently, forces $F_1 = \frac{p}{2} S_1$ and $F_2 = \frac{p}{2} S_2 = pS_1$, directed along the radii, will act on the sphere. Having projected these forces on the axes $OX$ and $OY$, we find the projections $F_x$ and $F_y$ equal to the acting force of these forces (see figure):

$$F_x = F_1 \cos 30^\circ + F_2 \cos 30^\circ = \frac{3}{2} pS_1 \cos 30^\circ,$$

$$F_y = -F_1 \sin 30^\circ + F_2 \sin 30^\circ = \frac{1}{2} pS_1 \sin 30^\circ.$$

Thus, the results of the projection force acting on the sphere are equal in absolute value

$$F = \sqrt{F_x^2 + F_y^2} = \sqrt{\frac{7}{4}} pS_1$$

and is directed at an angle $\alpha$ to the axis $OX$ such that

$$tg \alpha = \frac{F_y}{F_x} = \frac{tg 30^\circ}{3}.$$

The action of this force will lead to uniform acceleration of the sphere’s motion, which is easy to calculate if over the distance time $T$ the air mass inside the sphere and the pressure changes insignificantly. Let's estimate the change in mass.

The number of molecules moving per unit time through a unit area of ​​the surface of a sphere is equal in order of magnitude to $\frac{1}{6} nv$ (dimension - $m^{-2} c^{-1}$), where $n$ is the number of molecules per unit volume, $v$ is the average speed of the tellan motion of molecules. During time $T$ a mass will flow out through two branches with a total area $3S_1$

$$\Delta m \sim m \cdot \frac{1}{6} nv \cdot 3S_1 \tau = \frac{1}{2} qv S_1 \tau,$$

where $q \approx 10^{-3}$ kg/m$^3$, $v \approx 500$ m/s. Substituting the numerical data, we find $\Delta m \sim \frac{5}{2} \cdot 10^{-7}$ kg. The initial mass of air is $m_0 = \frac{4}{3} \pi R^3 q \approx 4 \cdot 10^{-3}$ kg. Thus, $\Delta m \ll m_0$.

Assuming the air mass and pressure to be constant, we find the projections of acceleration and displacement of the sphere on the $OX$ and $OY$ axes:

$$a_x = \frac{F_x}{M + m_0} \approx \frac{F_x}{M},$$

$$x = \frac{a_x \tau^2}{2} \approx \frac{F_x}{2M} \tau^2 = \frac{3}{4M} pS_1 \cos 30^\circ \tau^2 = \frac{3\sqrt{3}}{8} \cdot 10^{-2} \text{ m},$$

$$y = \frac{a_y \tau^2}{2} \approx \frac{F_y}{2M} \tau^2 = \frac{1}{4M} pS_1 \sin 30^\circ \tau^2 = \frac{1}{8} \cdot 10^{-2} \text{ m}.$$

A. Stasenko

⟦folio 42⟧

F756. A container of volume $V=2$ l contains $m=2$ g of hydrogen and some water. The pressure in the vessel is $p_1=17$ atm. The vessel is heated so that the pressure in it increases to $p_2=26$ atm. How much water evaporates? What are the initial and final temperatures?
Note. Use the table of the dependence of saturated water vapor pressure on temperature.

The easiest way to solve the problem is graphic.

The total pressure $p(T)$ in the vessel is the sum of the pressure of saturated water vapor $p_H(T)$ and the pressure of hydrogen $p_B(T)$. According to the Mendeleev-Clapeyron equation, $p_B(T) = \frac{m_B}{\mu_B V} RT = \frac{2 \cdot 10^{-3}}{2 \cdot 10^{-3} \cdot 2 \cdot 10^{-3}} \cdot 8,3 \cdot T = 4,15 \cdot 10^3 \cdot T$ Pa.

By calculating $p_B(T)$ given two values ​​of $T$ - for example:
$$T = 373 \text{ K} - p_B \approx 15,5 \cdot 10^5 \text{ Pa},$$
$$T = 453 \text{ K} - p_B \approx 18,8 \cdot 10^5 \text{ Pa},$$

— let's build a graph $p_B(T)$ (see figure). Having obtained the table specified in the conditions of the problem, we build a graph $p_H(T)$. “Adding” graphs $p_B(T)$ and $p_H(T)$, we build a graph of the pressure in the vessel as a function of temperature. From the resulting graph $p(T)$ (see figure) we find the initial and final temperatures in the vessel:
$$p_1 = 17 \cdot 10^5 \text{ Pa} - T_1 \approx 380 \text{ K},$$
$$p_2 = 26 \cdot 10^5 \text{ Pa} - T_2 \approx 440 \text{ K}.$$

Let's find the mass of evaporated water. Considering water vapor to be an ideal gas, we determine the initial $p_H1$ and final $p_H2$ pressure of water vapor in the vessel. To do this, we will use the resulting graphs. At $T_1=380$ K, the hydrogen pressure is $p_{B1} \approx 15,5 \cdot 10^5$ Pa and
$$p_{H1} = p_1 - p_{B1} \approx 1,5 \cdot 10^5 \text{ Pa}.$$
At $T_2=440$ K $p_{B2} \approx 18 \cdot 10^5$ Pa and
$$p_{H2} = p_2 - p_{B2} \approx 8 \cdot 10^5 \text{ Pa}.$$

Let us write the equations of state for water vapor at $p_{H1}$, $T_1$ and $p_{H2}$, $T_2$:
$$p_{H1} V = \frac{m_{n1}}{\mu_n} RT_1, \quad p_{H2} V = \frac{m_{n2}}{\mu_n} RT_2,$$

where $m_{n1}, m_{n2}$ are the initial and final masses of vapor in the vessel. From here we find the mass of evaporated water:
$$\Delta m_n = m_{n2} - m_{n1} = \frac{\mu_n V}{R} \left( \frac{p_{H2}}{T_2} - \frac{p_{H1}}{T_1} \right) =$$
$$= \frac{18 \cdot 10^{-3} \cdot 2 \cdot 10^{-3}}{8,3} \left( \frac{8}{440} - \frac{1,5}{380} \right) \cdot 10^5 \approx 6 \cdot 10^{-3} \text{ кг.}$$

A. Buedin

F757. To obtain uniformly sized water droplets, a capitary tube containing a large reservoir filled with water is used. Liquid flows out of the capitolar as the pornium slowly moves in the reservoir. On the outside, at the free end of the capitlar, a piezoelectric element is attached, connected to a sound generator and transmitting vibrations to a stream of water. When the oscillation amplitude reaches a greater amplitude, the jet breaks into completely identical drops. Find the radius of the drops if the diameter of the tube is $d = 0,2$ mm, the speed of the flowing liquid is $v = 2$ m/s, the frequency of sound vibrations is $v = 1000$ Hz.

When mechanical (sound) vibrations occur, the shape of the jet flowing out of the capitlar will be slightly corrugated, as shown in figure. It will be the same in the absence of a piezoelectric element - in this case, the surface of the jet is “perturbed” by the edge of the capitolar. Under the influence of ultrasound, vibrations of the end of the capitolar “disturb” the jet, of course, more strongly. Therefore, it will “equal” earlier than in the absence of a piezoelectric element. But in any case, the amplitude of the corrugation can be considered small compared to the radius of the jet. So in the calculations below we will approximately assume the shape of the jet to be cylindrical. The radius of the jet will be equal to the radius of the drops.

It is natural to assume that the volume of a drop is determined by the amount of liquid flowing out of the capitular during one period of sound vibrations:
$$\frac{\pi d^2}{4} v T = \frac{4}{3} \pi R^3.$$
Considering that $T=1/v$, we find:
$$R^3 = \frac{3}{16} \frac{v d^2}{v}, \quad R = \sqrt[3]{\frac{3}{16} \frac{v d^2}{v}}.$$
