---
id: 1986-10-resheniya-zadach-m986-m990-f998-f1002-d5d688fb
issue: kvant_1986_10
year: 1986
number: "10"
title: Solutions to problems M986—M990; F998—F1002
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 36
page_last: 43
page_labels: 34, 35, 36, 37, 38, 39, 41
tag: RQJH
lang: en
source: kvant_digital
extraction: vision
content_sha256: 76b84e95950dcf01a5c853bc971b5a2aed8753a34ca8a00c58901eebe1a06084
prompt_sha256: draft-1
translated_from: content/ru/1986/10/articles/15_resheniya-zadach-m986-m990-f998-f1002-d5d688fb.md
source_content_sha256: 977008c7ca4e47855d2c6a0e320a361dc2809f2a9f1c6415c456aede9fd667d3
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

Problem solutions

M986—M990; F998—F1002

Let's put $a=x^{10}$, $b=y^{15}$ and consider the function
$$f(x)=2x^5+3y^5-5x^2y^3, \quad x \geqslant 0$$
(with fixed $y > 0$). We must prove that $f(x) \geqslant 0$. Derivative
$$f'(x)=10x^4-10xy^3=10x(x^3-y^3)$$
becomes 0 at $x=y$, negative at $0 < x < y$ and positive at $x > y$. Thus (see figure), for $x=y$ the function $f(x)$ takes a minimum value, and for all $x > 0$
$$f(x) \geqslant f(y)=2y^5+3y^5-5y^5=0.$$
Other proofs that do not use calculus can be obtained by factoring $f(x)$:
$$f(x)=(x-y)^2(2x^3+4x^2y+6xy^2+3y^3)$$
or use the inequality between the mean argument and the geometric mean for the heel of numbers $x^5, x^5, y^5, y^5, y^5$:
$$\frac{2x^5+3y^5}{5} \geqslant \sqrt[5]{x^5 \cdot 2y^5 \cdot 3}=x^2y^3.$$
(A detailed discussion of this problem is contained in the new edition of the book “Correspondence Mathematical Optimization”, M.: - “Nauka”, 1986, problem 4-16.)

N. V. Vasiliev

M987. There are 2 teams participating in the tournament. In the first.type there were some.m pairs of commands, in the second - other.m pairs of commands. Prove that after this you can select m teams, no two of which have played each other yet.

Let's depict our 2m commands as points on the plane. We will connect the pairs of commands encountered in the first.type with red segments, and in the second with blue segments. Then from each point there will be one red and one blue segment. Any command belongs to a certain “cycle” - a closed broken line consisting of alternating blue and red segments, so that all 2m points and 2m segments connecting them form one or more such cycles (see figure). Since the colors are alternating, the number of commands in each cycle is even. By choosing in each cycle the use of teams that are next to each other, we get a set of m teams that have not yet played with each other. From the solution it is clear that such a set can be selected $2^c$ in different ways, where $c$ is the number of cycles, and that more than m teams that have not played each other cannot be selected*).

M. Bona

M988. From point O of the plane, n vectors of unit length are drawn. Prove that if for some $k < n/2$ there are at least k vectors on both sides of each line passing through O, then the length of the sum of all n vectors is at most n-2k.

Let $\vec{s}$ be the sum of these vectors; can be considered $\vec{s} \neq \vec{0}$, otherwise everything is very visible. For example, the positive half-axis $Ox$ of the coordinate system $Oxy$ along the vector $\vec{s}$. Moving clockwise from

*)Here is another problem with a similar solution idea: prove that if each of the m members of the circle solved two of the m proposed problems, then it is possible to organize the analysis of the problems so that everyone solves one problem he solved (see problem 5-42 in the book mentioned in solution M986).

⟦folio 35⟧

negative half-plane $Ox$, we measure these vectors lying in the upper half-plane $y \geqslant 0$:
$\vec{a}_1, \vec{a}_2, \dots$; similarly, moving counterclockwise, we freeze the remaining vectors (in the lower half-plane): $\vec{b}_1, \vec{b}_2, \dots$ (see figure). By condition, at least $k$ vectors lie in the left half-plane $x \leqslant 0$; let it be $\vec{a}_1, \vec{a}_2, \dots, \vec{a}_l$ and $\vec{b}_1, \vec{b}_2, \dots, \vec{b}_{k-1}$, ... The condition “on both sides of each line there are at least $k$ vectors” is equivalent to the fact that each of the $n$ vectors, together with the $k$ following it counterclockwise (or clockwise) lie in the same half-plane. It follows that there are $k$ pairwise sums of vectors:
$\vec{a}_1 + \vec{b}_{k-1+1}$ (that is, the sum of the vector $a_1$ and $k$ from it counterclockwise, $\vec{a}_{l-1} + \vec{b}_{k-l+2}, \dots, \vec{a}_1 + \vec{b}_k$, as well as $\vec{b}_{k-l} + \vec{a}_{l+1}, \vec{b}_{k-1-l} + \vec{a}_{l+2}, \dots, \vec{b}_1 + \vec{a}_k$ - all give negative projections onto the $Ox$ axis. (Indeed, for example, the sum $\vec{v} = \vec{a}_1 + \vec{b}_k$ is directed along the bisector of the angle formed by the vectors $\vec{a}_1$ and $\vec{b}_k$, and the negative half-axis $Ox$ lies inside this angle and therefore makes an acute angle with $\vec{v}$.) The projections of each of the remaining $n-2k$ vectors are not more than 1. Therefore, the projection of the sum of all vectors, and it is equal to the length of $\vec{s}$, is not more than $n-2k$.

Note that in the conditions of the problem, a vector lying on a straight line can be considered located on any side of it.

It would be interesting to obtain a statement similar to our problem for vectors in space.

P. A. Kalutsin, V. V. Prasolov

◆ Let $d_1, d_2, \dots, d_n$ be divisors of the number $a$ such that
$$a - 1 = \frac{a}{d_1} + \frac{a}{d_2} + \dots + \frac{a}{d_n}.$$
Then
$$1 - \frac{1}{a} = \frac{1}{d_1} + \frac{1}{d_2} + \dots + \frac{1}{d_n} < 1.$$ (1)

The idea of ​​solving the problem is to ensure that each $n=2, 3, \dots$ in the set $X_n$ of numbers representable by the sum of $n$ numbers figurative of natural numbers, indicate the most number $\mu_n$, strictly less than 1. Then from (1) the estimate for $a$ will follow:
$$1 - \frac{1}{a} \leqslant \mu_n \Rightarrow a \leqslant \frac{1}{1-\mu_n}.$$ (2)

Note that since the set $X_n$ is infinite, even the existence of such a $\mu_n$ for each $n$ needs proof: a visual explanation of this proof, which we will give in point c), is that $X_n$ is obtained by adding to each number from $X_{n-1}$ all numbers of the form $1/k$ ($k=1, 2, \dots$) and therefore the points from $X_n$ accumulate in infinite quantities only to the right of each point from $X_{n-1}$ and cannot accumulate to the left of each point (in particular, from point 1).

a) Answer: $a=3, 4, 6$. If
$$x = \frac{1}{k_1} + \frac{1}{k_2} < 1, \quad k_1 \leqslant k_2,$$
then $k_1 \geqslant 2, k_2 \geqslant 3$ (begin $x \geqslant 1/2 + 1/2=1$), therefore $x \leqslant \mu_2=1/2+1/3=5/6$ and from (2) it follows that $a \leqslant 6$. Going through all such $a$, we see that the number is $a-1$

⟦folio 36⟧

can be represented as the sum of two divisors $a$ only for $a=3, 4$ and 6 (in these cases $a-1$ is equal to $2=1+1, 3=2+1, 5=3+2$; 4 cannot be represented as the sum of two divisors $a=5$).

6) Let

$$x = \frac{1}{k_1} + \frac{1}{k_2} + \frac{1}{k_3} < 1, \quad k_1 \leqslant k_2 \leqslant k_3.$$

If $k_1 \geqslant 3$, then $x \leqslant 1/3+1/3+1/4=11/12$; if $k_1=2, \quad k_2 \geqslant 4$, then $x \leqslant 1/2+1/4+1/5=19/20$; if $k_1=2, \quad k_2=3$ then $k_3 \geqslant 7$ and

$$x \leqslant 1/2+1/3+1/7=41/42.$$

Thus, $\mu_3=41/42$ and from (2) it follows that $a \leqslant 42$. By going through these $a$, we can select those for which $a-1$ is represented as the sum of three divisors $a-1$. Answer: $a=4, 6, 8, 10, 12, 18, 20, 24$ and 42.

c) Let us prove that for any $c>0$ in the set of numbers belonging to $X_n$ and less than $c$, there is the most number $\mu_n(c)$. (To solve the problem it is enough to prove this for $c=1$, but a more general statement is easier to prove by indication on $n$.) For example, that $X_n$ is an infinite set of numbers of the form

$$x = \frac{1}{k_1} + \frac{1}{k_2} + \dots + \frac{1}{k_n},$$

(3)

where $k_1, k_2, \dots, k_n$ are natural numbers.

For $n=1$ our statement is obvious: $\mu_n(c)$ is the largest number of the form $1/k$, less than $c$, that is, $1/[c+1]$ (square brackets indicate the integer part of the number). Let our statement be proven for $X_{n-1}$; Let's prove it for $X_n$.

Let us choose a natural number $k$ such that $n/k < c$ (we can take $k=[n/c]+1$). Then among the numbers $x$ from $X_n$, less than $c$, there is the number $n/k$ (the sum of $n$ fractions $1/k$), and in representation (3) of any number $x$, also that $n/k < x < c$, although one of the fractions $1/k_i$ is greater $1/k$, that is $k_i \leqslant k-1$. Moreover, $x-1/k_i$ belongs to $X_{n-1}$ and the most of these $x$ - and this is $\mu_n(c)$ - will be equal to the most of the finite set of numbers

$$\frac{n}{k}, \quad \mu_n\left(c - \frac{1}{k-1}\right) + \frac{1}{k-1},$$

$$\mu_n\left(c - \frac{1}{k-2}\right) + \frac{1}{k-2}, \dots, \quad \mu_n\left(c - \frac{1}{l}\right) + \frac{1}{l}$$

(where $l$ is the most natural number for which $c-1/l>0$, that is, $l=[1/c]+1$).

It turns out that for each $n=3, 4, \dots$ you can indicate the most number $a_n$, for which $a_n-1$ is represented as the sum of $n$ divisors $a_n$: quite a long time ago there was a hypothesis that $\mu_n(1)$ - a number of the form (3) close to 1 on the left - is equal to the sum of the first $n$ fractions $n$ fractions

$$\frac{1}{2} + \frac{1}{3} + \frac{1}{7} + \frac{1}{43} + \frac{1}{1807} + \dots,$$

in which the denominator of each fraction is 1 greater than the product of the denominator of all previous fractions; it follows that $a_n$ is the product of the denominator of the first $n$ fractions (that is, $a_{n+1}=a_n^2-a_n$).

H. B. Vasiliev

⟦folio 37⟧

M990. Three pairwise crossing lines a, b and c, not parallel to the same plane, are given in space; there are various paralleled lines in which these three lines are:
a) pass along the ribs,
b) pass along the edges or diagonals of the faces,
b) contain b paralleled vertices?

Let us first note that for any three pairwise crossing lines a, b and c that are not parallel to the same plane, there is a unique segment with endpoints at a and b, parallel to c.

Indeed, the required segment must lie in the plane a, containing a and parallel to c. Obviously, such a plane exists (it can be checked through a and any line intersecting a and parallel to c), unique and not parallel to b. The intersection point of a and b is one of the ends of our segment. Let us draw a straight line parallel to c until it intersects with a, and we will get the second end.

We will have to carry out this kind of segment many times; For brevity, we will call it a c-bridge between a and b or simply a c-bridge. In Figures 1-9, the data lines are indicated with it in color, and the nostics are indicated in red.

a) Answer: 1. It is clear that the 3 places defined by these lines are edges of the exclusive parallelepiped (Fig. 1). Having constructed them, we get 6 vertices, after which the last 2 vertices are also uniquely restored.

b) Answer: 19. Let us first list all possible sets of three pairwise crossing edges or diagonals of the faces of a parallelepiped. They may contain:
1) 3 ribs (see problem a));
2) diagonal of face a, edge b parallel to this face, and edge c intersecting it (Fig. 2);
3) edge a, diagonal b of the face parallel to a, and diagonal c of the face intersecting a (Fig. 3);
4) edge a and diagonals b and c of two faces parallel to a (Fig. 4);
5) 3 diagonals a, b and c of faces, of which 2 (say b and c) lie in parallel faces (Fig. 5).

In each of these cases, the parallelepiped can be uniquely reconstructed if lines containing segments a, b and c are given, and it is indicated which line belongs to each of these segments; Moreover, such lines can be any 3 lines that satisfy the conditions of the problem.

How to build a parallelepiped using our “bridges” is announced figure 2-5. Let us examine in more detail only one case 2). By constructing a c-bridge AB between a and b and a b-bridge CD between c and a, we obtain 4 vertices of the parallelepiped - ends A and D of the diagonal of face a and one end each - B and C - of edges b and c. To construct the remaining vertices, it is enough to plot the vector $\vec{AB}$ from points C and D and the vector $\vec{CD}$ from points A and B. The constructions in cases 3) and 4) are similar, and in case 5) the ends of our bridges give 4 vertices and the centers of two opposite faces of the parallelepiped, which makes it easy to find the remaining vertices.

In each of cases 2)—5) it is also necessary to indicate which of the segments a, b, c will lie on each of the three given lines. This “distribution of fields” can be carried out in 6 different ways, and, as can be seen from the construction, in cases 2) and 3) this gives 6 different parallelepipeds, and in cases 4) and 5) - 3 (since the constructions do not change when b and c are rearranged). Summing up the number of parallelepipeds in all cases, we get 1+6+6+3=19.

⟦folio 38⟧

C) Answer: 31. To the options considered when solving problem 6), those in which one of the lines contains the diagonal $a$ of the parallelepid, and the other 2 -
6) 2 edges $b$ and $c$ (Fig. 6),
7) edge $b$ and face diagonal $c$ (Fig. 7),
8) 2 diagonals of faces $b$ and $c$ (Fig. 8).

Let's build $b$- and $c$-bridges. In case 6) their ends are the vertices of the parallelepid, and the further construction is clear from figure 6. In case 7) the $b$-bridge $AC$ between $a$ and $c$ is an edge of the parallelepid; if $BD$ is a $c$-bridge between $b$ and $a$, then point $D$ (like points $A$, $C$) is the vertex of the parallelepid, 2 more vertices are the ends of vectors equal to $\vec{CA}$, laid down from $D$ and $B$, the remaining 3 vertices are built in a very different way (Fig. 7). The construction in the latter case is somewhat more complicated 8). Let $A_1B$ and $A_2C$ be $c$- and $b$-bridges between $a$ and $b$, or $a$ and $c$ (Fig. 8), respectively. Then points $A_1$ and $A_2$ divide the diagonal $a$ of the parallelepid into 3 equal parts, and points $B$ and $C$ divide the segments $b$ and $c$ in the ratio 2:1, and the segments $A_1B$ and $A_2C$ is 3 times shorter than diagonal $c$ and $b$, respectively. (These statements become obvious if you look at the projection of the parallelepid along the diagonal $b$ - Fig. 9 - and take into account that with a parallel projection the ratios of the lengths of parallel segments are preserved.) Now, setting aside the vectors $\overrightarrow{A_2A_1}$ and $\overrightarrow{2A_1A_2}$ from $A_1$, we find the ends of the segment $a$; putting aside the vectors $\overrightarrow{BA_1}$ and $\overrightarrow{2A_1B}$ from $C$, we find the ends of the segment $c$ and, similarly, the ends $b$, after which it remains to construct the remaining 2 vertices using 6 vertices.

Since in case 7) there are 6 ways to “distribute fields” between given lines, and in cases 6) and 8) there are 3, the total number of parallelepids is $19 + 3 + 6 + 3 = 31$.

V. N. Dubrovsky

F998. A skier descends a high mountain at a set speed $v$. The mountain forms a colla with the horizontal and smoothly passes into the horizontal section. How should a skier lean to avoid falling during the transition? Consider that the transition passes the skier is equal to $M$. Ignore air movement.

Since the transition is smooth, the skier’s kinetic energy is built up and his speed $v_1$ immediately after the transition to the horizontal section is equal to $(по модулю) v$. The change in the skier's momentum during the transition time $t$ is equal to $\Delta \vec{p} = M(\vec{v}_1 - \vec{v})$ and is directed along the bisector of the angle $ABC$ (see Fig.nok).

From the law of momentum change, taking into account the small value of $t$, we have: $\Delta \vec{p} = f\tau$, where $\vec{f}$ is the force acting on the skier’s body from the ski (it is also directed along the bisector). For the skier to balance, it is necessary that the vector of this force passes through the skier's center of mass. From this condition it is found that at the moment of transition to the horizontal section it must lean forward at an angle of $\alpha/2$ from the position it occupied when moving along the slope.

A. N. Semenov

⟦folio 39⟧

F999. A bag of mass $m_1$, connected with a small rigid rope to a bag of mass $m_2$, slides along the main horizontal surface of the table. The rope connecting the bags passes through a small hole in the table (see figure). The length of the rope is $L$, the height of the table is $H$, and $H < L$. To what height does the bag $m_2$ rise after hitting the floor, if at the initial moment the entire rope was lying on the table and the bags did not move?

The velocities $v$ of the bags at the moment one of them hits the floor are determined by the law of conservation of energy:

$$\frac{1}{2} (m_1 + m_2) v^2 = m_2 g H.$$

After the impact, the bag of mass $m_1$ will move along the table until it pulls the rope. At this moment, the bag $m_2$, lying on the floor, is accelerated by the fish so that the speeds of the bags become equal in magnitude.

The change in the speed of the bags in absolute value during this jerk is the same as if the bag of mass $m_2$ was lying not on the floor, but on the table. Indeed, the interaction of the bags is carried out through the rope, and the force applied to the bag lying on the floor differs only in direction from that which would be if it were lying on the table.

Thus, the velocities of the bags $u$ after the jerk can be found using the law of conservation of momentum:

$$m_1 v = (m_1 + m_2) u.$$

The further movement of the bags is again “controlled” by the law of conservation of energy, and the maximum height $h$ of the lifting of the bag $m_2$ is determined by the correspondence

$$m_2 g h = \frac{1}{2} (m_1 + m_2) u^2.$$

Eliminating $v$, $u$ from (1), (2), (3), we obtain:

$$h = \left( \frac{m_1}{m_1 + m_2} \right)^2 H.$$

G. L. Kotkin

F1000. The current $I$, flowing along the contour formed by the four edges of the cube (Fig. 1), creates a magnetic field with induction $B_0$ in the center of the cube. Find the magnitude and direction of the magnetic field induction vector created in the center of the cube by the current $I$ flowing along a contour of six edges (see figure 2 on p. 40).

Fig. 1.

From the symmetrine messages it follows that the indication $\vec{B}_0$ of the field created in the center of the cube (at point $O$) by the current $I$ flowing along the contour $ABCDA$ (see Fig. 1) is parallel to the $OY$ axis. Indeed, when rotated by $90^\circ$ around $OY$, the contour $ABCDA$ turns into itself, therefore, the vector $\vec{B}_0$ must also turn into itself. According to the gimlet, the vector $\vec{B}_0$ is directed along $OY$. Thus, in projection on the $OX, OY, OZ$ axis

$$\vec{B}_0 = (B_x, B_y, B_z) = (0, B_0, 0).$$

To find the field $\vec{B}$ created by the current flowing along the contour $ABCGHEA$ (see Fig. 2), we use the principle of superposition. Note that exactly the same distribution of current along the edges of the cube will be obtained if we take three circuits: $ABCDA$, $DCGHD$ and $ADHEA$, along each of which the current flow is $I$. This means that the combination of these three contours creates the desired field $\vec{B}$ in the center of the cube. According to the principle of superposition, $\vec{B}$ is equal to the vector sum of the three fields created by each of the circuits:

$$\vec{B} = \vec{B}_{ABCDA} + \vec{B}_{DCGHD} + \vec{B}_{ADHEA} = (0, B_0, 0) + (-B_0, 0, 0) + (0, 0, B_0) = (-B_0, B_0, B_0).$$

⟦folio 41⟧

F1002. A point source of light is located at a distance L from the screen. A converging lens with a focal length F > (L/4), parallel to the screen, is moved between the source and the screen. At what position of the lens will the diameter of the spot visible on the screen be minimal?

Let the lens move to the side so that the distance between it and the screen does not change. Then the size of the spot on the screen remains unchanged, because the beam of rays behind the lens is a cone with its vertex in the actual or minimum image of the source and the generators passing through the perimeter of the lens. Since the point of intersection of the planes of the lens and the screen with the height of the cone does not change in such light, then (from similarity) the size of the spot does not change either.

Therefore, we can move the lens so that the source is on its main optical axis. Let x be the distance from the source to the lens. It is not difficult to show that under the condition F > (L/4) it is impossible to obtain a sharp image of the source (point) on the screen - at any position of the lens, a spot will be visible on the screen, the diameter d of which depends on x and is minimal at x = x₀. In fact, the source image appears on the screen if

$$\frac{1}{x} + \frac{1}{L-x} = \frac{1}{F},$$

or $x^2 - Lx + FL = 0$,

but this equation has no solutions—its discriminant $L^2 - 4FL = 4L((L/4) - F)$ is negative by condition.

If x < F, then the beam of rays is behind the lens at a distance, and the further the lens is from the screen, the larger the spot. For F ≥ L we have x < F for all possible x, and in this case d is minimal at x₀ = L, that is, when the lens is mounted close to the screen. If (L/4) < F < L, then it is obvious that x₀ > F (the beam must converge). In this case, the source image is located behind the screen at a distance y from the lens such that

$$\frac{1}{x} + \frac{1}{y} = \frac{1}{F},$$

that is, y = $\frac{xF}{x-F}$.

From the similarity messages we obtain (see figure):

$$\frac{d}{D} = \frac{y - (L-x)}{y},$$

where

$$d = D \frac{y - (L-x)}{y} = D \left(1 - \frac{(L-x)(x-F)}{xF}\right) = D \left(2 \sqrt{\frac{L}{F}} - \frac{L}{F} + \left(\sqrt{\frac{L}{x}} - \sqrt{\frac{x}{F}}\right)^2\right).$$

This expression has a minimum value at x = x₀ = $\sqrt{LF}$, and

$$d_{\min} = D \sqrt{\frac{L}{F}} \left(2 - \sqrt{\frac{L}{F}}\right).$$

Thus, the spot size is minimal at x₀ = L, if F ≥ L, at x₀ = $\sqrt{LF}$, if F < L.

D. Yu. Grigoriev

Amendment
On the fourth cover page of «Kvant» No. 6, the name of the author of the program is incorrectly indicated. The author of this program is A. A. Levin.
