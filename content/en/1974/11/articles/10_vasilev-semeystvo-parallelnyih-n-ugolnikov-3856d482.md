---
id: 1974-11-vasilev-semeystvo-parallelnyih-n-ugolnikov-3856d482
issue: kvant_1974_11
year: 1974
number: "11"
title: Family of parallel n-gons
authors:
  - Васильев Н. Б.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 34
page_last: 40
page_labels: 32-38
tag: 14T3
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9f49a04bf48316ac6780fd3f8292d935ba83f78eda856088b9d7a82a93a3218b
prompt_sha256: draft-1
translated_from: content/ru/1974/11/articles/10_vasilev-semeystvo-parallelnyih-n-ugolnikov-3856d482.md
source_content_sha256: a3846da4f19fe987509ba9e3f11c475c4aecf819e8815b1988a1c9c3c7b0fd77
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 32⟧

Family of parallel n-gons
N. B. Vasiliev

Sometimes thinking about an artificial partial problem of the unexpected leads to an interesting and natural theorem. One such case, which occurred with problem M248 from the Problem Book «Kvant», is described below. Although this problem is geometric, our main tools will be linear and quadratic functions - the main ords of school algebra.

“...keep as close to the task as possible, but be prepared to be as far away from the task as you are forced to stay.”

D. Sing a. The mathematical discovery of figure 2. Symmetry figure allows you to easily compare all areas in terms of sides, heights and other convenient parameters. For different values ​​of the parameters one can hope to obtain all possible sets of $P, Q, S$.

(We will start with quadrilaterals rather than triangles, since the case $n = 3$ is special; in this case $S$ is uniquely determined by $Q$ and $P$; we will return to this below*).

In our example, the outer quadrilateral is an equilateral trapezoid with bases 2a and 2b (let $a < b$) and height $k + h$, so

$$P = (a + b)(k + h).$$

The diagonals of the middle quadrilateral are mutually perpendicular and equal to $k + h$ and

$$2c = 2a \frac{h}{k + h} + 2b \frac{k}{k + h},$$

pose

$$S = ah + bk.$$

If these two quadrilaterals are already fixed, then the inner trapezoid

*) This case was discussed in «Kvant» No. 10, p. 24 when solving M248.

⟦folio 33⟧

You can also change it so that it remains parallel to the outer trapezoid. One can imagine that the vertices of the trapezoid move uniformly along the red segments in the time interval $0 \leq t \leq 1$, and at time $t = 0$ the trapezoid degenerates into segment $2c$, at time $t = 1$ into an equilateral triangle with base $2b' = 2c \frac{b-a}{b}$ and height $k + h'$, where $h' = h \frac{a}{b}$, and each value $t$ between 0 and 1 corresponds to a true trapezoid with bases $2c(1-t), 2c(1-t) + 2b't$ and height $tk + th'$. Then its area is equal

$$Q(t) = c \left(2(1-t) + \frac{b-a}{b} t\right) \times \left(k + \frac{ha}{b}\right) t = \frac{(ah + bk)^2}{b^2(k+h)} \times t[2b - (a+b)t].$$

(3)

The last expression - square triangular in $t$ - has a maximum at $t = \frac{b}{a+b}$, and, obviously, at $0 < t < 1$ takes all possible values ​​in the following interval:

$$0 < Q \leq \frac{(ah + bk)^2}{(a+b)(k+h)} = \frac{S^2}{P}.$$

(4)

Battles

1°. The water poured into the aquarium gradually evaporates.

a) What is the water level now if $h$ hours ago it was $b$ cm (from the bottom), and in $k$ hours it will be $a$ cm?

6) What is the water level at time $t$, if at $t = 0$ it is $c$ cm, and at $t = 1$ it is $d$ cm?

Answers. a) $a \frac{h}{h+k} + b \frac{k}{h+k}$,

6) $c(1-t) + dt$.

2°. The merchant knows that he can sell $t \cdot 100\%$ of his goods only if he sets a price of no more than $2b - (a+b)t$ rubles per pood ($a$ and $b$ are known positive numbers). How can he get more money?

Answer. Sell ​​$\frac{b}{a+b} 100\%$ goods at a price of $b$ rubles per pood.

So, in our first example, $Q, P$ and $S$ can take any values ​​for which the inequalities $S < P$ and $QP \leq S^2$, or, what is the same, $\sqrt{QP} \leq S < P$, hold. Indeed, given $P$ and $S$ ($S < P$), we can select $a, b, k, h$ so that equalities (1) and (2) are satisfied, for example, by solving the system of equations

$$a + b = k + h = \sqrt{P},$$

$$(b-a) \times (k-h) = 2S - P,$$

and then (if only (4) is satisfied!) choose $t$ so that $Q = Q(t)$ takes on the desired value.

Battles

3. Prove that if $QP = S^2$, then the trapezoids on figure are 2 sub.

4. Prove that if our parallel polygons are rectangles (Fig. 3), then also $Q \leq S^2/P$.

This strange inequality will always hold true:

$$S^2 \geq QP?$$

(5)

Attempted refutation

Let's consider another, less symmetrical example, when a polygon, when a polygon, when a polygon, when a polygon, where $h$ hours ago it was $b$ cm (from the bottom), and after $k$ hours it will be $a$ cm?

Answers. a) $a \frac{h}{h+k} + b \frac{k}{h+k}$,

6) $c(1-t) + dt$.

Fig. 1.

Fig. 2.

Fig. 3.

⟦folio 34⟧

the nickname $S$ degenerates into the triangle $OAC$, and the polygons $P$ and $Q$ into parallel quadrilaterals $OABC$ and $OGEH$ (Fig. 4). The conditions are to denote the polygons themselves by the same letters as their areas: $S$, $P$ and $Q$. (One can imagine that on figure 4 three $n$-gons ($n \geq 4$) are depicted, all of whose vertices, except two $S$ and three $P$ and $Q$, are located extremely close to the point $O$. It is clear that if we can construct a degenerate example, in which $S^2 < PQ$, then, if we “move” its trace, we can get an example with real, non-degenerate $n$-gons).

We will assume that the vertices $O$, $A$, $B$, $C$ are fixed, and $E$ can move along the segment $AC$ (in this case, the points $G$ and $H$ move along the segments $OA$ and $OC$).

Note that if $E$ falls at the intersection point $E_0$ of $OB$ and $AC$, then the quadrilaterals are also subdivided by $S^2 = PQ$. Indeed, in this case the ratios of the areas $P/S$, $S/Q$ and the corresponding ratios of the areas of the triangles into which $P$, $S$ and $Q$ are divided by the line $OB$ are all equal to the relative $\frac{|OA|}{|OG_0|} = \frac{|OB|}{|OE_0|} = \frac{|OC|}{|OH_0|}$ (Fig. 5).

Now let’s find at what position of the point $E$ on the segment $AC$ the sum of the areas of two triangles $AGE$ and $HEC$ is minimal. Let $H'$ be the intersection point of lines $AB$ and $CD$, $G'$ be the lines $CB$ and $AD$ (D is the fourth vertex of the parallelogram $OADC$, Fig. 6), $M_1$ and $M_2$ be the areas of the triangles $AH'C$ and $AG'C$. If the point $E$ divides the segment $AC$ in the relative $\frac{|AE|}{|EC|} = \frac{t}{1-t}$ ($0 < t < 1$), then the sum of the areas of triangles $AGE$ and $HEC$ is equal to $M_1t^2 + M_2(1-t)^2 = (M_1 + M_2)t^2 - 2M_2t + M_2$ (6)

and minimal at $t = t^* = \frac{M_2}{M_1 + M_2}$, that is, for such a point $E^*$ that divides the segment $AC$ in relation to $\frac{t^*}{1-t^*} = \frac{M_2}{M_1}$.

And the area $Q$ of the quadrilateral $OGEH$ (at fixed points $O$, $A$, $B$, $C$) at this position $E = E^*$ is maximum.

Exercise 5°. Through the point $E$ on the diagonal $AC$ of the trapezoid $ABCD$ a straight line is drawn parallel to the base of the trapezoid and intersecting the sides $AB$ and $CD$ at points $G$ and $H$. At what position of point $E$ is the sum of the areas of triangles $AGE$ and $HEC$ minimal?

Answer. When $\frac{|AE|}{|EC|} = \frac{|AD|}{|BC|}$, that is, when the point $E$ coincides with the intersection point of the diagonal ($|GE| = |EH|$).

So, we know that for $E = E_0$ the equality $Q = S^2/P$ is satisfied, and for $E = E^*$ the area is larger!

We can fail in an attempt to construct an example defining inequality (5) only if, for any choice of the point $B$ inside the triangle $ADC$, the point $E^*$ coincides with $E_0$, that is, the equality

$$\frac{|AE_0|}{|E_0C|} = \frac{M_2}{M_1}$$ (7)

(where $M_1 = S_{\triangle AH'C}$, $M_2 = S_{\triangle AG'C}$).

It would seem, why should these relationships be connected with each other?

⟦folio 35⟧

Hypothesis confirmation

However, it turns out that equality (7) is always true.

Let's prove it using the concept of the center of gravity.

Let us place masses at the vertices of the parallelogram OADC so that the center of gravity of masses $m_A$ and $m_D$ falls at point $G'$, masses $m_C$ and $m_D$ - at point $H'$, masses $m_O$ and $m_D$ - in the middle of the diagonal of the parallelogram: take

$$m_D = m_O = 1,$$
$$m_A = \frac{M - M_2}{M_2},$$
$$m_C = \frac{M - M_1}{M_1},$$

where $M = S_{\triangle ADC}$, $M_1$ and $M_2$ are the same as in (7).

Then the center of gravity of the three masses $m_A$, $m_D$, $m_C$ will be at the point $B$ of the intersection of lines $AH'$ and $CG'$, which means the center of gravity of all four masses lies on the segment $OB$. On the other hand, the pair $m_O$ and $m_D$ can be replaced by a pair of masses, also unit ones, located at the vertices $A$ and $C$ of the parallelogram OADC, therefore the center of gravity of all four masses $m_A$, $m_D$, $m_C$ coincides with the center of gravity of two $\frac{M}{M_2}$ and $\frac{M}{M_1}$, placed respectively at points $A$ and $C$, and divides the segment $AC$ in relation to $M_2 : M_1$. So, we have proven that the segment $OB$ divides the segment $AC$ in the ratio $M_2 : M_1$, that is, $E^* = E_0$.

In the yarn 6.° Let the straight line $l$ intersect the sides $AB$ and $AD$ of the parallelogram $ABCD$ at points $G$ and $H$, the diagonal $AC$ at point $E$. Prove that

$$\frac{|AC|}{|AE|} = \frac{|AB|}{|AG|} + \frac{|AD|}{|AH|}.$$

Thus, our attempt to construct an example defining inequality (5) was carried out. But we can look at the situation from another point of view: from the hypothesis that inequality (5) is always satisfied, we obtained an unexpected consequence - equality (7) - and were able to prove it. This circumstance, of course, greatly strengthens the belief in the validity of such a hypothesis.

We have only described some attempts to disprove inequality (5). In fact, there were much more of them - here we select only those that we were able to present briefly (exercises with the ° symbol), although not directly related to the problem, are recognized to highlight the main messages used in our proofs). The last attempt, which led to equality (7), actually became a turning point in solving the problem: there was no longer any doubt that the inequality $S^2 \geq PQ$ is always satisfied, and all efforts were aimed at proving it. However, even here, daleko was not the first chosen path to the goal.

Tempting dead ends

Here, for example, are attempts to prove the statement of the problem using the partition of a $n$-gon into triangles and quadrilaterals.

U 7. From an arbitrary point of the interior polygon $Q$ we draw rays passing through all the vertices of the polygon $S$, and denote by $S_i, P_i, Q_i$ ($i = 1, 2, \dots, n$) the parts of the areas $S, P$ and $Q$, enclosed in the corners between adjacent rays (Fig. 7). Prove that for each $i$ the inequality $S_i^2 \geq Q_iP_i$ is true.

8. Let us divide the “gap” between the contours of the polygons $P$ and $Q$ into $n$ by a trapezoid $T_i$ (Fig. 8). a) Prove that $Q$ can be hit

Fig. 7.
Fig. 8.
Fig. 9.

⟦folio 36⟧

on the part $Q'_i$ so that $Q'_i$ lies between the extensions of the lateral sides of the trapezoid $T_i$. 6) Prove that with such a partition the inequality $(S'_i)^2 \geq Q'_i P'_i$ holds for the areas $Q'_i$, $P'_i = Q'_i \cup T_i$ and $S'_i = (S \cap T_i) \cup Q'_i$.

9. Let $S_i^2 \geq P_i Q_i$ for each $i = 1, 2, \dots, n$. Should it be here that $(\Sigma S_i)^2 \geq (\Sigma P_i)(\Sigma Q_i)$? *)

Ohm. No, you shouldn't.

Let's try to translate the problem into the language of algebra and prove the resulting inequality.

Average - extra

In one respect, this attempt was successful: it allows us to simplify our problem by eliminating the mention of the “intermediate” polygon $S$ and leaving only $P$ and $Q$. Here's how it works.

Let us denote the sides of the interior polygon $Q$ by $a_i$, the sides parallel to them $P$ by $b_i$ ($i = 1, 2, \dots, n$); we will use the same letters to denote the lengths of the sides); the distances between the lines on which $a_i$ and $b_i$ lie are through $h_i$. Then

$$S = Q + \frac{1}{2} \sum_{i=1}^{n} a_i h_i,$$

$$P = Q + \frac{1}{2} \sum_{i=1}^{n} (a_i + b_i) h_i.$$

From this it is clear that the $n$-gon $S$ is not particularly needed: if its vertices are moved along the sides $b_i$ (this will turn it into a $2n$-gon, Fig. 9), then the area $S$ does not change. Let us introduce the following notation:

$$R = \frac{1}{2} \sum_{i=1}^{n} a_i h_i,$$

$$T = \frac{1}{2} \sum_{i=1}^{n} (a_i + b_i) h_i.$$

*) Here $\Sigma x_i$ denotes the sum $x_1 + \dots + x_n$.

Then the hypothetical inequality (5) will be written as follows:

$$(Q + R)^2 \geq Q (Q + T),$$

or, after simplification:

$$R^2 \geq Q (T - 2R).$$

Let us introduce one more notation:

$$K = T - 2R = \frac{1}{2} \sum_{i=1}^{n} (b_i - a_i) h_i;$$

(10)

and then our inequality will take the same form as (5):

$$R^2 \geq QK,$$

(11)

- but with the pleasant difference that now all quantities relate only to two parallel polygons and their relative positions.

Exercise 10. Is it true that $T > 2R$, that is, $K > 0$?

Answer. Not always. (However, if $K < 0$, inequalities (11), and therefore (5) are very strong.)

Let us now try to prove that for any parallel convex $n$-gons, one of which lies inside the other, inequality (11) is satisfied.

Let us immediately note that this statement, at least at first glance, a significant number of polygons can be placed third: the “gap” between them may turn out to be too large (Fig. 9). Is (11) true in all cases?

From a couple - a family

We will now see that our notation is quite clever: inequality (11) expresses some natural property of a whole family of parallel polygons.

This family is obtained from the given two polygons $Q$ and $P$ very simply. Let's imagine that $n$ points coinciding at the moment of time $t = 0$ with the vertices of the polygon $Q$ began to move - some with their constant speed - so that

⟦folio 37⟧

at the moment of time $t=1$ fall into correspondence with the rows of the polygon $P$ (Fig. 10). At any time $t$ (at least between 0 and 1) these $n$ points will obviously be the vertices of a convex polygon parallel to $Q$ and $P$. Let's denote this polygon (as well as its area) by $F(t)$. Since the lengths of the side $n$-gon $F(t)$ and their distances from the parallel side $Q$ change uniformly with time, we have

$$F(t) = Q + \sum_{i=1}^{n} \frac{(a_i(2-t) + b_i t) h_i t}{2} = Q + 2Rt + Kt^2. \quad (12)$$

We see that $F(t)$ is expressed, as a function of time $t$, by a square trinomial; inequality (11) means that the discriminant of this trinomial $R^2-QK$ must be greater than or equal to zero. The non-negativity of the discriminant is equivalent to the statement that the trinomial $F(t)$ has a real root (but, of course, this root cannot possibly be on the segment $[0, 1]$, where $F(t) > 0$ by definition).

Battles

11. Prove that the discriminant of a quadratic trinomial

$$F^*(t) = F(\alpha + \beta t) = (Q + 2R\alpha + K\alpha)^2 + 2(R + K\alpha)\beta t + K\beta^2 t^2$$

has the same sign as the discriminant $F(t)$ (here $\alpha$ and $\beta$ are any numbers, $\alpha \neq 0$).

Comment. Replacing $t$ with $\alpha + \beta t$ simply means choosing a different cutoff origin and a different scale unit on the $t$ axis. It follows that the non-negativity of the discriminant is a property of the entire family of $F(t)$ parallel polygons, regardless of which two of them $Q = F(0)$ and $P = F(1)$ correspond to $t = 0$ and $t = 1$.

12°. From the bottom of a well of depth $h$, a worker throws a stone vertically upward with an initial speed of $v$. Will the stone fly out of the well?

Answer. Yes, if the discriminant of the trinomial $y(t) = -h + vt - (gt^2)/2$ is positive (r is the acceleration of the free pressure of the stone): $v^2 > 2gh$.

So, we put our hypothesis (5) into the following form:

1) The area $F(t)$ as a function of $t$ is expressed by a quadratic trinomial:

$$F(t) = Q + 2Rt + Kt^2 \quad (0 \leq t \leq 1).$$

2) The discriminant of the emodo trinomial is non-negative:

$$R^2 - QK \geq 0.$$

3) The discriminant is equal to zero if and only if the $n$-gon does not change its shape over time (remains similar to the original one).

⟦folio 38⟧

We have formulated the theorem...
But is it true - at least for triangles?

Triangle family

Two triangles with parallel sides are necessarily similar, and three straight lines connecting the corresponding vertices intersect at one point (Fig. 11).

After the tree, the statement becomes obvious if we imagine that one of the triangles is raised above the drawing plane - intersected into a parallel plane: then three planes passing through pairs of parallel sides of the triangles - the plane of the faces truncated by straight lines, the bases of which are our triangles - intersect at one point. At this point, the straight lines connecting the vertices of the triangles and the continuations of the side edges of the truncated straight lines will also intersect. Having projected the entire picture again onto the drawing plane, we find that the three mentioned lines actually intersect at one point $O$.

The family of parallel triangles, defined for instants $t$ from 0 to 1, can be naturally extended along the entire axis $t$ “from minus infinity to the plane of infinity”: at some instants $t = t_0$ the triangle will turn to point $O$, and then grow again; Moreover, its positions before the moment $t_0$ and after $t_0$ are respectively symmetrical with respect to the point $O$. (On figure 12 the case is shown when the point $O$ lies in non-triangles; our reasoning is also applied to this case: in the formulation of the theorem, we precautionarily did not stipulate in which direction - outside or inside the polygon - the straight lines should move; later we will see that this is unimportant.) The area of the triangle at time $t = t_0$ vanishes, and for any $t$ is proportional to the square of the linear dimensions, that is, proportional to the square of the difference $(t - t_0)$:

$$F(t) = c(t - t_0)^2,$$

where $c$ is a constant positive number.

The discriminant of such a square triangle is equal to zero, and, therefore, all three points of our theorem in the case of $n = 3$ are satisfied unconditionally.

Battles

13. Prove that lines connecting the vertices of two parallel polygons intersect at one point if and only if the polygons are similar.

14°. Even points move along the plane uniformly and rectilinearly (each along its own straight line and at its own speed). It is known that the first and second points will collide with each of the others. Prove that the third and fourth points meet each other.

15. Check the validity of the theorem for the case when the original polygon is parallel.

16°. Check that our theorem can be formulated as follows: if water evaporates uniformly in an aquarium with flat inclined walls (each of the $n \geq 3$ walls has its own slope), then the rate of evaporation of water $S(t)$ at time $t$ is expressed by a square triangle from $t$; its discriminant is non-negative, and is equal to 0 if and only if the planes of the walls intersect at one point.

The most important (and difficult) thing remains: to prove the theorem for an arbitrary $n \geq 4$.

It would be very careful and in the general case - for any $n$ - to extend our positive function $F(t)$, defined perononally for $t \in [0, 1]$, to the entire axis $t$ and prove that for some $t = t'$ its value will be negative or equal to zero - from this it would follow that the discriminant of the triangle $F(t)$ is non-negative. But doing this right away for arbitrary $n$ is difficult. Therefore, we will use induction.

Let's have some fun

Let us assume that for some $n \geq 3$ our theorem is proven and prove its validity for a family of parallel $(n+1)$-gons by representing a $(n+1)$-gon as a $n$-gon with a cut off corner.

Lemma. Any $m$-pleasure $(m \geq 4)$, with the exception of parallelram, has two adjacent angles whose sum is greater than $180^\circ$.
