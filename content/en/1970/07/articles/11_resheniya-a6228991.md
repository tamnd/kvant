---
id: 1970-7-resheniya-a6228991
issue: kvant_1970_7
year: 1970
number: "7"
title: '[Solutions to problems M1—M3; F1-F6]'
rubric: zadachnik-kvanta
page_first: 50
page_last: 60
page_labels: 48, 49, 50, 52, 53, 54, 55, 56, 57, 58
tag: H4HQ
lang: en
source: kvant_digital
extraction: vision
content_sha256: eaadb5cfa190f66669cd4bdaffcc179517e10b42809e7b9d12eb7c78e95a14a9
prompt_sha256: draft-1
translated_from: content/ru/1970/07/articles/11_resheniya-a6228991.md
source_content_sha256: a2a2f047989cc396b5628adab9bf189c4ad15a4e73dc875051f1d14bec175cf7
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

From this issue we will begin printing the solution to the Quantum Problem Book.
Most of the problems placed in this section of the journal are quite difficult and a discussion of some of them should be devoted to a larger statue. Many of them give rise to a conversation about a whole class of problems, about methods of approaching certain phenomena, about the use of various phenomena in practice. Sometimes we will have this conversation on the pages of our magazine. But often the reader himself should think about how to generalize the given solution, or how to simplify it, about where the phenomenon mentioned in the assignment is applied, etc.

The seventh issue was prepared for printing at the end of March, so, naturally, letters with decisions that we received later are not taken into account here. In the future, it is expected to publish the solution approximately six months after the publication of the problems. At the same time, we successfully got acquainted with the latest solutions “on time” - no later than a month and a half after the release of the corresponding issue. Of course, we will not be able to respond to all readers who sent us letters. The best solutions will be published on the pages of the magazine. Those who came up with a solution that is very different from the published one will have to figure out for themselves whether it is correct or not, and if not, what is the mistake.

And one last thing. Coming up with a problem is generally more difficult than solving it. It's more difficult, but it's also more interesting. Try to come up with problems and send them to us. We will publish the best problems in the Quantum Problem Book.

⟦folio 49⟧

M1. In the country of Anchuria, where President Miraflores rules, the time for new presidential elections is approaching. There are approximately 20 million voters in the country, of which only one percent (the regular army of Anchuria) supports Miraflores. Miraflores naturally wants to be elected, but on the other hand he wants the elections to appear democratic. What Miraflores calls “democratic voting” is this: all voters are divided into several equal groups, then each of these groups is raised by a number of equal groups, then these last groups are again divided into equal groups, etc.; in the smallest groups, representatives of the elector group are elected, then the elector submits for voting in an even larger group, etc.; finally, representatives of the largest groups choose a representative for the groups as he wishes, and instructs his parties how to vote. Will he be able to organize “democratic elections” in such a way that he will be elected president? (If the votes are equal, the opposition wins.)

Answer. Yes, we can.

First of all, let’s figure out how a candidate with a minority vote can win in a “multi-stage” election. (By the way, many capitalist countries vote under this system.) The simplest example of such a situation is depicted in figure 1: here nine voters - four "black" and five "blue" - are divided into three groups of three voters so that in two groups the blacks win, and therefore, as a result of this "two-stage election", the black candidate will be elected, although the number of his side is only $\frac{4}{5}$ of the total number of voters. (It is not difficult to report that in a two-stage election with a large number of voters, the percentage of votes sufficient to win may be even less, but everything is still completed above 25%.) It is clear that in a three-stage election system this percentage can be made even lower. For example, if we replace by figure 1 each voter in a group of one hundred people, so that in the voting group all of these voters are voting, and in the black group there are 51 blacks and 49 blues, then we get an example of a situation where blacks make up only $\frac{4}{9} \cdot \frac{51}{100} = \frac{17}{75}$ of the total number of voters and nevertheless win.

After these preliminary messages, the solution to the problem came.

Let's divide all voters into 5 groups of 4 million each so that two groups will consist entirely of opponents of Mirafloresa (let's call these groups “blue”, and the other three “black”). Each of

⟦folio 50⟧

These “first rank” groups will again be divided into 5 groups of second rank, and of the five groups that make up the black group of the first rank, three are black, etc., as indicated in the table.

It is clear that with such a division, for Miraflores to win, it is enough for people to vote for him

$$\frac{3^{11}}{2^8 \cdot 5^7} = \frac{177 \cdot 147}{20 \cdot 000 \cdot 000} < \frac{1}{100}$$

part of all voters. Thus, since the army constitutes $\frac{1}{100}$ part of the voters and supports Miraflores, he will be able to win.

Some readers have tried to solve the following, more general question: what is the smallest number of supporters Miraflores must have to win a “democratic election” if the total number of voters is $N$? Of course, the answer to this question depends not so much on the size of the number $N$, but on how it is factored. If, say, $N$ is a prime number, then voters cannot be divided into equal groups in any way (except for the trivial method: $N$ groups of one person each) and to win you need to have a simple greater instrument. We'll show you how to answer this question for any $N$.

Let us consider such a division of $N$ people into groups (1st, 2nd, etc. rank), in which Miraflores wins and the number of his side is the smallest possible. Obviously, it can be assumed that in the groups voting against him there is not a single one on his side and that all black groups of the same rank are divided exactly the same. It is convenient to use communication $[1]$ - “integer part” ($[x]$ - the most integer number, not exceeding $x$; for example, $[2] = 2$, $[3\frac{1}{2}] = 3$). It is clear that if a non-orthodox black group consists of $k$ groups of the next rank, then there must be at least $[\frac{k}{2}] + 1$ blacks among them. Let each group of $r$ rank ($r = 1, 2, \dots, m-1$) be divided into $k_r$ groups of lesser rank, and let the groups of the last $m$ rank consist of 1 person. Then to win you must have at least

$$B = \left( \left[ \frac{k_1}{2} \right] + 1 \right) \left( \left[ \frac{k_2}{2} \right] + 1 \right) \dots \left( \left[ \frac{k_m}{2} \right] + 1 \right)$$

black voices. Our task boiled down to this: decompose the given $N$ into a product of maximals $k_1, k_2, \dots, k_m$ so that the product $B$ is minimal.

Let

$$N = k_1 k_2 \dots k_m$$

- such decomposition. As the next lemma shows, we can propose that in this expansion there are no factors $k$ of the form $k = pq$, where $p$ and $q$ are greater than 2 (if there are such, we can check the further expansion without increasing $B$).

Lemma.

$$\left( \left[ \frac{p}{2} \right] + 1 \right) \left( \left[ \frac{q}{2} \right] + 1 \right) \leq \left[ \frac{pq}{2} \right] + 1$$

for all integers $p$ and $q$ greater than 2.

Proof. If $p$ and $q$ are both even, then the inequality can be rewritten as:

$$\left( \frac{p}{2} + 1 \right) \left( \frac{q}{2} + 1 \right) \leq \frac{pq}{2} + 1,$$

$(p + 2) (q + 2) \leq 2pq + 4,$

$pq - 2q - 2p + 4 \geq 4, \quad (p - 2)(q - 2) \geq 4,$

which is obviously true for $p > 2$ and $q > 2$.

In the case when one of the numbers $p, q$, for example $p$, is even and the other is odd, we have:

$$\left( \frac{p}{2} + 1 \right) \left( \frac{q}{2} + 1 \right) \leq \frac{pq}{2} + 1,$$

$(p + 2) (q + 1) \leq 2pq + 4,$

$pq - 2q - p + 2 \geq 0, \quad (p - 2)(q - 2) \geq 0.$

The case where $p$ and $q$ are odd is split similarly. The lemma is proven. From here it immediately follows that odd $N$ must be factored “to the end” into prime factors. All that remains is to deal with the deuces.

We can assume that the expansion contains no factors of the form $2q$, where $q$ is odd, since $2$ is of rank

$$2 \left( \left[ \frac{q}{2} \right] + 1 \right) = \left[ \frac{2q}{2} \right] + 1.$$

⟦folio 52⟧

necks through the centers of the circles and the center of the sphere. Indeed, both circles are symmetrical with respect to the plane $P$, and if they had a common point on one side of the plane $P$, they would have to have a symmetrical common point on the other side $P$, but they have only one common point. If these circles have the same radius $r$, then the distance between their “centers” is equal to $2r$, because on the great circle circle resulting from the intersection of the sphere and the plane $P$ (Fig. 2, $\theta$), the diameters of our circles (black segments) and the segment connecting their “centers” (red) contract equal arcs.

Let $A_0, A_1, A_2, \dots, A_n$ be the “centers” of circles $\gamma_0, \gamma_1, \dots, \gamma_n$, which are discussed in the conditions of the problem. Then $A_0A_1 = A_0A_2 = \dots = A_0A_n = A_1A_2 = A_2A_3 = \dots = A_nA_12r$, in other words, $A_0A_1A_2 \dots A_n$ is a regular $n$-gonal paramid inscribed in a given sphere of radius 1 with vertex $A_0$, all of whose lateral faces are equilateral triangles with sides equal to $2r$. So, it is enough to construct a paramid for which these conditions are met, then the points $A_0, A_1, \dots, A_n$ will be certain circles of radius $r$ with “centers” $A_0, A_1, \dots, A_n$, which obviously satisfy the conditions of the problem.

Since the sum of the plane angles of a convex $n$-faceted angle with vertex $A_0$ is less than $360^\circ$:
$$n \cdot 60^\circ = A_1A_0A_2 + A_2A_0A_3 + \dots + A_nA_0A_1 < 360^\circ,$$
then $n < 6$. For $n = 3, 4$ and 5 it is not difficult to construct the necessary paramids.

Let $O$ be the center of the sphere. The height of the paramid $h$ and the length of its edges $2r$ are found from the following considerations: the radius $KA_1$ of the base of the paramid is the leg $\Delta A_0KA_1$ and the side $\Delta A_1KA_2$, where $\Delta A_1KA_2 = 2\pi/n$ (Fig. 3, $a, \delta$),

$$\sqrt{4r^2 - h^2} \sin \frac{\pi}{n} = r.$$

From $\Delta A_0OA_1$ we have $r = \frac{h}{2r}$.

Hence $h = 2r^2$, $r = \sqrt{1 - \frac{1}{4 \sin^2 \frac{\pi}{n}}}$.

Thus,

at $n = 3$: $r = \sqrt{\frac{2}{3}} \left( \sin \frac{\pi}{3} = \frac{\sqrt{3}}{2} \right)$;

at $n = 4$: $r = \sqrt{\frac{1}{2}} \left( \sin \frac{\pi}{4} = \frac{\sqrt{2}}{2} \right)$;

at $n = 5$: $r = \sqrt{\frac{5 - \sqrt{5}}{10}}$

(the formula $\sin \frac{\pi}{5} = \frac{\sqrt{10 - 2\sqrt{5}}}{4}$ can be derived from figure 4, with the help of which regular decagons and regular heel-gons are constructed).

⟦folio 53⟧

Knowing $r$ and $h$, we can construct correct paramidas, which, due to the above relations, will satisfy all the necessary conditions: all faces are equilateral triangles with sides $2r$, the radius of the circumscribed sphere is 1.

The constructed paramids are closely related to regular polyhedral

kami, the faces of which are triangles. There are only three such polyhedra: tetrahedron, octahedron and ikocahedron (Fig. 5), and if from each of these polyhedra we cut off the “top” - all the faces adjacent to one vertex - then we get exactly the same three paramides that we were studying. You can read more about regular polyhedra and the construction of a pentagon in the excellent book by G. S. Kokter “Introduction to Geometry” (“Science”, 1966, Chapter 10 “Five Platonic Solids” and Chapter 11 “Golden Ratio and Phyllotaxis”).

A 10th grade student Serdey Makeev from Volokolamsk solved the problem somewhat differently (without using “centers on the sphere”).

Let us also note that the constraint $n \geq 3$ in the conditions of the problem could be completely replaced by $n \geq 2$. A corresponding arrangement of three circles $\gamma_0, \gamma_1, \gamma_2$ exists (Fig. 6; the “centers” of the circles are located at the vertices of a regular triangle-

⟦folio 54⟧

Fig. 6.

ka inscribed in a large circle), and to calculate $r$, oddly enough, the same formula that we proved for $3 \leq n \leq 5$ is suitable

$$r = \sqrt{1 - \frac{1}{4 \sin^2 \frac{\pi}{2}}} = \frac{\sqrt{3}}{2}.$$

M3. a) On figure 7, $a$ the plane is covered with squares of five colors. The centers of squares of the same color are located at the vertices of the square grid. With what number of colors is a similar filling of the plane possible?

6) On figure 7, $b$ the plane is covered with hexagons of those colors so that the centers of hexagons of the same color form the vertices of a lattice of identical regular triangles. With what number of colors is a similar filling possible?

Note. In the first problem, the number of colors can be one (all squares are the same color) or two (like on a chessboard). In the second problem you can easily find a pattern with one color and with three colors. It is advisable to give a complete solution to the problems, i.e., describe all colorings that satisfy the specified conditions. However, please send incomplete solutions if you find them interesting. Think, for example, is there a solution to the second problem with thirteen colors?

We have not yet received complete solutions to this problem.

6th grade student Serey Eliseev (Moscow) sent us a coloring of a hexagonal grid with thirteen colors, which we reproduce, as far as printing capabilities allow, on figure 8;

Fig. 7 a, b.

he states (without explanation) that the answer in general is:

In problem a), the required coloring is possible if the number of colors is equal to the sum of two squares of integers:

$$1 = 0^2 + 1^2; \quad 2 = 1^2 + 1^2; \quad 4 = 0^2 + 2^2; \quad 5 = 1^2 + 2^2; \quad 8 = 2^2 + 2^2; \quad 9 = 0^2 + 3^2; \quad 10 = 1^2 + 3^2; \quad 13 = 2^2 + 3^2; \quad 16 = 0^2 + 4^2$$, etc.

In problem b) the solution is possible with the number of colors equal to the sum of two numbers from the sequence 0, 1, 3, 6, 10, 15, . . . , $\frac{n(n+1)}{2}$, . . .

$$1 = 0 + 1; \quad 3 = 0 + 3; \quad 4 = 1 + 3; \quad 6 = 0 + 6; \quad 7 = 1 + 6; \quad 9 = 3 + 6$$, etc.

Try to find out if these answers are correct? We will return to this issue later, but for now let us pay attention to one point in the formulation of the problem (reader V. Gutenacher from Moscow was the first to notice it).

Let's start with task a). It requires finding colorings in which “the centers of squares of the same color are located at the vertices of a square grid.” But the condition does not say that this “large” square grid should be the same for different colors. Look at figure 9. Here, too, the squares of each of the three colors form a grid, but for red the “step” (side of the square) of the grid is $\sqrt{2}$, and for white and green it is 2, and even the grid is surface-

⟦folio 55⟧

Fig. 8.

chickpeas relative to each other. But if the condition of the problem is understood literally - and this is exactly what should be done on a written exam or at an Olympiad - then the coloring of Figure 9 satisfies the condition of the problem. With this understanding, the answer to problem a) will be this: for any number of colors. Indeed, from any coloring with $n$ colors, one of which is white, it is easy to make a coloring with $(n+1)$ color: you need to color the white squares in a “checkerboard order” with white and the new $(n+1)$ red (this is how the coloring of Figure 9 was obtained from a checkerboard red-white coloring).

With this understanding, task 6) becomes very simple.

Answer. For any number of colors greater than 2. Indeed, coloring with two colors is impossible, since if out of three hexagons, each two of which have a common side, two are covered in the same color, then all hexagons must be colored with this color. coloring pages with 3 and 4 colors are easy to find, and then it’s not difficult to color white hexagons in three colors, increase the number of colors by 2, then by 2 more, etc.

Of course, you can get a lot of different coloring pages this way. Having any coloring $A(k)$ colors, highlighting in

⟦folio 56⟧

F1. Three communicating vessels with water, the centers of which are at the same distance $a$ from each other, are covered with pistons of the same thickness, made of the same materials. Vertical identical rods are attached to the pistons, which are hingedly connected to the rod $AB$. At what point on the rod can a load be attached to it so that in the equilibrium position the rod remains horizontal, if the masses of the rod and rods are negligible compared to the masses of the pistons and the load. The diameters of the vessels are $d_1$, $d_2$ and $d_3$, respectively.

Torsion $AB$ and the pistons are in equilibrium under the action of seven forces: force $Q$, acting from the load, the force of gravity acting on the pistons—these forces are proportional to the areas of the pistons: $P_1 = k_1 d_1^2$; $P_2 = -k_1 d_2^2$; $P_3 = k_1 d_3^2$ and three fluid pressure forces on the pistons: $N_1$, $N_2$, $N_3$ (Fig. 10). Since the liquid levels in the vessels are the same, the pressure on all pistons is equal, and the pressure force is related to the area of ​​the pistons: $N_1 : N_2 : N_3 = d_1^2 : d_2^2 : d_3^2$. Therefore $N_1 = k_2 d_1^2$, $N_2 = k_2 d_2^2$, $N_3 = k_2 d_3^2$.

The equal forces applied to each of the pistons are equal: $F_1 = N_1 - P_1 = (k_2 - k_1) d_1^2 = kd_1^2$, $F_2 = kd_2^2$, $F_3 = kd_3^2$.

Denoting by $x$ the distance from the middle of the rod to the point at which the load is attached, we write down the conditions of the rod: 1) the sum of all forces acting on the rod is equal to zero: $F_1 + F_2 + F_3 - Q = 0$ and 2) the sum of the moments of all forces acting on the rod is equal to zero relative to the middle of the rod: $F_1 a - F_3 a - Qx = 0$. Substituting the expressions for $F_1$, $F_2$ and $F_3$ into these equations, and then solving these equations together, we find that

$$x = \frac{d_1^2 - d_3^2}{d_1^2 + d_3^2 + d_3^2} a.$$

None of the readers who sent a solution to this problem took into account the masses of the pistons. But only two - G. Kalshin from Kirovobad and A. Karpenko from the town of Lisiansk, Voroshilgovred region - explained why this could be done. Since the pistons are made of the same materials and have the same thickness, the additional pressure on the body does not depend on the diameters of the pistons. The condition for equilibrium of the pistons is the equality of pressure on the body in all cylinders (since the water levels in the cylinders are the same). Additional pressures due to the pistons satisfy this condition automatically.

F2. Two balls with masses $m_1$ and $m_2$ lie on a horizontal plane, fastened together by a spring with a stiffness $c$. The plane is smooth. The balls are bent, releasing the spring, then they are simultaneously released. Determine the periods of the resulting oscillations of the balls.

The center of mass of the system should not move (or can move uniformly and rectilinearly), therefore the balls vibrate in antiphase with the same frequency, and their deviations $x_1$ and $x_2$ from the equilibrium position satisfy the corresponding pieces of the spring with lengths $l_1$ and $l_2$ ($l_1$ and $l_2$ are the distances from the balls to the center of mass of the system;

$$l_1 = l \frac{m_2}{m_1 + m_2}, \quad l_2 = l \frac{m_1}{m_1 + m_2}).$$

The elongation of the $1/q$th part of the spring is always $q$ times less than the elongation of the entire spring, i.e. the $1/q$th part of the spring has a stiffness $q$ times greater elongation than

⟦folio 57⟧

The stiffness of the entire spring. Therefore $c_1 = \frac{m_1 + m_2}{m_2} c$. It follows that the period of oscillation of the balls

$$T = 2\pi \sqrt{\frac{m_1 m_2}{(m_1 + m_2) c}}.$$

It is interesting to check the answer by taking some limiting case. This is what E. Tikhonov, a 10th grade student from school No. 20 from the city of Volgda, did. Let us assume that the mass of $m_2$ is very large: $m_2 \gg m_1$. Then a ball with mass $m_1$ should oscillate like this; as if the second ball were fixed, and $T = 2\pi \sqrt{\frac{m_1}{c}}$. Let's check our formula

$$T = 2\pi \sqrt{\frac{m_1}{c \left(1 + \frac{m_1}{m_2}\right)}} \approx 2\pi \sqrt{\frac{m_1}{c}}.$$

F3. Two springs were made from two identical pieces of steel wiring. The diameter of the turns of one of them is $d$, the other $2d$. The first spring, under the action of the load, stretched by one tenth of its length. How much of its length will the second spring stretch under the same load?

The elongation of the spring is equal to $\Delta l = n \cdot 2d \cdot \sin \frac{\alpha}{2}$, where $n$ is the number of turns of the spring, and $\alpha$ is the angle at which adjacent turns of the spring unfold (Fig. 11). Since the extension of the spring is small, this angle is also small $\sin \frac{\alpha}{2} \approx \frac{\alpha}{2}$. Therefore $\Delta l = nd\alpha$.

Angle $\alpha$ is proportional to moment

forces $F$, which stretch the coil: $\alpha = F \cdot d$. The force $F$ is equal to the weight of the load suspended from the spring, and is the same in both cases, so $\Delta l \sim nd^2$.

The diameter of the coils of the second spring is twice as large, and the number of coils is twice as small, therefore, the abscylton elongation of the second spring is twice as large as that of the first. Thus, the second spring will stretch $\frac{2}{5}$ of its length.

Many who tried to solve this problem correctly found that the elongation of the second spring is twice as great as the first, but they forgot that the second spring is half as long as the first, therefore the relative elongation of the second spring is equal to $\frac{1}{5}$, as they found out, and $\frac{2}{5}$.

F4. The cylinder contains purified gas, but it is not known what kind. To raise the temperature of 1 keto gas by one degree at constant pressure, 958.4 J is required, and at constant volume - 704.6 J. What kind of gas is this?

When heating a gas at a constant volume of energy, the energy expended only goes towards changing the internal energy of the gas, and when heating at a constant pressure, it also goes towards doing work. Let us write down the law of conservation of energy for both cases:

$$mc_V \Delta t = \Delta W,$$

$$mc_p \Delta t = \Delta W + A.$$

Here $c_p$ is the specific heat of the gas at constant pressure (i.e., the amount of heat required to heat 1 kE of gas at constant pressure), $c_v$ is the specific heat of the gas at constant volume, $\Delta t$ is the change in temperature, $\Delta W$ is the change in the internal energy of the gas, $m$ is the mass of the gas, $A = p \Delta V$ is the perfect temperature during expansion gas work ($\Delta V$ - change in volume, $p$ - pressure).

Since when the temperature of a gas increases by the same number of degrees, the change in its internal energy is the same both when heated at a constant volume and when

⟦folio 58⟧

heating at constant pressure, we can write: $c_p m \Delta t = c_v m \Delta t + p \Delta V$. Using the equation of gas state (Clapeyron-Mendeleev equation), the work done by a gas can be expressed through the molecular mass of the gas $\mu$ and the gas constant $R$: $p \Delta V = \frac{m}{\mu} R \Delta t$. Substituting this correspondence into equation (1), we obtain: $c_p = c_v + \frac{R}{\mu}$, whence

$$\mu = \frac{R}{c_p - c_v} \approx 32,7 \text{ ккал/кмоль}.$$

The unknown gas is oxygen with a very small admixture of a heavier gas.

F5. There is an electrical target selected at figure. What will a voltmeter with a very high internal resistance show if it is connected to points $C$ and $D$? $U_{AB} = 518$.

The voltmeter will show the presence of voltage between points $E$ and $D$. In order to find it, it is convenient to first determine the voltage voltage between points $F$ and $B$. To do this, the circuit can be rewritten as shown in figure 12.

$$R_0 = 3 \text{ ом}, R'_0 = \frac{3}{4} \text{ ом},$$

$$U_{FB} = U_{AB} \frac{R'_0}{R_0^1 + R_1} = \frac{3}{11} U_{AB}.$$

Now, in the same way, find what

$$U_{ED} = \frac{R_3}{R_2 + R_3} U_{FD} = \frac{1}{3} U_{FD} = \frac{1}{11} U_{AB} = 4,6 \text{ е}.$$

This problem was correctly solved by almost all the readers who sent us letters.

F6. Find the value of a grounded metal ball of radius $r$ if there is a point charge $q$ at a distance $R$ from its center.

The ball's potential must be zero. The field potential at the center of the ball, equal, of course, to the potential of the ball, is the sum of the field potential of the point charge $q$ and the field created by the charge $Q$ of the ball. The charge $Q$ is not distributed uniformly over the ball, but if the ball is divided into small sections with charges $\Delta q$, then the potential of the field created by the charge of the ball in the center can be expressed as the total potential of the fields of the exact charges $\Delta q$. Thus, we can write for the center of the ball:

$$\Delta \varphi = \sum \frac{\Delta q}{r} = \frac{1}{r} \sum \Delta q = \frac{Q}{r} + \frac{q}{R} = 0.$$

Hence $Q = -\frac{r}{R} q$.

Many readers received the correct answer, but we received very few correct solutions. Many readers have used the formula for the capacitance of a capacitor $C = \frac{\Delta Q}{\Delta \varphi}$, assuming the capacitance of the ball to be $r$. But this is true only for an isolated ball with a uniformly distributed charge.
