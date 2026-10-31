---
id: 1974-4-resheniya-zadach-m211-m218-f223-f227-ab171c42
issue: kvant_1974_4
year: 1974
number: "4"
title: Solutions to problems M211—M218; F223—F227
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 34
page_last: 41
page_labels: 32, 33, 34, 35, 36, 38, 39
tag: 8J1S
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6bdd300977fb32491f8750d6f4fa42a684f4243d9640f9703fe92dacce20c463
prompt_sha256: draft-1
translated_from: content/ru/1974/04/articles/08_resheniya-zadach-m211-m218-f223-f227-ab171c42.md
source_content_sha256: 6bd16fa3586f206fc1b48529f3d3ce94e7f273a28c042c94cba0e432b1413305
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 32⟧

F270. In a long test tube, at a distance $l_1$ from the sealed end there is a short mercury pot (Fig. 4). Mass of mercury $m$. At what angular speed o must the test tube be rotated around the vertical axis so that the mercury reaches the end of the test tube? The length of the test tube is $l$, the air temperature in the test tube does not change. Atmospheric pressure is $p_0$.

F271. Calculate the average density $\rho$ of electron charges in the atmosphere if it is known that the directionality of the electron field on the Earth’s surface is 100 $\beta \cdot m^{-1}$, and at an altitude of $h = 1,5$ km this directionality drops to 25 $\beta \cdot m^{-1}$.

Fig. 4.

F272. A matrix of length $l$ (Fig. 5) is suspended from a wall inclined at an angle $\alpha$ to the vertical. The soft tissue was deflected in a plane perpendicular to the wall at a small angle $\beta$ from the vertical position and released. Find the period of vibration of the matrix if $\beta > \alpha$ and the impact of the ball on the wall is absolutely elastic.

Fig. 5.

Problem solutions

M211—M218; F223—F227

M211. Given $n$ points, $n > 4$. Prove that you can connect them with arrows so that each point can be reached in each dish by passing either one arrow or two (every two points can be connected by an arrow in one direction; one arrow in the direction indicated on it).

For $n = 5$ the required graph (the so-called system of points connected by arrows) is represented by figure 1. Now let’s make an inductive transition: we prove that if we can connect $n$ points with arrows as required in the conditions, then we can also connect $n + 1$ points. Let $n$ points be already connected - you get a graph with $n$ vertices. We can assume that any two of these $n$ points are connected by an arrow: otherwise we draw all the missing arrows (directing them in any direction), and the conditions of the problem will be even more fulfilled. Let's denote the new point by $C$.

Let's consider two cases.

a) $n$ — even. Then we divide these $n$ points into pairs. Let the points $A_h B_h$ be one of the pairs ($1 \leq k \leq n/2$) and from $A_h$ there is an arrow to $B_h$. Then we will draw an arrow from $C$ to $A_h$ and from $B_h$ we will draw an arrow to $C$ (see Fig. 2). Let's do this for each pair. A new graph with $n + 1$ vertex is constructed. Let us prove that it satisfies the conditions of the problem. Let $X, Y$ be any two distinct vertices of it. We need to prove that you can get from $X$ to $Y$ by passing one or two arrows. If both $X$ and $Y$ do not coincide with $C$, then this is so by inductive hypothesis. Let $X$ or $Y$ be the same as $C$. Then another of these points ($Y$ or $X$) is included in some pair of those into which we divided the first $n$ points. Thus, $X$ and $Y$ are some two of the three points depicted in figure 2. Looking at this figure, it is easy to go through all the possible options and make sure that the requirement is met.

b) $n$ - odd. In this case, we divide the first $n$ vertices into several pairs and one triple. We follow this as follows. Let's choose any vertex $A_1$. She

⟦folio 33⟧

connected by arrows to all other $n - 1$ vertices: $A_2, \dots, A_n$. At least two arrows come out of $A_1$ or at least two arrows enter into $A_1$. Indeed, otherwise $n$ would be less than four.

Let at least two arrows leave $A_1$ (the other case is similar) and arrive at vertices $A_2, A_3$. We will divide the remaining vertices into pairs. Now we connect the new vertex with arrows to the triple $A_1, A_2, A_3$ - as shown in figure 3, and with all the pairs - as shown in figure 2. As in case a), it is easy to prove that the resulting graph satisfies the conditions of the problem. The inductive transition is legal. So, we have proven by induction that $n$ points can be connected as required in the condition, with $n \geq 5$. If you understand the proof, then you can easily understand the following paradox. For $n = 3$ the required graph also exists (Fig. 2), but for $n = 4$ there is no such graph (this can be easily verified by enumeration). But, applying the induction transition to the special case $n = 3$, we obtain: if such a graph exists for $n = 3$, then it also exists for $n = 4$. The result is a contradiction *). What's the matter?

**M212. At the trial, 14 coins were presented as evidence. The expert discovered that seven of them were file ones, the rest were abbots, and he found out which ones were file ones and which ones were abbots. The court only knows that file coins weigh the same, the original coins weigh the same and the file lese coins weigh the same. The expert wants the time of weighing on cup scales without digital judgment, that all the file coins he discovered are indeed file coins, and the rest are originals. Can he do it?

Figures 4, a, b, c show by what weightings an expert can convince the court that coins $\Phi_1, \Phi_2, \dots, \Phi_7$ are file coins, and $H_1, H_2, \dots, H_7$ are real coins. Each time the right cup moves, and this is only possible if there are more file coins on the left cup than on the right (and there are more infusions on the right than on the left).

This method is easy to generalize, and then the fact that the data $n$ coins are file ones, and the others $n$ are real, can be proven by performing $[\log_2 n] + 1$ weighing. Despite the fact that such a weighing system is very economical (at $n = 1000$ 10 weighings are enough), we cannot prove that it is optimal. It would be interesting to prove that the minimum weighting number still grows without limit as $n \rightarrow \infty$ (or to disprove this).

**A. L. Toom**

*) Almost like in §§ 2 and 3 of M. Milg’s article “What the Guide Said” («Kvant», 1973, No. 8).

**M213. Given a node with vertex O and a circle tangent to its line in monks A and B. A ray is drawn from point A parallel to OB,**

Fig. 4.

⟦folio 34⟧

intersecting the circle at point C. The segment OC intersects the circle at point E, and lines AE and OB intersect at point K. Prove that OK = KB.

We have obtained many different solutions to this problem, which use theorems on tangents and secants, on subtriangles, on inscribed angles, etc. Let us present one of the shortest and most beautiful ones.

Let's draw a tangent to the circle at point C; let P and N be its intersection points on the AO and OB sides of the angle AOB (Fig. 5). It is clear that PB is the symmetrical axis of triangle OPN, so all four tangents are equal:

$$OA = OB = BN = CN.$$

Triangles NOC and OAK are similar because

$$\angle CNO = \angle AOK, \angle NOC = \angle ACO = \angle OAK$$

(each of the last two angles is measured by the irrigation arc AE). From here

$$\frac{OK}{OB} = \frac{OK}{OA} = \frac{CN}{ON} = \frac{1}{2}.$$

**M214. The square triangle f(x) = ax^2 + bx + c poppies means that the equation f(x) = x has no real roots. Prove that the equation f(f(x)) = x also has no real roots.**

This problem can be solved purely algebraically, using the fact that if f(x) is a polynomial, then f(f(x)) - x is always divisible (as a polynomial) by f(x) - x, that is

$$f(f(x)) - x = (f(x) - x)g(x).$$

Here g(x) is a polynomial of the second degree. Simple calculations show that the discriminant of this polynomial is negative. Most readers, however, contributed a more colorful solution, using visual messages associated with graphs.

The condition that the equation f(x) = x has no real roots means that the parabola y = f(x) is located entirely above or entirely below the straight line y = x (Fig. 6). In other words, for all x

$$f(x) > x,$$

but then for all x

$$f(f(x)) > f(x) > x,$$

or for all x

$$f(x) < x,$$

and then for all x

$$f(f(x)) < f(x) < x.$$

Thus, in general cases the equation f(f(x)) = x has no solutions.

**M215. On an infinite checkered sheet of white paper, n cells are colored black. At moments of time t = 1, 2, ... let us perform a simultaneous recoloring of all cells of the sheet according to the following rule: each cell k acquires the color that most of the three cells had at the previous moment: the cell k itself and its neighbors to the right and above (if two or three of these cells were white, then k becomes white, if two or three of them were black), and Prove that after a finite time there will be no black cells left on the sheet.

b) Prove that black cells will disappear no later than at time t = n.

Let H be some set of black cells. Let us denote by the letter Γ (from the word “heading”) the recoloring operator, that is, by Γ (Ч) we will denote the set of cells that are obtained from the number, by Γ²(Х) we will denote the set Γ(Γ(Ч)), in which the number is transferred in two steps, by Γ³(Ч) in three steps, etc. (see Fig. 7; by the way, this figure refutes the assumption that the total number of cells in Γ(H) is always less than in H).

Statement a) follows immediately from two such venerable sentences.

(1) If more black cells are added to the set Γ, then black cells can also only be added to the set Γ(Н), but none will be lost. Using the sign ⊆(A ⊆ B) means that the set A is entirely contained in B, in part, it can

⟦folio 35⟧

coincide), it can be written like this:

$$\chi \subset \chi' \Rightarrow \Gamma(\chi) \subset \Gamma(\chi')$$

(2) If $\chi_0$ is the set of all cells inside a square on checkered paper (consisting of $N$ cells), then after a finite number of steps nothing will remain from $\chi_0$ (Fig. 8); more precisely, after $(2N-1)$ steps you will get an *empty* set of black cells:

$$\Gamma^{2N-1}(\chi_0) = \varnothing$$

It is clear that any set $\chi$ can be enclosed in a sufficiently large square $\chi_0$; according to (2) this black square $\chi_0$ will “die out” in a finite number of steps, and according to (1) any $\chi$ cannot exist longer than $\chi_0$. Thus, problem a) is solved.

Proving 6) is much more difficult.

Let us present the solution to problem 6), invented at the Olympiad by tenth-class student A. Gomilko from Khmelnitsky (for this he received a special prize).

By the way, the fact that solution 6) cannot be very simple is shown by the many examples of $n$ cells dying out in exactly $n$ steps (Fig. 9).

Let us prove statement 6) by induction on $n$—the number of cells in the initial set $\chi$; for $n = 1$ it is obvious.

Let it already be proven that if there are less than $n$ cells in $\chi$, then

$$\Gamma^{n-1}(\chi) = \varnothing$$

Let us now consider $\chi$, consisting of $n$ cells. Let's enclose it in a right angle $x \geq 0$, $y \geq 0$ (the coordinate axes $Ox$ and $Oy$ are directed to the right and up along the grid lines, the side of the cell is equal to 1) so that in the strip $0 \leq x \leq 1$ there is at least one black cell and in the strip $0 \leq y \leq 1$ - too (Fig. 10).

Let $\chi^1$ be the part of $\chi$ lying in the half-plane $x \geq 1$. By the induction hypothesis, $\Gamma^{n-1}(\chi^1) = \varnothing$. And the cells from $0 \leq x \leq 1$ have no effect on what happens above the line $x = 1$. Consequently, $\Gamma^{n-1}(\chi)$ lies entirely in the strip $0 \leq x \leq 1$ (obviously, in

⟦folio 36⟧

HALF-PLANES $x < 0$ black cells cannot be reflexive).

In the same way it is proved that $\Gamma^{n-1}(\Upsilon)$ is contained in the strip $0 \leq y \leq 1$. It follows that $\Gamma^{n-1}(\Upsilon)$ can contain at most one cell: $0 \leq x \leq 1$, $0 \leq y \leq 1$ and therefore $\Gamma^n(\Upsilon) = \emptyset$.

N. B. Vasiliev

**M216.** $N$ people do not know each other. You need to introduce dtype to some of them so that no three people have the same number of acquaintances. Prove that this can be done for any $N$.

Let's solve the problem using the method of mathematical induction. For $N < 3$ the statement of the problem is obvious.

Let us assume that we are able to introduce $k$ people, so that no three of them have an equal number of acquaintances. Let's add $k+1$th. Let us indicate a way to introduce the $(k+1)$th person so that in a group of the $(k+1)$th person, no three people still have an equal number of acquaintances. If among the first $k$ people there is a person who knows everyone else, then $k+1$ will not introduce anyone to anyone. If there is no such thing, then we will introduce the $(k+1)$th to everyone.

In the first case, $(k+1)$th has no acquaintances, and each of the others has at least one acquaintance - the one who was familiar with everyone. In the second case, $(k+1)$ has $k$ acquaintances, the number of acquaintances of each of the first $k$ people increased by one, but none of them had $k$ acquaintances.

figure 11 shows dating patterns for $k=6$ obtained in the described way.

There are many other solutions to this problem. For example, if we number $n$ people with numbers from 1 to $n$ and introduce $i$ to $j$, if

$$|i-j| \leq \frac{n}{2},$$

then only pairs of people with numbers $k$ and $n-k$ have an equal number of acquaintances (with

⟦folio 38⟧

Let's find out how the speed of the ship changes over time.

Since $m\Delta v = F\Delta t$ and $F = -kv$, then
$$\frac{\Delta v}{\Delta t} = -\frac{k}{m} v.$$

We found that the rate of change of the ship's speed is proportional to the speed itself. But, as is known (see, for example, the article by S. D. Osyatinsky and L. Z. Rumshinsky “Exponenta”, «Kvant», 1972, No. 12), if a change in any quantity is proportional to this quantity itself, then such a quantity changes according to an exponential law, therefore

$$v = v_0 e^{-\frac{k}{m} t}.$$

From this formula it follows that $v = 0$ at $t \to \infty$. That is, the ship could travel the path $s_2$ in an infinitely long time! This means that the second question of the problem under condition $F \sim v$ should be clarified. We will consider that the body has stopped if its speed has decreased, for example, by a thousand times (the number can, of course, be different; it all depends on the goals of the experiment).

F224. Along wooden skids forming an angle $\alpha$ with the horizon, holding the box by the rope. The coefficient of friction between the box and the tool is $\mu$. At what angle to the horizon should the rope be directed so that with the least number of boxes being stuck in: a) uniformly, b) with a given acceleration $a$?

Let's consider the forces acting on the box (Fig. 14). These are the gravitational force mg, the tension force of the rope F, the reaction force N and the friction force F_Tp, the value of which is F_Tp = μN. Let's project all the forces in a direction along and perpendicular to them and write down the corresponding equation of motion.

Since the box does not move in the direction perpendicular to the skordi, the sum of the projections of forces on this direction

$$\text{Рис. 14}$$

must be equal to zero, that is
$$N + F \sin(\beta - \alpha) - mg \cos \alpha = 0.$$ (1)

Along the skodney the box moves with acceleration $a$ (in some cases with uniform motion $a = 0$), therefore the sum of the projections of forces must be equal to ma:

$$F \cos(\beta - \alpha) - mg \sin \alpha - \mu N = ma.$$ (2)

From equations (1) and (2)

$$F = \frac{ma + mg(\sin \alpha + \mu \cos \alpha)}{\cos(\beta - \alpha) + \mu \sin(\beta - \alpha)}.$$ (3)

In the resulting expression for the force F, the angle $\beta$ is included only in the significant factor. Consequently, the magnitude of the force F will be minimal at such a value of the angle $\beta$, at which the value in formula (3) is maximum, that is, the maximum equation of motion.

$$\cos(\beta - \alpha) + \mu \sin(\beta - \alpha).$$

Let's make some transformations. Let's imagine the friction coefficient $\mu$ as the tangent of some angle $\gamma$:

$$tg \gamma = \mu; \quad \gamma = \arctg \mu;$$

$$\sin \gamma = \frac{\mu}{\sqrt{1 + \mu^2}}; \quad \cos \gamma = \frac{1}{\sqrt{1 + \mu^2}}.$$

Then we can write:

$$\cos(\beta - \alpha) + \mu \sin(\beta - \alpha) = \sqrt{1 + \mu^2} \cos(\beta - \alpha - \gamma).$$

After it, the expression is maximum and equal to $\sqrt{1 + \mu^2}$ at $\beta - \alpha - \gamma = 0$, that is, at $\beta = \alpha + \gamma = \alpha + \arctg \mu.$ (4)

With this value of the angle $\beta$ and the minimum force F. Moreover, if the box moves uniformly ($a = 0$), then

$$F_{\min} = \frac{mg(\sin \alpha + \mu \cos \alpha)}{\sqrt{1 + \mu^2}},$$

and when moving with acceleration $a$

$$F_{\min} = \frac{ma + mg(\sin \alpha + \mu \cos \alpha)}{\sqrt{1 + \mu^2}}.$$

However, this solution is not true for any acceleration. Since the direction of the force F does not depend on $a$, and the absolute value of the force F increases with increasing acceleration, then at a certain value of acceleration $a = a_0$ the force F becomes such that its component $F \sin(\beta - \alpha)$, perpendicular to the inclined plane, will be equal in absolute value to the gravity component $mg \cos \alpha$. In this case, both the force N and the force $F_{\text{Tp}}$ will vanish. Subsequently (at $a > a_0$), in order not to break away from the positions, the direction of force F should be less with increasing acceleration $a$ so that the component of force F, perpendicular

⟦folio 39⟧

to the inclined plane, remained equal to the component of the gravity force, that is
$$F \sin(\beta - \alpha) = mg \cos \alpha.$$
For the components of these forces parallel to the inclined plane, we can write
$$F \cos(\beta - \alpha) = mg \sin \alpha = ma.$$
From the last two equalities we find:
$$tg(\beta - \alpha) = \frac{g \cos \alpha}{g \sin \alpha + a},$$
where
$$\beta = \alpha + arctg \frac{g \cos \alpha}{g \sin \alpha + a}.$$
The value $a_0$ can be found from those messages that at $a = a_0$ the value of the angle $\beta$ from (4) and (5) coincides:
$$\alpha + arctg \frac{g \cos \alpha}{g \sin \alpha + a_0} = \alpha + arctg \mu,$$
where
$$a_0 = g \left( \frac{\cos \alpha}{\mu} - \sin \alpha \right).$$
So,
at $a \leq a_0$ (hence, at uniform motion too)
$$\beta = \alpha + arctg \mu,$$
at $a > a_0$
$$\beta = \alpha + arctg \frac{g \cos \alpha}{g \sin \alpha + a}.$$
We solved the problem. However, we will give one more solution. This is a beautiful geometric solution.
With uniform motion along the gangway, the sum of all forces must be equal to zero. Let's replace the forces $N$ and $F_{TP}$ with their equivalent $Q = N + F_{TP}$ (Fig. 14) and add the forces $Q$, $F$ and $mg$. They should form a closed triangle.
Note that the direction of the force $Q$ makes an angle $\delta$ with the perpendicular to the inclined plane such that
$$tg \delta = \frac{F_{TP}}{N} = \frac{\mu N}{N} = \mu,$$
that is, when the magnitude and direction of the force $F$ changes, the direction of the force $Q$ remains unchanged. Consequently, the absolute value of the vector $F$ will be minimal if it is perpendicular to the vector $Q$ (Fig. 15) (since the magnitude and direction of the vector $mg$ do not change). In this case, $F$ will make an angle with the force horizon
$$\beta = \alpha + \delta = \alpha + arctg \mu$$
(angles $\beta$ and $\alpha + \delta$ are equal as angles with mutually perpendicular sides).
The problem is solved in exactly the same way when the box moves with acceleration $a < a_0$. In this case, the sum of the vectors $mg$, $Q$ and $F$ must equal $ma$ (Fig. 16). This will change the absolute magnitude of the force $F$, but will not change its direction.
At $a > a_0$, when the forces $N$, $F_{TP}$, $a$, and therefore $Q$ are equal to zero, the force $F$ must connect the ends of the vectors $mg$ and $ma$ (Fig. 17). It is easy to see that in this case
$$\beta = arctg \frac{g + a \sin \alpha}{a \cos \alpha} = \alpha + arctg \frac{g \cos \alpha}{g \sin \alpha + a}.$$
F225. There are two non-displaceable liquids in the juice: carbon perchloride $CCl_4$ and water. At normal atmospheric pressure, $CCl_4$ boils at $76,7^\circ \text{C}$, water at $100^\circ \text{C}$. When the relish is uniformly heated in a water bath, boiling at the liquid interface occurs at a temperature of $65,5^\circ \text{C}$. Determine which liquid boils quickly at the maximum “borderline” boiling point and by how much. The saturated vapor pressure of water at $65,5^\circ \text{C}$ is 192 mm rm. cm.
For a homogeneous liquid to boil, it is necessary that the saturated vapor pressure in the bubbles formed throughout the entire volume of the liquid be equal to the external atmospheric pressure *).
During “borderline” boiling, the bubbles located at the boundary of water and carbon tetrachloride contain:
*) In reality, the saturated vapor pressure should be greater than atmospheric pressure by an amount $\Delta p = \rho gh + \frac{2\sigma}{R}$, where $\rho gh$ is the hydrostatic pressure at a depth $h$, $\frac{2\sigma}{R}$ is the additional pressure under the curved surface of the liquid (σ is the surface tension coefficient, $R$ is the radius of the bubble). Obviously this value can be converted in comparison with external atmospheric pressure.
