---
id: 1990-6-resheniya-zadach-m1201-m1205-f1213-f1217-41cee53a
issue: kvant_1990_6
year: 1990
number: "6"
title: Solutions to problems M1201—M1205; F1213—F1217
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 31
page_last: 39
page_labels: 29, 31, 32, 33, 34, 35, 36, 37
lang: en
source: kvant_digital
extraction: vision
content_sha256: d782109cafc2acf41ef8a10e9f57f583a5a882df5b0ece60bdfd9f8887ddf01c
prompt_sha256: draft-1
translated_from: content/ru/1990/06/articles/07_resheniya-zadach-m1201-m1205-f1213-f1217-41cee53a.md
source_content_sha256: 9a2786d2a6f45dddcba0393564fd714ede3908957d5c95bd918585cfd03c7313
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 29⟧

Problem solutions

M1201—M1205, F1213—F1217

Candidates from the party $C$, very indo, will be able to enter all 999 constituencies (Fig. 1). Let us estimate from above the number of constituencies in which party $C$ can lose. If in $x$ districts $C$ has less than $N/2$ supporters, then the total number of supporters (equal to 0.55 · 999 $N$; $N$ is the number of voters in the district) does not exceed

⟦folio 31⟧

---
running_head:
folio:
---

M1202. From vertex A of the square ABCD, two rays are drawn inside the square, onto which the redistributions BK, BL, DM, DN are dropped from vertices B and D. Prove that the segments KL and MN are equal and the redistributions are equal.

Let us consider a rotation $R$ around the center of the square by $90^\circ$, at which points B and A will go to A and D, respectively. Let us show that with this rotation the segment KL will go to the segment MN (see Fig.ok) - thereby the problem will be solved. Since $\angle KBA = 90^\circ$ - $\angle KAB = \angle KAD$ and, similarly, $\angle KAB = \angle ADM$, ray BK with this rotation will go into ray AM, and ray AK into DM. Consequently, the intersection point K of rays BK and AK will go to the intersection point M of rays AM and DM, i.e. $R(K) = M$. In the same way it is proved that $R(L) = N$.

V. Dubrovsky

M1203. Is it possible to cut a square from a side of 1 km into a) 31 squares; b) 30 square so that one of them has a side of no more than 1 m.

Fig. 1.

Fig. 2.

Answer: in both problems it is possible.
The most natural idea is to cut the square into 4 smaller squares; one of the resulting squares is again “quartered”, etc. (Fig. 1). Each such operation increases the number of squares by 3, after the tenth size of the squares it will become $3 \cdot 10 + 1 = 31$, and the side of the smallest will be $2^{10} = 1024$ times smaller than the side of the original square. The condition of point a) is met.

In order to answer the question of point 6), consider our process “in reverse” - not as cutting a large square into a small one, but as composing a large one from small squares (starting with square $1 \times 1$). Before the last step we will have a square $512 \times 512$ made up of 28 smaller squares. Of the three squares that we are going to add, we will try to take one a little larger than the others - so that it absorbs the small square in the corner. We will save one square, and the side of the large square is now 1023 times larger than the side of the small one (Fig. 2).

The problem is to solve, but the question naturally arises - what should be the “best” partition, more precisely:
For what maximum $n$ can a square $n \times n$ be cut into $k$ squares, the minimum of which has dimensions $1 \times 1$?

The author has collected a “collection” of record partitions, among which there is, in particular, a partition of the square $1121 \times 1121$ into 27 squares. The ideas used in constructing such partitions are quite interesting, and we hope to return to this topic in the pages of the journal, having become acquainted with letters from readers.

S. Eliseev

⟦folio 32⟧

---
running_head:
folio:
---

M1204*. Points A, B, C are given on the plane - the centers of three circles. Each circle inflates evenly (the radius increases at the same rate for all circles). As soon as two circles touch each other, they “pop”—their radii decrease to 0—and begin to expand. Is it true that if the distances AB, BC, CA are integers, then this process will be periodic?

Study how this process can develop if triangle ABC is a) equilateral; b) equidistant; b*) rectangular on the side 3, 4, 5. The initial state can be arbitrary (not only “zero”).

Fig. 1.

We will consider the general case: the initial radii of the bubbles are arbitrary.

a) Triangle ABC is equilateral. After the first pop, the radii of the two bubbles will be zero. The second pop will burst all three bubbles. The process will then be repeated periodically.

6-1) Triangle ABC is equilateral, the base is smaller than the side. Then, at the first or second clap, two bubbles will burst, the centers of which lie at the base of the triangle. Further, their radii will be equal (Fig. 1). Soon all three bubbles will burst simultaneously, after which a periodic process begins. The number of claps in a period (cycle) depends on the ratio of the length of the side and the base.

Now let's look at the remaining case from a more general point of view: 6-2) (the base is larger than the side) and c). We see that in these cases the process will generally not be periodic.

Let us denote the lengths of segments BC, AC and AB by a, b and c, respectively. Let for definition $a \leq b < c$. (We have already considered option $b = c$.) Note that bubbles with centers at points A and B (short: bubbles A and B) can touch only at the very beginning of the process. After this, bubble C is involved in each clap. Thus, the specific value of the quantity $c$ does not play any role (as long as condition $b < c$ is satisfied). It is also clear that it is not the lengths $a$ and $b$ themselves that are important, but their ratio $r = b/a$. Therefore, we will further consider triangle ABC with sides $BC = 1$, $AC = r \geq 1$ and base $AB > r$.

Let us denote by $x$ and $y$ the radii of bubbles A and B immediately after an arbitrary clap. However, there will be a next clap, depending on what is greater - the length of the side opposite to the bubble, or the difference between the other side and the radius of this bubble. Thus, the transformation of the quantities $x$ and $y$ occurs according to the rules indicated in Table 1.

Table 1

| Current status | Conversion |
| :--- | :--- |
| 1 $y = 0, r - x > 1$ | $x_{\text{HOB}} = x + \frac{1}{2}, y_{\text{HOB}} = 0$ |
| 2 $y = 0, r - x = 1$ | $y_{\text{HOB}} = 0, x_{\text{HOB}} = 0$ |
| 3 $y = 0, r - x < 1$ | $y_{\text{HOB}} = (r - x)/2, x_{\text{HOB}} = 0$ |
| 4 $x = 0, 1 - y < r, y \neq 0$ | $x_{\text{HOB}} = (1 - y)/2, y_{\text{HOB}} = 0$ |

Here $x_{\text{HOB}}$ and $y_{\text{HOB}}$ are the new values ​​of $x$ and $y$ immediately after the next clap. Option $x = 0, 1 - y \geq r$ is not included in the table, since it is impossible with $r > 1$, and in the case

⟦folio 33⟧

---
running_head:
folio:
---

$r=1$ only the second option $x=0$, $1-y=r$ (i.e. $y=0$) is possible, which is described by line 2.

Studying the table shows that from state 3 (and only from it) we always get to state 4. Therefore, lines 3 and 4 can be combined into one (remembering that it corresponds to two claps). The consideration now focuses on states with $y=0$ (see Table 2).

Table 2

| State | Conversion | Number of claps |
| :--- | :--- | :--- |
| 1 | $x<r-1$ | $x_{\text{HOB}}=x+\frac{1}{2}$ | 1 |
| 2 | $x=r-1$ | $x_{\text{HOB}}=0$ | 1 |
| 3 | $x>r-1$ | $x_{\text{HOB}}=(2-r+x)/4$ | 2 |

Thus, the sequence of values ​​of the variable $x$, fixed at the moments of popping bubbles $B$ and $C$, is determined recursively by the formula $x_{\text{HOB}}=f(x)$, where the function $f$ is defined on the interval [0; $r$] in accordance with table 2:

$$f(x)=\begin{cases}
x+1/2, & \text{ если } x<r-1, \\
0, & \text{ если } x=r-1, \\
(2-r+x)/4, & \text{ если } x>r-1.
\end{cases}$$

For the case $r=1$ (item 6-2) of the problem, the graph of the function $f$ is shown on figure 2. From figure it is clear that the interaction process is periodic for the initial values ​​$x=0$ and $x=\frac{1}{3}$ (in the corresponding period there is one double clap or two single ones). In other cases, the process tends to a “stable” state $x=\frac{1}{3}$, and thus it is non-periodic.

Since the initial states $a$, $b$ and $c$ (under the assumptions $a=b<c$) can be integer, the answer to the first question of the problem is negative.

For item c) $r$ is equal to 4/3. The graph of the corresponding function $f$ is shown in figure 3. The graph shows a single cycle including 5 claps. The specific values ​​of the numbers $x_1$, $x_2$, $x_3$ (see Fig. 2) can be found from the system

$$\begin{cases}
x_2=x_1+\frac{1}{2} \\
x_3=\frac{x_2}{4}+\frac{1}{6}, \\
x_1=\frac{x_3}{4}+\frac{1}{6}.
\end{cases}$$

They are equal: $x_1=\frac{23}{90}$, $x_2=\frac{34}{45}$, $x_3=\frac{16}{45}$.

Having considered several cases of choosing the initial value $x$, it is easy to show that any “trajectory” of the process approaches the described cycle. If,

⟦folio 34⟧

---
running_head:
folio:
---

say $x = x_1 + \varepsilon$, where $\varepsilon$ is small enough, then at the next step $b = f(x_1 + \varepsilon) = x_2 + \varepsilon$, then $x = f(x_2 + \varepsilon) = x_3 + \frac{1}{4} \varepsilon$, after which $x = f(x_3 + \frac{1}{4} \varepsilon) = x_1 + \frac{1}{16} \varepsilon$. Thus, the difference $x - x_1$ decreases by 16 times in 5 claps, and the process quickly approaches the “limit cycle”.

Recall that at the beginning of the solution we divided all linear dimensions by $a$ (in this case, by 3). Taking this into account, the answer for point c can be formed as follows: if at the moment of the first contact of the bubbles $B$ and $C$ the radius of the bubbles $A$ is equal to $\frac{23}{30}, \frac{34}{15}$ or $\frac{16}{15}$, then the process will be periodic; otherwise, no.

The general case (an arbitrary triangle) can be considered in a similar way. Although the technical difficulties here increase sharply, fundamentally new types of travel behavior are not discovered. For the case of four or more bellies, the answer (hereinafter as a form) is unknown.

S. Fomin

M1205. A boy and a girl play the following game: the boy draws non-overlapping polygons on a plane, and the girl colors them. If two polygons have a common side segment, then they must be painted in different colors. What is the smallest number of colors completed that will be enough for girls to follow these rules,

Let's call a polygon $M$ a polygon $M_1$ if it is possible to construct an integer chain of similar polygons, starting with $M$ and ending with $M_1$, in which neighboring polygons collide along a segment. It is enough to learn how to color only a set of interconnected polygons (unconnected ones cannot collide).

a) Answer: two colors are enough. All equilateral triangles connected to a given triangle $\Delta$ will either have the same rotation from $\Delta$ (like $\Delta_1$ on figure 1) or rotate by $180^\circ$ with respect to $\Delta$ (like $\Delta_2$ on figure 1). Triangles of the first type are painted one color, the second - another. Then one thing-

⟦folio 35⟧

---
running_head:
folio:
---

a) equilateral triangles;
b) isosceles right triangles;
b) identical squares?

Fig. 1.

Fig. 2.

Fig. 3.

Fig. 4.

Let's color its nodes in four colors, as shown in figure 4. To determine how to color the next square, let's remove the top and right sides from its boundaries. The remaining “planed” square always contains exactly one lattice node - we will take the color of this node. Obviously, “planed” squares containing single-link nodes cannot touch. This means that the correct thing will be observed.

If the girl had only three squares, then squares 1 and 2 would be on figure 5, and would have to be colored the same, which means on figure 5, the bars of squares 1 and 2, 1 and 3, 2 and 4, 3 and 5 would be the same. But squares 4 and 5 must be different colors. Therefore, to color the squares in figure 5, b, at least four colors are required.

We propose to prove that in a game with squares of arbitrary sizes, a girl will not have enough colors. Think about how many colors there will be in a game with equal regular hexagons.

G. Kondakov

⟦folio 36⟧

---
running_head:
folio:
---

F1213. A homogeneous inextensible rope is suspended by its ends at points A and B, located at different heights (Fig. 1). The tension in the rope at point A is $T_A$. Find the tension of the rope at point B if it is located h above point A. The mass of the rope is m, the length is l.

Fig. 1.

Fig. 2.

F1214. Following a projectile fired horizontally from a mountain h = 1 km high at a speed of $v_0 = 500$ m/s, a second projectile was fired after a time of $t_0 = 1$ s. What minimum initial speed should it have and at what angle should it fly out in order to catch up with the first projectile?

We present two solutions to this problem.

1) Let's imagine that we have some supply of rope at point A. Let's release the rope to a small length $\Delta l$ at point A and choose the same length $\Delta l$ at point B. Obviously, in this case, work will be done equal to $(T_B - T_A)\Delta l$, where $T_B$ and $T_A$ are the tension forces of the rope at points B and A, respectively. This work is spent on changing the potential energy of a section of rope with mass $m\Delta l/l$ when rising to a height h. According to the law of conservation of energy,

$$mg\frac{\Delta l}{l}h = (T_B - T_A)\Delta l,$$

where do we get it from

$$T_B = T_A + \frac{mgh}{l}.$$

2) Let's connect points A and B with a smooth inclined plane of length L and close the rope along this plane (Fig. 2). It is clear that the entire rope must be in balance. A section of rope lying on a plane maintains equilibrium by the difference in rope tension at points B and A:

$$T_B - T_A = \frac{mL}{l}g\frac{h}{L},$$

And

$$T_B = T_A + \frac{mgh}{l}.$$

E. Tatarinova

First, consider the problem in report system 1 associated with a launcher (we assume that both projectiles are fired from the same launcher located on the top of the mountain (see figure)). By the time of the second shot, the primary projectile will have traveled a distance $x_0 = v_0t_0$ horizontally and $y_0 = gt_0^2/2$ vertically. In this case, it will have a speed equal to $v_1 = \sqrt{v_x^2 + v_y^2} = \sqrt{v_0^2 + (gt_0)^2}$ and directed at an angle $\alpha = \arctg(gt_0/v_0)$ to the horizon. Let's imagine that the second projectile was fired at a speed of $v_1$ at an angle of $\alpha$ to the horizontal. In this case of the second shot, both projectiles would move while being at the same distance $s_0 = \sqrt{x_0^2 + y_0^2}$ from each other.

Let's connect reporting system 2 with the second projectile if it were moving as we assumed. In this system, the second projectile will finish the primary if it approaches it along a straight line connecting the projectiles with a relative speed $\vec{v}'$. Let's find its magnitude and direction.

It is clear that the convergence speed cannot be arbitrarily small in value, or the convergence must be initiated less than the flight time

⟦folio 37⟧

---
running_head:
folio:
---

$t = \sqrt{2h/g}$. So,

$v' \geq \frac{s_0}{t} = s_0 \sqrt{\frac{g}{2h}}$.

The relative velocity vector $\vec{v}'$ must make an angle $\alpha'$ with the horizon such that

$$tg \alpha' = \frac{y_0}{x_0} = \frac{gt_0}{2v_0}$$.

Now let's return again to the stationary system of cutoff 1. Here the projections of the desired speed $\vec{v}$ should be equal

$$v_x = v_0 + v' \cos \alpha', v_y = -gt - v' \sin \alpha'$$,

where $v' \geq s_0 \sqrt{g/(2h)}$. The minimum value of speed $v' = s_0 \sqrt{g/(2h)}$, at which the meeting of projectiles will occur near the surface of the earth, corresponds to the angle

$$\alpha_0 = \arctg(v_y/v_x) |_{t=t_0} = 0,019 \text{ рад} = 1^\circ 5'$$.

missing horizontal view. In this case, the desired speed of the second projectile is equal to

$$v = \sqrt{v_x^2 + v_y^2} |_{t=t_0} = 535,1 \text{ м/c}$$.

V. Nikiforov

F1215. In a heat-insulated vessel with a heated interior, 1 kcal and 1 kcal of a fusible substance that is not mixed with water. First, the temperature in the vessel was equal to $-40^\circ\text{C}$, then a heated one consuming constant power was turned on. The dependence of the temperature in the vessel on time is shown in figure. Specific heat of ice $c_\pi = 2 \times$ The presence of a “plateau” (horizontal section) on the graph corresponding to temperature $-20^\circ\text{C}$ indicates that it is at this temperature that the melting of the unknown substance occurs. (Obviously, the “plateau” at $0^\circ\text{C}$ corresponds to the process of ice melting.)

As can be seen from the graph, it took $\tau_1 = 1$ min $= 60$ s to heat the contents of the vessel from the initial temperature $t_1 = -40^\circ\text{C}$ to temperature $t_2 = -20^\circ\text{C}$, while an amount of heat equal to $P\tau_1$ was obtained from the heated object, where $P$ is the power of the heater. Let us write the heat balance equation for this process:

$$(c_\pi + c)m(t_2 - t_1) = P\tau_1$$,

where $m = 1$ kg. To completely melt the substance,
