---
id: 1973-11-vasilev-posledovatelnost-pryizhkov-1578700c
issue: kvant_1973_11
year: 1973
number: "11"
title: Jump sequence
authors:
  - Васильев Н. Б.
rubric: osnovnye-stati
page_first: 27
page_last: 33
page_labels: 25-31
tag: HGEZ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 00b706f8b02e3ba1d0c365dbbe75ad57b54e372afc083c6867ca9b95efd4d4ef
prompt_sha256: draft-1
translated_from: content/ru/1973/11/articles/05_vasilev-posledovatelnost-pryizhkov-1578700c.md
source_content_sha256: 4405c05b41b17c1840994f3f2b4d7c3c15285448a1625dcba24e4d2d9dbd0a25
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 25⟧

Jump sequence

In this note we will solve problem M190 from “Kvant’s Problem” - the problem of a bluefish jumping along two straight lines. It can be solved in different ways. We will reduce this problem to the following question: the path is given by two or more movements of the plane, leaving a given point O fixed (these can be rotations or symmetries); What transformation of the plane will be obtained if these transformations are performed sequentially one after the other?

Since this question is interesting in itself, and not only in connection with solving the problem of blues, we will sometimes deviate to the side and offer exercises that are not directly related to problem M190.

First, let us recall the formulation of the problem.

Two intersecting lines a and b are given on the plane. At point A₀, located on line a at a distance of less than 1 from line b, сdim blues. Then the bluha jumps sequentially to points B₀, A₁, B₁, A₂, B₂, ..., guided by the following rules (Fig. 1):

1) points A₀, A₁, A₂, ... lie on line a, points B₀, B₁, B₂, ... lie on line b;

2) A₀B₀ = B₀A₁ = A₁B₁ = =B₁A₂ = A₂B₂ = ... = 1;

3) the point Aₙ+1 does not coincide with Aₙ, except in the case when A_rB_n ⊥ a (and similarly, Bₙ+1 coincides with Bₙ only if BₙAₙ+1 ⊥ b).

(Conditions 1) - 3) the sequence of jumps is determined uniquely.)

Prove that if straight lines a and b change by a rational number of degrees, then the path of the bluebird will be periodic, that is, at some moment it will get to the initial point A₀ and then will sequentially pass the very points B₀, A₁, B₁, ..., as at the beginning of the path; and if it is an irrational number, then the blue will not hit any point more than twice.

Of course, it is interesting to understand not only whether the bluebird’s path is “cyclical” or not, but also to understand in general how the sequence of points A₀, B₀, A₁, B₁, ..., (1) is structured

for example, learn to determine the positions of points Aₙ and Bₙ by number n. Our decision will answer this question as well. In the future, together with the word “blukha” we will often use the words “point”.

Fig. 1.

⟦folio 26⟧

1. A point jumps along two straight lines
It's natural to start with an experiment:
draw two straight lines, arm yourself with a circlel (even more conveniently, a meter) and, taking some point $A_0$ as the starting point, see what the “trajectory” of the plot looks like. One such example is built on figure 1: points $A_0$, $B_0$, $A_1$, $B_1$, ... are sequentially connected by red and head segments (with arrows) indicating the path of the blog. You can repeat this experiment by taking a different angle between the lines or a different starting point. After several delays, it is clear that points $A_n$ (and $B_n$) fall either on one side or on the other side of the intersection point $K$ of lines $a$ and $b$. True, there is no strict periodicity here:
for example, on figure 1 blozha appears on each of the rays with vertex $K$, sometimes twice in a row, sometimes three times. And, of course, the experiment does not allow us to find out whether the blog after several steps ends up at the starting point $A_0$: after all, we can only carry out constructions by approximation, so from the drawing we will not be able to grasp the difference between rational and irrational approximation.

Fig. 2.

Fig. 3.

scrap. (The only case that is immediately clear is when the angle is a right angle; Fig. 2.)

No corral figure can suggest a simpler pattern that determines the path of the bug than rule 1) - 3) formed in the conditions of the problem.

2. Jumping directions
Consecutive links of the broken line - trajectories of the plot - are vectors of unit length

$\vec{A}_0\vec{B}_0, \vec{B}_0\vec{A}_1, \vec{A}_1\vec{B}_1, \vec{B}_1\vec{A}_2, \dots$ (2)
(Each vector shows what the next jump is.)

Note that if we know the vector $\vec{u} = A_n\vec{B}_n$ (let it be drawn somewhere to the side, on the plane), then we can determine where the points $A_n$ and $B_n$ lie.

Indeed, this Lemma is true. Let $a$ and $b$ be intersecting lines. For any vector $\vec{u}$ (on the plane) will find two points $A$ (on the line $a$) and $B$ (on the line $b$) also that the vector $\vec{AB}$ is equal to the given vector $\vec{u}$. Points $A$ and $B$ are uniquely determined.

Proof (Fig. 3). If we want the beginning of the vector to lie on the line $a$ and this vector is equal to $\vec{u}$, then its end must fall on the line $a'$, obtained by parallel transfer of the line $a$ to the vector $\vec{u}$ (at figure 3 the straight line $a'$ is drawn by a dotted line). Therefore, point $B$ must lie at the point of intersection of line $b$ with line $a'$. After this, point $A$ is easily found.

Razzhene 1. Given two points $C$ and $D$ and two lines $a$ and $b$. Find on the lines $a$ and $b$ the corresponding points $A$ and $B$ that the 們 segment of the segments $AC$ and $BD$ coincides; b) the quadrilateral $ABCD$ was a trapezoid whose base $AB$ was twice the size of the base $CD$.

Take a point $O$ on the plane and let all the vectors of the sequence be

⟦folio 27⟧

Fig. 4.

(2) postpone from this point. We denote these vectors, equal to the correspondence of the vector of sequence (2), as follows:

$$\overrightarrow{OC_0}, \overrightarrow{OD_0}, \overrightarrow{OC_1}, \overrightarrow{OD_1}, \dots$$

(3) From the lemma it follows that, knowing the sequence (3), we can use the sequence of points (1):

for example, knowing $\overrightarrow{OC_n}$, one can find both $A_n$ and $B_n$.

figure 4 shows the “buckle directions” (3) for the sequence shown in figure 1. Note that the red vectors $\overrightarrow{OC_n}$ (corresponding to the buckles from line $a$ to line $b$; $n = 0, 1, 2, \dots$) form equal angles with each other. It turns out that this is a general fact that is true for any sequence of buckles. Let us formulate it in the form of a theorem.

Theorem. If the value between the lines $a$ and $b$ is equal to $\gamma$, then the value between

between the vectors $\overrightarrow{OC_n}$ and $\overrightarrow{OC_{n+1}}$ is equal to $2\gamma$.

This is the main message in problem M190. The theorem can be proven by using the fact that any two adjacent links of the broken line in sequence (2) are the lateral sides of an isosceles triangle, and the base of this triangle alternately lies either on the straight line $a$ or on the straight line $b$. The main difficulty in proving the connection is that the links of a broken line can be located differently relative to the given straight lines. For example, to prove the theorem for $\gamma = 60^\circ$, one would have to consider 10 random ones depicted on figure 5 (the rest of them are positive by symmetry with respect to the point of intersection of lines $a$ and $b$). We will do it differently: using the concepts of “transformation” and “product of transformation”, we will give a general proof that covers all cases at once.

⟦folio 28⟧

3. The point jumps around the circle

Let's compare figure 1 and 4 again. Let us select from them fragments consisting of two consecutive links (the same “right-femoral triangles” discussed above; Fig. 6, a, b and 7, a, b). Looking at these figure, it is easy to form a simple rule by which sequence (3) is constructed.

Let us denote by $p$ and $q$ the lines passing through the point $O$ and parallel to the corresponding lines $a$ and $b$; then in sequence (3)

after the vector $OC_n$ there is a vector $OD_n$, symmetrical to it relative to the straight line $p$; after the vector $OD_n$ there is a vector $OC_{n+1}$, symmetrical to it with respect to the straight line $q$ (here $n = 0, 1, 2, \dots$).

Y unraveling 2. Check that this rule exactly corresponds to rules 1)—3) in the conditions of the problem (including in the “expressions” of the case).

Extension 3. a) Prove that if sequence (1) hits the point $A_0$ more than two times, then it will be a period and some point $C_n$ coincides with $C_0$.

6) Give an example when the sequence hits point $A_0$ twice: $A_1$ matches $A_0$, but $B_1$ no longer matches $B_0$.

U kazan e. For a point $A$ on a line $a$ there are at most two vectors starting at $A$, ending on a line $b$ and having length 1.

Let us now formulate problem M190 again (or rather, the problem to which it has been reduced), but we will not talk about transformations of the tori $OC_n$ and $OD_n$ into someone, but about transformations of their ends - points lying on the unit circle.

Let $p$ and $q$ be two lines passing through the point $O$. Let us denote by $S_p$ the transformation of the symmetric relative line $p$ and by $S_q$ the transformation of the symmetric relative line $q$. (We can consider these transformations as transformations of all planes onto themselves; for example, $S_p$ assigns to each point $X$ the point $S_p(X)$, symmetrically to the point $X$ relative to the line $p$. But in the future we will need to consider points on the unit circle with center $O$. It is clear that the transformations $S_p$ and $S_q$ map the unit circle onto itself.) Let $C_0$ be some point located at a distance of 1 from $O$, and

$$C_0, D_0, C_1, D_1, C_2, D_2, \dots$$

- sequence determined by conditions

$$D_n = S_p(C_n), C_{n+1} = S_q(D_n)$$

(Fig.8). We must prove that the point $C_n$ with neokotrom $n$ coincides with $C_0$ if and only if the angle $\gamma$ between the lines $p$ and $q$ is expressed by a rational number of degrees.

So, the problem of jumping along two straight lines has been reduced to the problem of jumping along a circle.

And the theorem that we must prove first of all

⟦folio 29⟧

asserts that $C_n C_{n+1} = 2\gamma$. where $\gamma$ is the angle between $p$ and $q$.

4. Conversion product

Our transition rule (5) will be further simplified if we combine every two consecutive jumps into one: in sequence

$$C_0, C_1, C_2, \dots$$

(6)

each subsequent point is obtained from the previous one according to the following rule:

$$C_{n+1} = S_q (S_p (C_n))$$

(7)

that is, you need to apply $S_p$ to $C_n$, and then to the resulting point $-S_q$.

About the limit. Let $K$ and $L$ be two transformations of the set $M$ onto itself. The product of the transformation $K$ and $L$ is called such a transformation $R$, which assigns the point $X$ from $M$ to the point $L(K(X))$.

Thus, the product of the transformation $K$ and $L$ is simply the result of performing two transformations sequentially: first $K$ and then $L$. The product $R$ means: $R = L \cdot K$. Writing $K$ and $L$ in exactly this order (“from right to left”) is convenient in that for any point $X$ the equality holds:

$$R(X) = L \cdot K(X) = L(K(X))$$

(8)

We specifically clarified the order in which the “factors” are written, because for multiplying a transformation, generally speaking, the equality $L \cdot K = K \cdot L$ does not hold (see Exercise 4 below).

The product of three and a large transformation number is defined in the same way: $R = R_1 \cdot R_2 \cdot R_3$ means that you need to do first $R_3$, then $R_2$, then $R_1$. Finally, the notation $R = (R_1)^n$ means that $R$ is the result of applying the transformation $R_1$ $n$ times.

Let's return to our $S_p$ and $S_q$ - symmetrine transformations with respect to the straight lines $p$ and $q$. What will their product be? (Now it is more convenient for us to assume that $S_p$ and $S_q$ are transformations into the plane onto themselves.) It is clear that the point $O$ remains in place under the transformation $S_q \circ S_p$: it goes into itself both under the transformation $S_p$ and under the transformation $S_q$. What happens to the remaining points?

This transformation can be visually represented as follows. During the transformation $S_p$ the plane is always flipped around the straight line $p$ and superimposed on itself by the “other side”. After the second transformation $S_q$ - symmetric relative to the straight line $q$ - the plane is again turned over to the transition side. It is clear that the movement of a plane that has a fixed point $O$ and does not change the “orientation” of the plane (does not turn the plane over to the other side) can only be a rotation around the point $O$. Thus, $R = S_q \circ S_p$ is a rotation of the plane through some angle around the point $O$. At what angle exactly? In order to answer this question, it is enough to take one point and see what happens to it. Let the angle from straight line $p$ to straight line $q$ be equal to $\gamma$ (we will count the angles counterclockwise). Take point $E$ on line $p$ (Fig. 9) and find $R(E)$. It is clear that $S_p(E) = E$: which point of the line $p$ transforms into itself under the transformation $S_p$. And then the point $E$ falls on a straight line, symmetrically to the straight line $p$ relative to the straight line $q$, that is, the surface around the point $O$ at an angle $2\gamma$. So, if the angle from $p$ to $q$ is equal to $\gamma$, then $R = S_q \circ S_p$ is a rotation through the angle $2\gamma$. This leads to our main theorem:

$$\cup C_n C_{n+1} = 2\gamma.$$

⟦folio 30⟧

Fig. 10.

U tense 4. Make sure that the transformation $S_p \circ S_q$ is a rotation by angle $(-2\gamma)$, that is, a rotation by $2\gamma$ clockwise (see syntegrine on Fig. 4). Thus, if the angle $\gamma$ is different from a zero or right angle, then $S_p \circ S_q \neq S_q \circ S_p$.

5. Recording rotations and symmetries of a circle

It is possible to calculate the product of the transformed one formally. To do this you need to enter coordinates. Since we are only interested in displacements of the plane that have the given point $O$ fixed, we can, together with the transformed plane, talk about mappings of the unit circle with center $O$ onto itself - about rotations and symmetries.

Let's enter the coordinates of the circle like this. Let us select the beginning of the report $E$—one of the points of intersection of the straight line $p$ with the unit circle. Let us assign each point $X$ of the circle to the value of the angle $EOX$, counting from $OE$ counterclockwise and measured in degrees (Fig. 10); in this case, the point $X$ corresponds to a set of numbers

$$\varphi, \varphi \pm 360^\circ, \varphi \pm 2 \ 360^\circ, \dots$$

- a number that differs by an integer multiple of $360^\circ$ corresponds to the same point on the circle.

Tension 5. a) Transformation $S_p$ - symmetry with respect to straight line $p$ - is given by the formula $S_p(\varphi) = -\varphi$.

6) Transformation $R^\alpha$—rotation by angle $\alpha$ (counterclockwise)—is given by the formula $R^\alpha(\varphi) = \varphi + \alpha$.

b) Let the straight line $q$ make an angle $\gamma$ with the straight line $p$. We will further denote the transformation $S_q$ by $S_\gamma$ in order to explicitly indicate what angle the straight line $q$ makes with the “initial” straight line $p$. (In part, together with $S_p$ we will write $S_0$.) Then

$$S_\gamma(\varphi) = 2\gamma - \varphi$$

Comment. Of course, $R^\alpha + 360^\circ = R^\alpha$ and $S_\gamma + 180^\circ = S_\gamma$ for any integer $n$ (the angle that the line $q$ makes with the line $p$ is determined up to the addition of any multiple of $180^\circ$). This exactly corresponds to the fact that $\varphi$ is defined up to the addition of an integer multiple of $360^\circ$.

U tense 6. a) Prove that $R^\gamma S_0 R^{-\gamma} = S_\gamma$. What is the geometric meaning of this equality?

6) Prove that $S_{\gamma_1} S_{\gamma_2} = R^{2\gamma_1 - 2\gamma_2}$ (hence, in part, it follows that $S_0 S_\gamma = R^{-2\gamma}$ and $S_\gamma S_0 = R^{2\gamma}$)

b) Check that $R^\alpha R^\beta = R^\alpha + \beta$

d) Prove that $S_\gamma R^\beta = S_\gamma - \frac{\beta}{2}$

d) What is the product $R^\alpha S_\gamma$?

Let us solve problem d) as an example. Let the point $X$ correspond to the number $\varphi$. Then the point $S_\gamma^\circ R^\beta(X)$ corresponds to the number

$$S_\gamma\left(R^\beta(\varphi)\right) = S_\gamma(\varphi + \beta) = 2\gamma - (\varphi + \beta) = 2\left(\gamma - \frac{\beta}{2}\right) - \varphi.$$

posture, as we know (exercise 5 c)), $S_\gamma^\circ R^\beta = S_\gamma - \frac{\beta}{2}$.

U tense 7. Prove that a) $(R^\alpha)^n = R^\alpha n$

6) $(S_\gamma)^2 = I$, where $I$ is the identical transformation ($I$ leaves all points in place).

6. Finishing the solution to the problem about bloxy

So, we found out that in sequence (6) each point follows from the previous one by rotating by an angle $2\gamma$, where $\gamma$ is the angle between straight lines $p$ and $q$. Therefore, $C_n$ is obtained from $C_0$ by rotating through the angle $2\gamma n$. In order for $C_n$ and $C_0$ to coincide, it is necessary and sufficient that the rotation angle be an integer multiple of $360^\circ$. It is clear that if

$$2\gamma n = 360^\circ k,$$ where $k$ is an integer, then $\gamma$ varies by a rational number of degrees. Conversely, if $\gamma = \frac{p}{q}$ degrees, then for $n = 180^\circ q$ we get

$$2\gamma n = 360^\circ p,$$ where $p$ is an integer, so $C_n = C_0$.

⟦folio 31⟧

Fig. 11.

In conclusion, we once again suggest that you get better at “jumps, turns and symmetries.”

7. Somewhat exercised

Although most of the questions below are formulated for specific numbers, we strongly advise you to try to answer analytical questions in a general form (for arbitrary parameter values). Otherwise, this one is even simpler.

8. Let the angle $\gamma$ between the lines $a$ and $b$ be equal to $60^\circ$, and the angle of the segment $A_0B_0$ with the ray $KA_0$ be $7^\circ$. What angle will the segment $A_{100}B_{100}$ make with this ray? Segment $B_{100}A_{101}$?

9. Let the angle $\gamma$ be equal to one radian and $KA_0=1$. Find out whether the point $A_{1973}$ belongs to the ray $KA_0$ or is on the other half of the line $a$.

10. Prove that the period of the block's trajectory (the smallest $n>1$ at which $A_n=A_0$) depends only on the angle $\gamma$, but does not depend on the point from which the block starts. What is this period equal to if $\gamma=72^\circ$? Try to check this fact “experimentally”.

11. Let $\gamma=37^\circ$. How many times in a row will the points of the sequence $A_0, A_1, A_2$, ... occur on the ray $KA_0$ (indicate the smallest and smallest values)?

If you want to solve the following exercise in general form - about patterns in a circle - then you will probably have to use the little theory contained in exercises 6 and 7. By pattern we simply mean a non-extra set of the point $M$, isolated inside the unit circle: we can assume that the circle is white, and this is the set
