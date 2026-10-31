---
id: 1970-10-resheniya-3e2ec111
issue: kvant_1970_10
year: 1970
number: "10"
title: '[Solutions to problems M8—M10; F12—F17]'
rubric: zadachnik-kvanta
page_first: 40
page_last: 53
page_labels: 38, 39, 40, 41, 42, 43, 44, 45, 46, 47, 48, 49, 51
tag: P5Q0
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2130dcf1a74918b46d6e5f5294dbb96f3cbfa6a9d6cdfd9d7c82aa77c287051b
prompt_sha256: draft-1
translated_from: content/ru/1970/10/articles/07_resheniya-3e2ec111.md
source_content_sha256: 0ef88b8966c3094f1ac04f975f54fe5dc86ca729ad939639031822e8480e438c
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 38⟧

M8. Two people play this game. From a pile of 25 matches, everyone takes one, two or three matches in turn. The winner is the one who at the end of the game - after all the matches have been sorted out - has an even number of matches.

Who wins when played correctly - the beginner or his partner? How should he play to win? How will the answer change if we assume that the one who wins an odd number of matches wins?

Explore this game in the general case when there are 2n+1 matches and you are allowed to have any number of matches from 1 to m.

Solution

In order to talk about a game, it is necessary to somehow name its parts. Conditions once and for all call one of them I, and the other He.

First of all, let us slightly generalize the conditions of the problem. The number N of matches lying on the table at the beginning of the game can be any, not just odd. Moreover, for four N one of the players if at the end of the game the total number of matches is four, and the other if the number of matches is odd.

We are considering, strictly speaking, an infinite number of games at once, since N and m can be any natural numbers. Further, if m and N are given, two options are possible: I won if at the end of the game I have 1) an even, 2) an odd number of matches.

Let's first talk about all the variants of this game together.

Let's think about what the player needs to remember during the game. Does he need to remember all his and his opponent's moves from the beginning of the game? No, in any case, it is enough for him to know the following:

1) how many matches are left on the table,
2) Does it have an even number of matches?
3) whose move?

If these three parameters are given, then we will say that given the state, the player can make m different moves (or less if there are fewer than m matches left on the table). Each of his moves moves the game to a different state when his partner moves.

It is convenient to depict the states of the game on paper in the form of a cell or circles, and possibly moves in the form of arrows. That's what we'll do.

The table at figure 1 is compiled for the case when m=2 (there can only be one or two matches per turn),

In the tables in Figures 1-4:
Column I - line number m, shows how many matches are left on the table.
Column II - I have an even number of matches, my move.
Column III - I have an even number of matches and its course.
Column IV - I have an even number of matches, my move.
Column V - I have an even number of matches and its move.

⟦folio 39⟧

Fig. 1. Table of possible states and moves of the game with $m=2$.

and I win if at the end of the game I have an even number of matches. In fact, only those states are drawn when there are no more than seven matches left on the table.

Colored arrows show how players can move: a player whose turn is in that cell can follow any arrow coming out of it. For example, the first glory cell in the building with number 5 (gray) corresponds to the state of the game when there are 5 matches left on the table, I have an even number of matches and my move, and the two arrows coming out of this cell show which states I can transfer the game to with my next move.

The table can be continued visually and we will put the letter B in the cell according to it, if when the game starts from this state, I can win, no matter how much He tries to put me in a position.

Let's call the state disruptive and put the letter P in the cell corresponding to it, if when the game starts from this state, He can win and, if He doesn't make a mistake, I won't be able to prevent this.

Let us now proceed to the main part of the solution: we will place the letters B and P in all cells of the table. We will do this first for the game corresponding to figure 1. In the zero line, the letters, of course, must be placed like this: VVP, since we consider that I won if at the end of the game I have an even number of matches. Next, the letters must be arranged from top to bottom according to the following law.

I. If it’s my move (that is, the cell is in the II or IV column), then the following is placed in it:

the letter B, if at least one arrow from it leads to the cell with the letter B;

the letter P if every arrow coming from it leads to a cell with the letter P.

II. If it is his move (that is, the cell is in the III or V column), then the following is placed in it:

the letter P if at least one arrow from it leads to the cell with the letter P;

the letter B if every arrow coming from it leads to the cell with the letter B.

Since all the arrows in the table lead from bottom to top, this law makes it possible to fill out the entire table, no matter how much we use it.

In our case ($m=2$), in order to fill the cells of the $n$th row, it is enough to know only how to fill the cells of the $(n-1)$th and $(n-2)$th rows. In fact, there is no need at all to draw all the arrows, as in figure 1. It is enough to separately (on a piece of tracing paper) draw a “template” - a set of arrows coming out of the cells of one line, and, applying this template in turn to all the rows of the table, fill them with the letters B and P, following the rules written on the head background. figure 2 shows the moment when we filled out all

⟦folio 40⟧

Fig. 2. Table of winning and losing states of the game with $m=2$.

table up to the 5th line and are ready to fill out the 6th. This way you can fill the table to any place, for example to the 25th line and see which letter will appear in the first place in the 25th line. If it is B, then the player who starts the game with 25 matches on the table will win, but if it is P, then he will lose.

In fact, let's say there is no need to fill out the table. The fact is that the 4th line coincides with the zero, and the 5th with the first. Therefore, the 6th necessarily coincides with the 2nd (since each line is determined by the two previous ones). Then the 7th line coincides with the 3rd, the 8th with the 4th, the 9th with the 5th, etc. The lines will be repeated with a period of 4, which means that any line with the number 4 $k$ will be a VVP;
line numbered $4k+1$ will be PVVP;
line numbered $4k+2$ will be VPVP;
line numbered $4k+3$ will be VPVP.

Specifically, the 25th line will be PVVP ($25=4\cdot 6+1$).

The fact that there must necessarily be a period could have been foreseen in advance. Indeed, let us fill the table up to some line. Then everything depends on how the last two lines are filled in. The number of all ways to fill two lines with the letters P and B is finite (it is complete at most $2^8$). This means that when filling a table, a new pair of rows cannot appear all the time. And when a couple of lines are repeated, periodicity begins.

After the letters B and P are placed in the table, the strategy that I must follow in order to win becomes clear: every time I need to make a move that leads to the cell with the letter B. The law for arranging the letters B and P, indicated above, is designed precisely in such a way that if I once got into cell B, then I can then move to B every time, and the enemy will not be able to interfere with me.

Listen, when I winvio, if I have an odd number of matches at the end, it is examined in a similar way. You can put PPVV in the zero line and fill out the table further according to the same law. Period will again be equal to 4. But you can not do all this, but use the same figure 2 for this case.

Note that not giving a player anything before the start of the game and requiring him to have an odd number of matches at the end is the same as giving him one match before the start of the game and requiring him to have an even number of matches at the end of the game. Thus, in this new case I have won if in the table there are figure 2 in the cell at the intersection of the $N$th row and

Column IV is B, if I start,

Column V is B if He starts.

Note also that the pattern will not change if you swap column P with IV, and column III with V. In the first row after such a rearrangement, VPVP will be PPVV. Therefore, the table for the case when I must have an odd number of matches to win can be obtained from the table for the case analyzed by the indicated rearrangement of columns. The same applies to all other values ​​of $m$.

Let now $m=3$. The table will still consist of the same

⟦folio 41⟧

Fig. 3. Table for the game with $m=3$.

four columns. The pattern will change (see Fig. 3). Now each line depends on the previous three lines. To arrange the letters B and P, the rule written out on page 39 is applicable. By arranging the letters, we make sure that the period consists of eight lines. In particular, the 25th line is the same as the first: PVVP.

Thus, in the case of $m=3$ and $N=25$ it turns out like this

Answer: if the winner is the player who took an even number of matches, then the starter loses, and if the player who took an odd number of matches is considered the winner, then the starter wins.

The general case is studied in a similar way. The length of the period turns out to be $m+2$ if $m$ is even, and $2m+2$ if $m$ is odd. These periods are depicted in Figures 4 a, b. The patterns given for $m=8$ and $m=9$ provide insight into what the patterns would be in the general case. It was inconvenient to draw arrows here. Cells shaded with each color represent the state in which a player can move from a cell containing a dot of the same color. The rules for arranging the letters B and P are the same, written out on page 39. Checking that the periods are dividing

⟦folio 42⟧

We will leave this evidence to the reader. Let us only note the following. To be sure that the period will repeat, you need to check the placement of letters in all lines of the first period and in the first m lines of the second period.

As we see, with large m, the part of everything we sew on is what we withstand. All letters that violate this rule are circled in Figures 4, a, b. So, the sewer is processed by molley in the following cases.

| period | The one who scores “even” wins | The one who scores “odd” wins. |
| :--- | :--- | :--- |
| m is even | N leaves remainder 1 when divided by m+2 | N gives remainder m+1 or 0 when divided by m+2 |
| m odd | N gives remainder 1 or m+1 when divided by 2 m+2 | N gives remainder 0 or m+2 when divided by 2 m+2 |

**M9. Consider the following properties of a tetrahedron (we call an arbitrary triangular paramid a tetrahedron):**
1) all faces are equal in size;
2) each edge is equal to the opposite;
3) all edges are equal;
4) the centers of the circumscribed and inscribed spheres coincide;
5) the sums of plane angles at each vertex of the tetrahedron are equal.
Prove that all these properties are equivalent.
Try to find other equivalent properties of the tetrahedron.

Solved and e. In this problem it is very important to choose a rational way of proof: to figure out which property is easier to deduce from which. We will, as is customary, put an arrow along with the words “from... it follows...”: ⇒

It is convenient for us to add a few more properties of the tetrahedron:

6) the sum of plane angles at each vertex is 180°;
7) the development of the tetrahedron is represented by an acute triangle in which the middle lines are drawn (Fig. 5);
8) all faces are acute triangles with the same radius of the circumscribed circle;

Fig. 4, 6. Table for the game with odd m and template for m=9.

⟦folio 43⟧

Fig. 5.

9) projection of a tetrahedron onto each of three planes parallel to two opposite edges - a rectangle -

and prove that properties (1)–(9) are equivalent, in this order:

Most of the twelve theorems, indicated by arrows here, are almost obvious. Let's prove them in order.

(5) ⇒ (6). The sum of all plane angles of all faces of a tetrahedron is equal to the sum of the angles of four triangles, that is, $4 \cdot 180^\circ = 720^\circ$, therefore, if the sums of the angles at each vertex are equal, then each of them is equal to $180^\circ$. The converse: (6) ⇒ (5) is obvious.

(4) ⇒ (8). If $R$ is the radius of the sphere circumscribed about the tetrahedron, $r$ is the radius of the circumscribed sphere and the centers of these spheres coincide, then the point of contact of the sphere with each edge lies inside this face and is distant from each vertex of the tetragon by $\sqrt{R^2-r^2}$, that is, it is the center

Fig. 6.

a circle of radius $\sqrt{R^2-r^2}$ described around this triangle.

(8) ⇒ (4). It is clear that in any tetrahedron the perpendiculars dropped from the center $O$ of the circumscribed sphere on the face fall into the centers of the circumscribed circles, and if the radii of all these circles are equal $R_1$, then the point $O$ is equally distant from all faces (at a distance $r = \sqrt{R^2-R_1^2}$). If the bases of the perpendiculares lie inside the faces, then $O$ is the center of a circumscribed sphere of radius $r$.

(8) ⇒ (6). If the radius of the circumscribed circles of the faces $ABC$ and $DBC$ of the tetrahedron $ABCD$ are equal, then $\angle BAC = \angle BDC$, since these angles rest on equal others $BC$ in equal circles (here it is important that $\triangle BAC$ and $\triangle BDC$ are acute-angled!). This also applies to all other parameters of adjacent faces.

Thus, $\angle BDC + \angle CDA + \angle ADB = \angle BAC + \angle CBA + \angle ACB = 180^\circ$ and similarly for all other vertices.

(6) ⇒ (7). The development of an arbitrary tetrahedron $ABCD$ is a hexagon $D_1AD_2BD_3C$, divided into four triangles (Fig. 6). Obviously, from (6) it follows that the segments $D_1A$ and $AD_2$, $D_2B$ and $BD_3$, $D_3C$ and $CD_1$ lie on the same straight line, that is, the points $A$,

⟦folio 44⟧

B and C are the midpoints of the sides $\Delta D_1D_2D_3$ (as on Fig. 5). This triangle is acute, since in the triangular angle of the tetrahedron (at vertex D) each of the plane angles is less than the sum of the other two.

(9) $\Rightarrow$ (7), (7) $\Rightarrow$ (8) and (7) $\Rightarrow$ (2) are very significant. (2) $\Rightarrow$ (3) also very different (triangles are equal on three sides); (3) $\Rightarrow$ (1) very.

It remains only to prove that (1) $\Rightarrow$ (9). This place turned out to be the most difficult for readers.

(1) $\Rightarrow$ (9). Note that if $p_1$ and $p_2$ are parallel planes, AK and BH are two segments whose ends A and B lie in the $p_1$ plane, and the ends K and H lie in the $p_2$ plane, then the segments AK and BH are equal if and only if their projections onto the $p_1$ plane are equal (or $p_2$). This is easily proven using the Pythagorean theorem (Fig.7).

Let us draw parallel planes $p_1$ and $p_2$ through the edges AB and CD of the tetrahedron. Let $C_1$ and $D_1$ be the projections of points C and D onto the plane $p_1$ (Fig. 8, a), O the intersection point of $C_1D_1$ and AB. If the areas $\triangle CAD$ and $\triangle CBD$ are equal, then the heights AK and BH of these triangles are equal, therefore, the projection of these heights onto $p_1$ is equal: AK$_1$ = BH$_1$, and therefore AO = OB (Fig. 8, b), it follows, in particular, that points A and B lie on opposite sides of the line C$_1$ D$_1$. Similarly, the plane of area $\triangle ACB$ and $\triangle ADB$ are equal, C$_1O$ = D$_1O$. Therefore, AC$_1BD_1$ is a parallelogram, that is, AC$_1$ = BD$_1$ and C$_1B$ = D$_1A$, whence AC = BD and BC = AD. In the same way it is proved that AB = CD, so AC$_1BD_1$ is a right angle.

M10. Four circles, the centers of which are the vertices of a convex quadrilateral, completely cover this quadrilateral. Prove that from them it is possible to choose three circles that cover a triangle with vertices at the centers of these circles.

Solution. The main difficulty in this task is to come up with a deconstruction that would cover all possible cases.

Fig. 7.

Fig. 8, a. Tetrahedron in space.

Fig. 8, b. Projection of a tetrahedron onto a plane.

⟦folio 45⟧

Fig. 9.

arrangement of circles and all possible quadrilateral shapes.

The idea of ​​the solution given below belongs to N. Vasiliev.

Let us denote the circles with centers A, B, C, D at the vertices of a given quadrilateral ABCD by Kₐ, Kₑ, K₃, K₄, and their radii by rₐ, rₑ, r₃, r₄. Let's assume that the problem statement is false. Then each circle has a common point with the part of the triangle assigned to it that is not covered by triangles:

for example, Kₐ must contain points △BCD, none are covered

Fig. 10.

from circles Kₐ, Kₑ, K₃, K₄. Let O be the point of intersection of the diagonals. Let us prove, under our assumption, that rₐ ≥ OA, that is, that the circle Kₐ contains the point O. The rest is already clear: in the same way it will be possible to prove that the point O belongs to Kₐ and K₃, and from here it obviously follows that these circles cover △ABC. Look at figure 9,10: if OL and ON are perpendiculars dropped onto lines AB and BC, then Kₐ covers △OAL, K₃ - △OCN, K₄ - △OBL and △OBN, and these four right triangles cover △ABC, even if

Fig. 11, a.

Fig. 11, b.

⟦folio 46⟧

one of the triangles AOB or OBC (as in figure 10) is obtuse.

We come to a contradiction with our assumption; therefore, the statement of the problem is correct.

So, it remains to prove that $r_A \geqslant OA$. We will need the following, almost obvious one.

Lemma. Let a convex quadrilateral PQRS and a circle $K_R$ (not containing $\triangle PQR$ entirely) be given. Then, of all the points lying inside $\triangle PQR$ and outside $K_R$, those close to the point $S$ will be:

a) the base $F$ perpendicular $SF$ dropped from the point $S$ to the line $PR$, if this point $F$ lies outside the circle $K_R$ (Fig. 11, a);

b) point $E$ of intersection of circle $K_R$ with segment $PR$, if point $F$ lies inside circle $K_R$ (Fig. 11, b). (It is important here that the QRS angle of the quadrilateral is less than $180^\circ$; we leave the proof of the lemma to the reader.)

We can assume that $\angle AOB \leqslant 90^\circ$ (otherwise we would take not $B$, but $D$). Let $BB_1 \perp AC$; $AA_1 \perp BD$; $B_1A_2 \perp BD$ (Fig. 12). Suppose that $r_A < OA$ and $E - \text{ближайшая } K$ are on the segment $OA$ and $AE = r_A$, $EM - \text{перpendикуляр}, \text{опущенный } E$ on $BD$. It is clear that then $AM > AE$. Let us prove that, nevertheless, $r_A > AM$, it will follow that our assumption ($r_A < OA$) is incorrect.

Let us first prove that $r_B > BM$. Let us apply the lemma to $\triangle ACD$, the circle $K_A$ and the point $B$. Distance two cases:

a) $E$ lies between $A$ and $B_1$. Then $r_B > BB_1 > BA_2 \geqslant BM$;

b) $E$ lies between $O$ and $B_1$. Then (by lemma)

$$r_B > BE > BM.$$

So we know that the point $M$ belongs to $K_B$. Applying the lemma to $\triangle BCD$, the circle $K_B$ and the point $A$ (note that $M$ lies between $O$ and $A_1$, so case 6 always holds)), we obtain $r_A > AM$. The circle is closed, we demand a contradiction.

F12. Two identical heavy steel balls rotate on light rods of length $l$ and $2l$ around the point $O_1$, $O$, the distance between which is 3$l$ (Fig. 13). At the initial moment, the balls are at points $A$ and $B$, having speeds $v$ and $2v$, respectively. How many times will the balls collide in time $t$? How long will it take for the balls to collide $k$ times? The coduar balls are considered to be absolutely elastic.

Solution. Since the balls are identical, during absolutely elastic collisions they will exchange velocities. This follows from the laws of conservation of energy and momentum (number of movements) of balls upon collision. The first time the balls collide is when each of them makes half a revolution around the point about which it is spinning.

This will take time $t_1 = \frac{\pi \cdot 2l}{2v} = \frac{\pi l}{v}$. After the collision, the left ball will have a speed of $2v$, and the right ball will have a speed of $v$.

The second collision of the balls will occur in time $t_2 = \frac{4\pi l}{v}$ after the first, when the right ball makes one revolution around the point $O_1$. During this time, the left ball will make four revolutions around the point $O$ - it has twice the speed, and it rotates around the circle in half the time

⟦folio 47⟧

Fig. 13.

shero radius. Upon collision, the balls will again exchange velocities, and the third collision will occur in time $t_3 = 2t_1 = \frac{2\pi l}{v}$ after the second, when each of the balls has completed one revolution. Thus, after each odd collision, the left ball will have a speed of $2v$, and the right ball will have a speed of $v$, and therefore the next, even, collision will occur after a time of $t' = t_2 = t_4 = \cdots = \frac{4\pi l}{v}$.

After each odd collision, the left ball will have a speed of $v$, and the right one will have a speed of $2v$, and the next, now odd, collision of the balls will occur after a time $t'' = 2t_1 = t_3 = \cdots = \frac{2\pi l}{v}$ after the even one.

Now it is easy to calculate that if $k$ is an even number, then the $k$-th collision of the balls will occur in time
$$t_k = \left( \frac{k}{2} - \frac{1}{2} \right) t'' + \frac{k}{2} t' = (3k - 1) \frac{\pi l}{v},
$$
since in total there will be $\frac{k}{2}$ even collisions between the balls and $\frac{k}{2}$ odd ones. This means that the right ball must make $\frac{k}{2} - \frac{1}{2}$ revolutions, having a speed of $2v$ (here we taught that before the first collision the ball makes only half revolutions) and $\frac{k}{2}$ revolutions around point $Q_1$, having a speed of $v$.

If $k$ is odd, then before the $k$-th collision the right ball must make a speed of $v$ and $\frac{k-1}{2} + 1 - \frac{1}{2} = \frac{k}{2}$ revolutions, having a speed of $2v$. Therefore, from the initial moment to the moment of the $k$-th collision in this case, time must pass
$$t_k = \frac{k}{2} t'' + \frac{k-1}{2} t' = \frac{(3k-2)\pi l}{v}.$$

Let us now calculate how many times the balls will collide in time $t$. We will assume that $t > t_1$. Between two consecutive odd collisions of balls, time $t_0 = t' + t''$ passes. There will be as many odd collisions after the first as how many times $t_0$ will collide in $t - t_1$:

$$n = \left[ \frac{t - t_1}{t_0} \right]$$

(the [ ] sign means “integer part of a number”).

A total of $n+1$ odd collisions will occur between the balls. The time elapsed before the last odd collision will be equal to $\left[ \frac{t - t_1}{t_0} \right] t_0 + t_1$.

During this time, $n$ even collisions should occur between the balls. Additionally, if the remaining time $t - \left( \frac{t - t_1}{t_0} \right] t_0 + t_1$ is greater than $t'$, then another odd collision will occur. Thus, in time $t$ the balls will collide

$$N = \left[ \frac{t - t_1}{t_0} \right] + 1 + \left[ \frac{t - t_1}{t_0} \right] + \left[ \frac{t - \left[ \frac{t - t_1}{t_0} \right] (t_1 + t_2)}{t_2} \right] = 2 \left[ \frac{vt - \pi l}{6\pi l} \right] + \left[ \frac{vt - \left[ \frac{vt - \pi l}{6\pi l} \right] 6\pi l}{4\pi l} \right] + 1$$

⟦folio 48⟧

Fig. 14.

F13. Two identical cylinders with pistons are connected by a tube (Fig. 14). There is water in the cylinders. Identical cylindrical glasses with equal amounts of water are placed on top of the pistons. Then a body of mass $m$ is lowered into one of the glasses, and a body of mass $M$, which do not sink, is lowered into the other.

At what distances from each other will the ends of the pistons and the water levels in the glasses be when the system reaches equilibrium? The day area of ​​the glasses is $S_1$, the area of ​​the pistons is $S_2$.

Solution. Since the cylinders are connected by a tube, the water pressure in the cylinders at the same levels should be the same. Identical and pressure in the cylinders is at the level at which the lower edge of the left piston is located. But the pressure in the left cylinder (Fig. 14) at this level is $\frac{(M_0 + M)g}{S_2}$, and the pressure at this level in the right cylinder is $\frac{(M_0 + m)g}{S_2} + \rho gy$, where $M_0$ is the total mass of the piston, glass and water in the glass, and $\rho gy$ is the pressure of a column of water of height $y$. Then from the equilibrium condition we obtain:

$$\frac{(M_0 + M)g}{S_2} = \frac{(M_0 + m)g}{S_2} + \rho gy.$$

Solving this equation, we find that

$$y = \frac{M - m}{\rho S_2}.$$

Now let’s determine the values ​​of $x$. When a body is immersed in a glass, the pressure at the bottom of the glass increases by an amount equal to the weight of this body. On the other hand, since the body does not sink and does not itself press on the bottom, a change in the force of pressure on the bottom is a change in the force of water pressure on the bottom due to the fact that the water level increases. If the water level in a glass rose by $\Delta x$, then the water pressure at the bottom increased by $\rho g \Delta x$, and the pressure force by $\rho g \Delta x S_1$. Thus, for the left glass $\rho g \Delta x S_1 = Mg$, where $\Delta x_1$ is the change in the water level in the left glass: $\Delta x_1 = \frac{M}{\rho S_1}$. Similarly, we find that in the right glass the water level when the body was immersed in it rose by $\Delta x_2 = \frac{m}{\rho S_1}$. Since the distance between the bottom of the left and the bottom of the right glasses is $y$, then

$$x = y + \Delta x_2 - \Delta x_1 = \frac{(M - m)(S_1 - S_2)}{\rho S_1 S_2}.$$

F14. Two pipes with sections $S_1$ and $S_2$ are connected to each other and plugged with pistons whose masses are $m_1$ and $m_2$ (Fig. 15). After an explosion in the space between the pistons, the pistons fly out of the pipes. One of them flew out at a speed of $v$. At what speed did the second one fly out if: a) the pipes are fixed and cannot mix, b) the pipes are not fixed and their total mass is $M$? Neglect the friction of the pistons against the pipe walls.

Solution. Let us first consider the case when the pipe is fixed. The gas pressure on the pistons is the same, and the pressure force is related to the area of ​​the pistons. Since these forces act on the pistons for the same amount of time (we believe that after one of the pistons leaves the pipes, the pressure on the second piston drops abruptly to the pressure outside), then the ratio of the average pressure forces on the pistons is equal to the ratio of the areas of the pistons. This gives us the opportunity to find the ratio of the impulses of the pistons after they leave the pipes. The initial impulses of the pistons are zero, and the change in their impulses is equal to the average forces multiplied by

⟦folio 49⟧

Fig. 15.

at the time of the explosion. Therefore, the ratio of the impulses of the pistons after they leave the pipes is equal to the ratio of the average pressure forces acting on the pistons, and, therefore, equal to the ratio of the areas of the pistons.

To determine this, we will assume that the left piston (Fig. 15) comes out at a speed of $v$. The speed of the right piston will be denoted by $u$. Then we can write that $\frac{m_1v}{m_2u} = \frac{S_1}{S_2}$; hence $u = v\frac{m_1S_2}{m_2S_1}$.

Now consider the case when the pipes are not fixed. Then after the explosion they will acquire a speed, which we will denote $u_1$. Comparing in the same way as we did for pistons, the average pressure forces acting on the left piston and on the joint of the pipes, we find that $u_1 = v\frac{m_1(S_2 - S_1)}{MS_1}$.

As for the pistons, our alienation is fair for them in this case as well.

F15. The amount of heat $Q=190$ kilocalories penetrates through the walls of the refrigerator in an hour. The temperature inside the refrigerator is $T_1=+5^\circ\text{C}$, and in the room $T_2=+20^\circ\text{C}$. What is the minimum power consumption of this refrigerator from the network?

Solution. A refrigerator is a heat engine operating on a processing cycle. If a direct heat engine absorbs an amount of $T_2$ and separates a lesser amount of heat $Q_1$ at a low temperature $T_1$, performing work $A = Q_2-Q_1$, then a refrigeration engine absorbs an amount of heat $Q'_1$ from cold heat at a temperature of $T_1$ and separates an amount of heat $Q'_2$ to a higher heat at a temperature $T_2$. In this case, you need, of course, to supply energy $A'=Q'_2-Q'_1$ to the refrigerator.

The efficiency coefficient of a direct heat engine $\eta = \frac{A}{Q_2} = \frac{Q_2-Q_1}{Q_2}$ cannot exceed the value $\frac{T_2-T_1}{T_2}$. Moreover, in order for c.p. The machine was at its maximum, it would have to work in a reverse cycle. If the refrigeration machine operates on the same cycle as the direct one, then $Q'_1 = Q_1$, $Q_2=Q_2$ and $A'=A$. K.p. d. of the refrigeration machine would in this case be equal to $\eta_x = \frac{Q'_1}{A} = \frac{Q_1}{Q_2-Q_1}$. But in this case, k.p. d. of a straight machine is $\frac{Q_2-Q_1}{Q_2} = \frac{T_2-T_1}{T_2}$, and therefore $\frac{Q_1}{Q_2} = \frac{T_1}{T_2}$. Using this correspondence, we find that k.p. d. of the refrigeration machine cannot exceed the value $\frac{Q_1}{Q_2} = \frac{T_1}{T_2}$.

The k.p. calculated using this formula. refrigerator (sometimes called the “coefficient of performance”) can be more than one. This is due to the fact that, by separating the energy $Q_2$, we consume not only the energy $A$, but also the energy $Q_1$ received from cooling the body. When calculating the k.p. e machine, we consider only the energy $A$ consumed from the network, since this is the only energy we have to pay for.

⟦folio 51⟧

Fig. 16.
at high speeds of automatic movement, there was no loss of power in the mechanisms and rolling friction of the wheels on the road. Consider how taking these factors into account would change equations (1) and (2).

F17. A plate having a charge $q$ was placed between the plates of a short-circuited flat capacitor. The plate is moved parallel to itself at a distance $x$ (Fig. 17). What charge passes through the external circuit of the capacitor if the distance between its plates is $d$?

To solve the problem, we need to know what field is created by a large uniformly charged plate (large compared to the distance from the plate to the point at which the field interests us). We will proceed from the fact that, as we know, the electric field in a flat capacitor is equal to $\frac{u}{d} = \frac{Q}{C_d} = \frac{Q}{\varepsilon_0 S}$, where $C$ is the capacitance of the capacitor, $u$ is the potential difference between its plates, $Q$ is the charge of the capacitor, $S$ is the area of the plates, $d$ is the distance between the plates and $\varepsilon_0$ is the electrical constant. But the field in the capacitor is equal to the sum of the fields created by its plates. This means that each of the capacitor plates creates a field equal to $\frac{1}{2} \frac{Q}{\varepsilon_0 S}$. Such a field should be created simply by one large uniformly charged plate.

Thus, we found that the middle movable plate creates a field $\frac{1}{2} \frac{q}{\varepsilon_0 S}$. But the field of a system of charges is equal to the sum of the fields created by each of the charges separately. Therefore, the field between the plates is equal to the sum of the fields created by the plates and the moving plate. We will assume that the total charge of the closed plates is zero *). Then, if the charge of one of the plates is equal to $Q$, then the charge of the second plate is equal to minus $Q$, and the field created by these plates is exactly the same as the field in a capacitor with charge $Q$ $E = \frac{Q}{\varepsilon_0 S}$. On one side of the plates, the fields of the plates and the movable plate are directed in one direction, on the other - in the opposite direction. Therefore, to the left of the plates (Fig. 18) (for definition we assume that $q > 0$) is the field $E_1 = \frac{1}{2} \frac{q}{\varepsilon_0 S} + \frac{Q}{\varepsilon_0 S} = \frac{q + 2Q}{\varepsilon_0 S}$, and to the right of it is the field

$$E_2 = \frac{Q}{\varepsilon_0 S} - \frac{1}{2} \frac{q}{\varepsilon_0 S} = \frac{2Q - q}{\varepsilon_0 S}.$$

*) It is not difficult to generalize the problem to the case when the total charge of the capacitor plates is not zero. The answer in this case remains the same.
