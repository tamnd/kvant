---
id: 1979-12-resheniya-zadach-m540-m544-f553-f557-a40abb4c
issue: kvant_1979_12
year: 1979
number: "12"
title: Solutions to problems M540—M544; F553—F557
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 24
page_last: 31
page_labels: 22, 23, 24, 25, 26, 28, 29
tag: ZQSG
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3cedf26d860e0509bca8abdec628e02027a7f97f73f8d7dc225d1e21e6ee6ccb
prompt_sha256: draft-1
translated_from: content/ru/1979/12/articles/09_resheniya-zadach-m540-m544-f553-f557-a40abb4c.md
source_content_sha256: 28193709041240e5c0fd0b0c5e812d10fa7af9deb67df00d422f493fd0df1d80
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 22⟧

The distance from the Earth to the Moon is $L = 380 \cdot 10^3$ km.
The diameter of the pupil of the eye is taken equal to $d = 5$ mm.
Planck's constant $h = 6,6 \cdot 10^{-34}$ J s.
X1 International Physics Olympiad, 1979

F611. The acrobat, standing on the side surface of a cylinder lying on a very rough floor, moves his legs and moves at a constant speed to the right. Considering the coefficient of friction of the acrobat's boots on the surface of the cylinder equal to $\mu$, determine the limiting angle $\alpha$, which can be equal to the vertical radius of the cylinder drawn to the point at which the acrobat is located. What will be the amount of friction between the acrobat's boots and the cylinder?

F612. What amount of heat must be supplied to 0.1 kg of neon to heat it by $5^\circ\text{C}$, if during heating the pressure of neon is proportional to its volume?

Problem solutions

M540—M544; F553—F557

M540. The international society consists of representatives from six different countries. The list of members of the society consists of 1978 surnames, numbered 1, 2,..., 1978.

Prove that there is at least one member of the society whose number is equal to the sum of the numbers of two members from his country or matches the number of some member from his country.

Fig. 1.

Let's assume that the conclusion of the problem fails. Note that one of the countries is represented in the society by at least 330 members. Indeed, if each state delegation had no more than 329 members, then there would be no more than $329 \times 6 = 1974$ members in total in the society. We will use a similar argument (known as the Dirichlet reason) several more times, without specifically infringing on it. Let us arrange the numbers of scientists of this country in ascending order: $a_1, a_2, \dots, a_{330}$. By virtue of our assumption, scientists with numbers $a_2-a_1, a_3-a_1, \dots, a_{330}-a_1$ represent the remaining five countries. At least 66 averages represent one country; let these be scientists with numbers $b_1, b_2, \dots, b_{66}$. Then scientists numbered $b_2-b_1, \dots, b_{66}-b_1$ represent the remaining four countries. On average, at least 17 scientists represent one country; let their numbers be $c_1, c_2, \dots, c_{17}$. Then scientists with numbers $c_2-c_1, \dots, c_{17}-c_1$ live in the remaining three countries. From these, we will similarly find 5 scientists representing two countries, and then two representatives of one country, the difference in numbers of which cannot be the number of a scientist in either country. Contradiction!

Solution problem.

If we now pose the question of how many members should there be in a society from representatives of $k$ countries in order for the conclusion of the problem to be satisfied, then the above solution method gives the answer $n_k = [k!e] = k! \left( 2 + \frac{1}{2!} + \frac{1}{3!} + \dots + \frac{1}{k!} \right)$ (check this yourself).

However, this estimate can be improved already for $k=3$. As A. Khodulyev told us, for three countries, not 16=[3!e], but 14 representatives are enough. For thirteen representatives of three countries, the conclusion of the task is not fulfilled; a corresponding example is given in figure 1. And for four countries, 45 representatives are sufficient; for 44 representatives of four countries, an example can be given when the conclusion of the task is not fulfilled. SSI estimate for the number of society members from $k$ countries for which

⟦folio 23⟧

M541. In a group of N., each person has exactly three friends.
a) Prove that N is equal.
b) Can a group of people always be divided into N/2 pairs so that the people in each pair are friends?

Fig. 2.

M542. Given a right triangle $A_0A_1A_2$ with comets $|A_0A_2| = a$ and $|A_1A_2| = b$. Ant field along the endless brittle $A_2A_3A_4A_5\dots$, food $A_nA_{n+1}$ - the height of the triangle $A_{n-2}A_{n-1}A_n$.
a) Find the length of its path (from an infinite number of segments).
b) Construct a limit point L, to which the ant approaches. At what distances from the camets is it located?

a) Let's count the number of pairs of friends. Since everyone has three friends, that is, is included in 3 such pairs, then the total number of pairs is 3N/2. It follows that N is even.

If we represent people as points - vertices, and friends are connected by segments - edges, then the configuration that satisfies the conditions of the problem will be a homogeneous graph of column 3 (3 edges extend from each vertex). In the language of graphs, our solution can be written as follows: since each of the M edges of the graph has two ends and each of the N vertices serves as the end of three edges, $2M=3N$, whence $M=3N/2$.

6) Answer. Not always. The simplest example, which was given by almost all readers who correctly solved the problem, contains 16 vertices and, therefore, 24 edges (Fig. 2). If we choose the pair $OA_1$, then the quints containing $A_2$ and $A_3$ can no longer be divided into pairs. As tenth grader V. Guba from Vologda noted, examples also exist for all four $N \geq 16$.

In all countermeasures given by readers, the graph has an isthmus - an edge, after choosing which the graph splits into two pieces (in our example there are three isthmuses: $OA_1$, $OA_2$ and $OA_3$). This is no coincidence. It is possible to prove—we offer this as a task to the readers—that in a homogeneous graph of stem 3 without an isthmus, there always exists a graph containing all the vertices of the graph and having no common vertices. (See, for example, chapter 18 of the book by K. Berge “Graph Theory and Its Applications” (Moscow, IL, 1962).)

The matching task is a fairly advanced section of graph theory. Some of these problems were discussed in «Kvant» (1970, no. 4, p. 14; 1974, no. 11, p. 23).

Consider the similarity transformation Π that takes triangle $A_0A_1A_2$ to triangle $A_2A_3A_4$. Its similarity coefficient

$$k = \frac{|A_2A_3|}{|A_0A_1|} = \frac{ab}{a^2 + b^2}.$$

The transformation Π, very indo, maps the red broken line Γ of interest to us, complemented by two initial links $[A_0A_1]$ and $[A_1A_2]$, exactly on Γ, since Π $(A_n)=A_{n+2}$ for $n=0, 1, 2, \dots$ (Fig. 3). Since P reduces all distances by a factor of k, the length z of the broken line Γ is determined from the equation

$$k(|A_0A_1| + |A_1A_2| + z) = z,$$

where

$$z = \frac{k(\sqrt{a^2 + b^2} + b)}{1 - k} = \frac{(\sqrt{a^2 + b^2} + b)ab}{a^2 + b^2 - ab}.$$

(In this reasoning, the general way of finding the sum of an infinite geometric progression is hidden: $(\sqrt{a^2 + b^2} + b)(k + k^2 + k^3 + \dots) = z$.) Note that each triangle $A_nA_{n+1}A_{n+2}$ contains the next $(n=0, 1, \dots)$, and the intersection of all these triangles is the point L to which in the limit there is an ant arrow. Since Π $(\triangle A_nA_{n+1}A_{n+2}) = \triangle A_{n+2}A_{n+3}A_{n+4}$, we obtain Π $(L) = L$, that is, the point L is a fixed point of the transformation Π.

Transformation Π is a central similar rotation; it can be obtained as a composition rotated by 90°

⟦folio 24⟧

and cooks (with coefficient $k$) with center $L$. It follows that $A_0LA_2 = A_2LA_4 = 90^\circ$; Thus, the point $L$ can be constructed as the intersection of two semicircles with diameters $[A_0A_2]$ and $[A_2A_4]$, or even simpler - lowered from $A_2$ perpendicular $A_2L$ onto the segment $A_0A_4$. And to find the distances $x$ and $y$ from the point $L$ to the legs of length $a$ and $b$ of the triangle $A_0A_1A_2$, you can use either the fact that $L \in [A_0A_4]$ and $|LA_4| : |LA_0| = k^2$, or the fact that the perpendiculars omitted from $L$ into segments $A_0A_2$, $A_2A_4$, $A_4A_6$, obtain transformations $\Pi$ from each other, from which

$$\begin{cases} y = kx, \\ ka - x = ky \end{cases}$$

(at figure 3 the segment of length $x$ is blue, the segment of length $y = kx$ is green, the segment of length $ky$ is blue again). Thus,

$$x = \frac{ka}{k^2 + 1} = \frac{a^2b}{a^4 + 3a^2b^2 + b^4},$$

$$y = \frac{k^2a}{k^2 + 1} = \frac{a^3b^2}{a^4 + 3a^2b^2 + b^4}.$$

In a number of letters, these answers were received as sums of a geometric progression with a value of $k^2$ - the transformation coefficient $\Pi^2$ is being prepared.

**M543. Let**

$$\rho(x, y) = \frac{|x - y|}{\sqrt{1 + x^2}\sqrt{1 + y^2}}.$$

Prove that for any real numbers $a, b$, with the inequality

$$\rho(a, c) \leq \rho(a, b) + \rho(b, c).$$

**Fig. 4.**

The formula for the "distance" $\rho$ can be essentially projected by establishing a one-to-one correspondence $y = tg\alpha$ between the numbers $y \in \mathbb{R}$ and the numbers $\alpha \in \left[-\frac{\pi}{2}; \frac{\pi}{2}\right]$. If $y_1 = tg\alpha_1$, $y_2 = tg\alpha_2$, then replacing $tg\alpha$ with $\sin\alpha/\cos\alpha$, we get

$$\rho(y_1, y_2) = \frac{|tg\alpha_1 - tg\alpha_2|}{\sqrt{1 + tg^2\alpha_1}\sqrt{1 + tg^2\alpha_2}} = |\sin(\alpha_1 - \alpha_2)|.$$

Thus, we need the triangle inequality for the distance $\rho$ follows from the following inequality:

$$|\sin(\alpha_1 - \alpha_2)| \leq |\sin(\alpha_1 - \alpha_2)| + |\sin(\alpha_2 - \alpha_3)|;$$

(2) the following inequalities are valid (for all $\alpha_1, \alpha_2, \alpha_3$) beyond doubt: for any $\beta$ and $\gamma$

$$|\sin(\beta + \gamma)| = |\sin\beta\cos\gamma + \sin\gamma\cos\beta| \leq |\sin\beta\cos\gamma| + |\sin\gamma\cos\beta| \leq |\sin\beta| + |\sin\gamma|;$$

putting $\beta = \alpha_1 - \alpha_2$, $\gamma = \alpha_2 - \alpha_3$ here, we get (2).

These formulas and trionometric calculations, as many readers have noticed, can be clarified with the help of a geometric interpretation of our distance $\rho$. Let us draw on the plane a circle tangent to the coordinate line $Oy$ at point $O(y=0)$, with a diameter $|OP|=1$, and for each point $Y$ (with coordinate $y$) of our line we associate the intersection $F=F(y)$ of the segment $PY$ with this circle (Fig. 4). Let $F_1=F(y_1)$, $F_2=F(y_2)$. Then $\rho(y_1, y_2)$ is simply dilinah $|F_1F_2|=\sin\beta$.

(This is immediately clear from (1), since $F_1PF_2=|\alpha_1 - \alpha_2|=\beta$, but it is also easy to establish geometrically - to the right, then, that the area of ​​a triangle on Fig. 4 with base length $|y_1-y_2|$ and height length 1 is equal to half the product $\sqrt{1+y_1^2}\sqrt{1+y_2^2}\sin\beta$.) Now the “triangle inequality” is very indo.

The mapping $y \rightarrow F(y)$ of a straight line onto a circle and a similar mapping of a plane onto a sphere - “stereographic

⟦folio 25⟧

Physical projection is a very important tool for solving various geometric problems *).

Readers familiar with complex numbers will also appreciate this solution (which was indicated by the tenth classicist V. Guba from Vologda). After the transformation $y \rightarrow \frac{1}{y+i} = z (y)$, the distance $p$ turns into the usual distance between points on the complex plane: $\rho (y_1, y_2) = \left| \frac{1}{y_1+i} - \frac{1}{y_2+i} \right|$; then, that the geometric interpretation of this mapping essentially leads to the same figure 4.

N. Vasiliev

M544. What is the maximum number of vertices of which it is impossible to check a single diagonal (which lies entirely within the interior of the polygon) that a convex n-уzelbnik can have? Solve this problem for $n=4,5,6,7$ first.

Fig. 5.

Fig. 6.

Let us prove that the number of such vertices does not exceed $\left[ \frac{n}{2} \right]$.

This follows immediately from the following lemma:

Lemma. If $A$ and $B$ are adjacent vertices of a non-convex polygon $M$, then the diagonal can be checked from $A$ or $B$.

Proof. Let $B$ and $C$ be the vertices of the polygon $M$ adjacent to $A$.

Let us first assume that $BAC < 180^\circ$. If triangle $ABC$ (including its sides) has no other vertices of polygon $M$, then the required diagonal is $[BC]$. If in the triangle $ABC$ there are other vertices of the polygon $M$, then we choose their middle vertex $D$, located at the minimum distance from the line $l$, passing through the point $A$ parallel to $[BC]$. Then $[AD]$ is the required diagonal, since otherwise the segment $AD$ would be intersected by some side $EF$ of the polygon $M$ (Fig. 5), one of the ends of which would lie closer to the straight line $l$ than the point $D$, which would contradict the choice of the latter.

Let now $BAC > 180^\circ$. Let us show that in this case it is always possible to check the diagonal from the vertex $A$. To do this, we extend the side $BA$ of the polygon $M$ beyond the vertex $A$ until the first intersection with the sides of the polygon $M$ at some point $D$. If $D$ is a vertex of the polygon $M$, then $[AD]$ is the desired diagonal. Otherwise, $D$ lies on the $EF$ side of the polygon. Let vertex $E$ be located on opposite sides of line $BA$ with vertex $C$ (Fig. 6). We will move the variable point $P$ on the side $EF$ from point $D$ to point $E$. Then the variable segment $AP$ will sweep out the triangle $ADE$. If triangle $ADE$ has no vertices of polygon $M$, then $[AE]$ is the required diagonal. If such a thing is found, then we will definitely hit one when rotating the segment $AP$ from position $[AD]$ to position $[AE]$. The segment from vertex $A$ to the vertex closest to $A$ on the segment $AP$, which first “met” the vertices of the polygon $M$, will be the required diagonal.

The lemma is proven.

*) See, for example, the book by I. M. Yaglom “Geometric transformations, II. Linear and circular transformations" (Moscow, GTTI, 1956); the brochure by B. A. Rosenfeld and N. D. Sergeeva “Stegerfaitse transformations” (“Popular lectures on mathematics”, issue 53, M., “Hayka”, 1973); articles from «Kvant»: 1977, No. 10, p. 14; 1978, No. 12, p. c.: 1, 50 and 2nd s. covers.

⟦folio 26⟧

Figures 7, a and 7, b show examples of new points of the (2k)-gon and (2k+1)-gon, for which the estimate $\left[\frac{n}{2}\right]$ is achieved.

Thus, the most number of vertices of new points of the $n$-gon from which not a single diagonal can be verified is $\left[\frac{n}{2}\right]$.

S. Bichkov

F553. A heavy board of mass $M$ lies on two monocomment stones of radii $r$ and $R$ and equal masses. $m$.
Considered between the centers of stones $l$. With what acceleration will the board begin to move if it is loosened?
The friction between all surfaces is the mass that is assigned to it.

Since there is no slippage between all surfaces, when the board and rollers move, the distance $|AB|$ between the points of contact of the rollers and the horizontal plane and the equal distance $|A'B'|$ between the points of contact of the rollers and the board (Fig. 8) will remain unchanged. Consequently, the distance $|O_1O_2| = l$ between the centers of the rollers will not change. This means that the speeds of the centers of the rollers at any time are the same and are directed in a straight line $O_1O_2$.

Let's find the direction of the speed of the center of mass of the board $O$.
Let the speed of the roller centers be $\vec{v}$. Then in the reporting system moving with this speed, the centers of the rollers are motionless, the velocities of points $A'$ and $B'$, and therefore the speed $\vec{v}'$ of the center of mass of the board are equal in absolute value $\vec{v}$ and are directed along the board. In a stationary relative horizontal plane of the reporting system, the speed $\vec{u}$ of the center of mass of the board is equal to the vector sum of the velocities $\vec{v}'$ and $\vec{v}$.
From figure 8 it is clear that the speed $\vec{u}$ is directed parallel to the straight line $O_1O_2$. The movement of the board and its acceleration are also directed.

Let us denote by $\vec{s}$ the movement of the center of mass of the board at the moment when its speed is equal to $\vec{u}$. At this moment, the speed model of the roller centers $\vec{v} = |\vec{u}|/2 \cos \alpha$ and the kinetic energy of the entire system are equal to

$$2 \frac{m |\vec{v}|^2}{2} + \frac{M |\vec{u}|^2}{2} = \frac{|\vec{u}|^2}{4} (m \cos^2 \alpha + 2 M).$$

Fig. 8.

⟦folio 28⟧

where

$$t_0 = \frac{\mu g}{b} (m_1 + m_2).$$

Now it is not difficult to plot the dependence of $|\vec{a}_1|$ and $|\vec{a}_2|$ on time $t$ (Fig. 10).

I. Slobodetsky

F555. a) A light rigid rod of length $l$ with a mass $m$ at the top is hinged at the bottom point and held in a vertical position by two horizontal stiffening springs $k$, fastened to its upper end (Fig. 11). In the direction perpendicular to the springs, the rod cannot be bilingual. At what mass of load will the vertical position of the rod become stable?

b) A small knitting needle of length $l$ is set at half a maximum, which is 100 min vertical. If a small horizontal force $\vec{F}$ is applied to its upper end, the upper end of the spoke will deflect by amounts $a \ll l$. Estimate how much weight a knitting needle can withstand at its upper end without collapsing. The difference in shape, which, when horizontal or vertical forces act on it, elasticity balances the force $\vec{F}$, causes displacement of the end of the rod, that is, $\frac{|\vec{F}|}{a}$.

Therefore, the maximum load that a spoke can support is approximately

$$m \approx \frac{|\vec{F}| l}{ag}.$$

Fig. 11. Fig. 12.

can be neglected. Then the problem becomes similar to problem a), in which the value $2k$, which characterizes the stiffness of the springs in tension (compression), must be replaced by the rigidity $k'$ of the spokes by bending, equal to the ratio of the modulus of the elastic force balancing the force $\vec{F}$ to the displacement of the end of the rod, that is, $\frac{|\vec{F}|}{a}$.

Therefore, the maximum load that a spoke can support is approximately

$$m \approx \frac{|\vec{F}| l}{ag}.$$

⟦folio 29⟧

F556. If you put a piece of wire on an ice block, to which the éruz (Fig. 13) is suspended, the wire begins to cut the ice. This is explained by the fact that as the pressure increases, the melting point of ice is violated, the ice under the wire begins to soften, and above the wire it begins to freeze again. However, if something is made not from wire, but from a nylon thread of the same or even smaller diameter, the ice is practically not cut. Why? Try to check the described experience.

Fig. 13.

F557. In the circuit shown in figure 14, key K is closed. The maximum current in the circuit and the maximum voltage on the capacitor.

Fig. 14.

As the pressure increases, the melting point of ice is actually violated. However, as the ice melts, the heat of fusion is absorbed, and the temperature of the ice under the wire begins to drop. This occurs until the temperature of the ice in the area of ​​​​high pressure drops to the melting temperature when it begins. Further melting of ice will be determined by the heat that, due to thermal conductivity, will come to the region of elevated temperature.

In the case of wire, this heat will be conducted due to the good thermal conductivity of the metal from the water freezing from above, and the process of cutting the ice will be fast. In the case of a nylon thread, which has low thermal conductivity, heat will be conducted mainly due to the cooling of the entire block of ice as a whole, and the cutting process will be very slow.

I. Slobodetsky

After the key is closed, current will flow in the circuit. Due to the presence of inductance, the current cannot increase instantly; it will increase gradually until it reaches the maximum value.

The current flowing through the inductance will charge the capacitor. According to the law of conservation of energy at any moment in time

$$\frac{LI^2}{2} + \frac{CU^2}{2} = q$$ (*)

Here $I$ is the current flowing through the inductance at a given moment, $LI^2/2$ is the energy stored at this moment in the magnetic field of the inductance, $U$ is the voltage on the capacitor, $CU^2/2$ is the energy of the capacitor at a given moment, $q = CU$ is the charge passed through the battery, $q$ is the work done battery.

At a certain current value $I_0$, the voltage on the capacitor becomes equal to $\varepsilon$. From this moment on, the capacitor continues to charge due to the energy of the magnetic field of the inductance. In this case, the current through the inductance begins to decrease.

Therefore, $I_0$ is the maximum current in the circuit. From (*) at $U = \varepsilon$ there is

$$I_0 = \varepsilon \sqrt{C/L}.$$

Charging of the capacitor continues until flow occurs in the circuit ((*) under the condition $I = 0$:

$$U_{\max} = 2\varepsilon.$$

P. Zubkov
