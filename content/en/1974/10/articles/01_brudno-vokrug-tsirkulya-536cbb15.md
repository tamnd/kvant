---
id: 1974-10-brudno-vokrug-tsirkulya-536cbb15
issue: kvant_1974_10
year: 1974
number: "10"
title: Around the compass
authors:
  - Брудно А. Л.
rubric: osnovnye-stati
page_first: 4
page_last: 11
page_labels: 2, 3, 5, 6, 7, 8, 9
tag: JZSD
lang: en
source: kvant_digital
extraction: vision
content_sha256: f4afdbdb0d8b4087dcd1c8f5f8ecaf9ecfad8d8a59c841cff95992378b26e75e
prompt_sha256: draft-1
translated_from: content/ru/1974/10/articles/01_brudno-vokrug-tsirkulya-536cbb15.md
source_content_sha256: a452930dd172e6e0cfe17d9694f840663ef1901e91028a3cf8a1efae8d9e3b93
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

§ 1. Why are constructions with one compass needed, where are they used?

These constructions are just as unnecessary as constructions with compasses and a ruler. Yes, construction problems, solutions in school (or anything meaningful at all) do not find any application either in practice or in geometry. They are not needed in mechanical engineering (in the design and manufacture of parts). They also have nothing to do with the problem of the emergence of solving problems with compasses and a ruler, the unsolvability of problems of squaring a circle, trisection of an angle, etc.

But this is why construction tasks (with compasses and ruler) turned out to be necessary. On them, schoolchildren learn to independently solve problems in a creative, developmental and testing way to this activity.

Constructions with compasses (without a ruler) will be useful to us in some other ways. But we prefer to discuss which one at the end of the article, rather than in advance.

§ 2. Statement of the problem

In Euclid's geometry, and indeed among the ancient Greeks, constructions with compasses and rulers are studied. Well, what construction problems can be solved with one compass? Here is the problem *), which Mascheroni found and solved (in 1797).

When a person solves a ready-made (set before him) mathematical problem, he, of course, “works as a mathematician.” And who did Mascheroni “work” (better to say, “was or was”) when he formulated his problem - a mathematician or someone else?

To check, we presented Mascheroni's problems to several non-mathematicians. They were asked whether constructions with compasses were of interest, which of the general construction problems could be solved with one compass and which could not be solved, and, finally, whether any construction problem solved with a compass and a ruler could be solved with one compass.

The non-mathematicians agreed among themselves on one thing: “Not every problem solved with a compass and a ruler can be solved with a compass alone, or you cannot draw a straight line with a compass,” they said. And then we saw that a non-mathematician cannot pose Mascheroni’s problem - he cannot independently understand its existence. After all, Mascheroni’s solution (looking ahead, let’s present it) is that any problem solvable by a compass and a ruler can be solved by a single compass. Therefore we think

*) If you want, a super task regarding the construction tasks themselves.

⟦folio 3⟧

that in formulating his problem Mascheroni was “working as a mathematician,” that is, that the formulation of a mathematical problem was creatively mathematical.

Of course, Mascheroni also knew that a compass couldn’t draw a straight line. Well (probably, Mascheroni decided), why carry it out? Well, of course, let, for example, the problem say “draw a line that... has certain properties.” So, strictly speaking, the problem should say differently: “the most” (or defined) is a straight line that... has certain properties.” But to determine a straight line, it is not necessary to draw it. It is enough, for example, to specify two arbitrary points on this line.

What to do if you come across a point of intersection of two such “undrawn” straight lines? Well, maybe we can find the point with just a pair of compasses, so that’s not an objection.

§ 3. Mascheroni's theorem

So, Mascheroni decided that instead of drawing a straight line, he would point to two (different) points on the straight line. Having decided this, Mascheroni formulated his theorem:

Mascheroni's theorem.
Any problem that can be solved with a compass and a ruler can be solved with just a compass.

There is nothing wrong with calling our conjecture a theorem. A mathematician does this in order to clearly understand what he wants to prove (if the assumption turns out to be true) or refute (if it is false).

§ 4. Ponsk way of proof

How can you prove Mascheroni's theorem? There are an infinite number of problems that can be solved with a compass and a ruler. It is impossible to actually cross them all (with one compass). However, we will constructively encounter theorems where we need to consider an infinite number of objects. For example, “the sum of the angles of a triangle is 180°.” Here we are also talking about an infinite number of triangles. And yet the situation with this theorem is different. When proving the triangle theorem, we say: “Take triangle ABC.” And by the very silence about the dimensions of the sides and angles of a given triangle, we make the triangle “general”: what will be proven for △ABC turns out to be true for any triangle. How to take the “default” general task of constructing compasses and a ruler? We don't know how to do this.

Once again, Mascheroni was not so much supposed to “solve a problem” as doing something meant “solving it with a compass and a ruler.” Here is the result of his thoughts:

The solution to the problem of constructing compasses and a ruler consists of repeated application of several (axiomatic) problems; Finding a solution to these axiom problems is not performed in fact, but is accepted as an axiom.

Let us consider, for example, the following problem: given a circle and a straight line passing through its center. Find the intersection points of a line and a circle. By solving this problem with a compass and a ruler, we become nothing (the straight line and the circle have already been drawn), but we will say that the points of intersection are “already visible,” that is, we will assume that they are “defined by the axioms.” After careful consideration, Mascheroni received

List
all axiom problems used in constructing compasses and rulers:

(α) Find the intersection points of two lines.
(β) The same for a line and a circle.
(γ) The same for two circles.

⟦folio 5⟧

§ 6. Proof of Mascheroni's theorem

Let's agree on some expressions. If we say that a segment AB is given, then this means that its ends A and B are given; if a straight line AB is given, then only two points A and B are given on it. If you need to construct a segment AB, then you only need to construct its ends A and B; if you need to find a line AB, then it is enough to indicate two points A and B on it, etc.

When constructing circlels, we cannot draw straight lines, but this does not prevent us from drawing them in proofs, in illustrative drawings.

The first attempts (I hope you will make them) to solve problems (α) and (β) with one circlel, that is, using problem (γ), (δ), were mostly unsuccessful. Therefore, we will move on to the systematic implementation of the planned program.

Pongogram with circlel. Let's see what we can easily build for them.

Let there be two points A and B. We know how to draw a “rosette” on them (see Fig. 2). Triangle CDE is equilateral and AC = 2·(AB) is the diameter of the circle. This suggests the idea of ​​formulating the following problem.

Task No. 1. Doubling a segment. Given a segment AB. View segment AC with midpoint at point B.

Solution (Fig. 3). From the centers A and B we draw circles O_A and O_B of radius AB. Let's find (with the help of

⟦folio 6⟧

ties $O_A$ and $O_B$. Their second (besides $C$) intersection point will be $C'$. If $O_A$ and $O_B$ have only one intersection point, then $C$ lies on $AB$.

Proof. Triangles $ACC'$ and $BCC'$ are isosceles by construction. They have the same base $CC'$. This means that their altitudes (perpendicular $CC'$) pass through the middle of the segment $CC'$ and lie on the same straight line $AB$.

Thus, it is solved
Problem No. 4. Determine whether the point $C$ lies on the line $AB$.

Let's return to the axiom problems ($\alpha$) and ($\beta$). Let's try to solve problem ($\beta$) as follows. Let the data (Fig. 5) be a line $AB$ and a circle $O$ with center $C$. Let's find the point $C'$, symmetrical with $C$ relative to $AB$ (see No. 3). With the radius of the circle $O$ we draw a circle $O'$ from the center $C'$. The points $D$ and $E$ of intersection of the circles $O$ and $O'$ belong to $AB$ and are the required ones. Indeed, points $A$ and $B$ (like $D$ and $E$) are equidistant from points $C$ and $C'$. Therefore, all four points $A, B, D, E$ lie on the same straight line - perpendicular to the segment $CC'$ passing through its middle.

Unfortunately, this solution becomes invalid when the center $C$ of circle $O$ lies on $AB$. Then $O$ and $O'$ coincide and do not allow us to find the points $D$ and $E$. Therefore, we have solved only a special case of problem ($\beta$) - namely
Problem No. 5. Given a line $AB$ and a circle $O$ with a given center not lying on $AB$. Determine whether $O$ intersects with $AB$, and find the points of intersection.

Let's continue the exercise of solving problems with a compass.

Problem No. 6. Proportional division. Given two segments $AB$ and $DE$. At $AB$ there is a point $C$. Find on $DE$ the maxim point $F$ to $AC = AB = DF = DE$.

Solution. By increasing the segments $AB$ and $AC$ by the lower number of times (see No. 2), we obtain a segment $A'B'$ from the point $C'$, sufficiently long (for the construction, which we will now come to), and the same ratio $A'C' : A'B' = AC : AB$. Therefore, we can assume from the very beginning that $AB$ is long enough.

Now (Fig. 6) from the centers $D$ and $E$ we will draw serifs with a radius $AB$. These serifs (if $AB$ is long enough) will intersect at some point $G$. From points $D$ and $G$, using serifs of radii $AC$ and $BC$, point $H$ is found. It lies on $DG$, and for it $DH = AC$ and $GH = BC$.

From the center $H$ we draw a circle with radius $HD$ and determine the desired point $F$, where this circle intersects the straight line $DE$ (see No. 5).

Proof. Triangles $DFH$ and $DEG$ are isosceles, with a common angle at the base. So they are similar. Pozny $DF : DE = DH : DG = AC : AB$.

Problem No. 7. Dividing a segment in half.

⟦folio 7⟧

Fig. 7.

Solution. Let the segment DE be given. Let's take some segment AB with a midpoint at a point C known to us. To obtain such a segment AB, it is enough to notify (see No. 1) the segment DE. Applying the previous problem to AB and DE, we obtain point F in the middle of DE.

Now it's easy to solve

Problem No. 8. From a point outside the line, lower the redistributor onto the line.

Solution. (Fig. 7). Given a straight line AB and a point C. Let's construct a point C', symmetrical to C relative to the straight line AB (see No. 3), and find the midpoint D of the segment CC' (see No. 7).

It’s interesting that, apparently, we still don’t know how to use a repredcular from a point lying on a line.

Easy but important

Problem No. 9. Determine whether points A and B lie on different lines of the straight line CD.

Solution. First, let's check that A or B are not on CD (see #4). If they do not lie, then (Fig. 8) we drop the redistributor AE from A to CD and the redistributor BF from B to the straight line AE. If (on line AE) point E does not lie between A and F, then (in this and only this case) A and B lie on the same side of CD.

This task requires some explanation. We will use the order axiom: of the three points on a straight line, one and only one lies between A and F, then (in this and only this case) A and B lie on the same side of CD.

This task requires some explanation. We will use the order axiom: of the three points on a straight line, one and only one lies between A and F, then (in this and only this case) A and B lie on the same side of CD.

The application of problem No. 9 is the following two problems:

Problem No. 10. Construct a parallelogram ABCD on three points A, B, C that do not lie on the same line.

Solution (Fig. 9). From centers A and C we draw circles of radii BC and AB, respectively. As D we take the point of intersection of the circles that, together with C, lies on the same side AB (see No. 9).

Comment. Without solving problem No. 9, we could get another point D' of the intersection of the circles and together with the parallelogram we would get a stellated quadrilateral with

⟦folio 8⟧

pairs of equal opposite sides. On figure 9 it is shown as a dotted line.

Task No. 11. Addition of parallel segments.

Solution (Fig. 10). Let $AB$ and $CD$ be parallel and we need to call the segment $CE$ containing the point $D$ so that $AB = DE$. To find $E$ you need to construct a parallelogram $BAED$ or $BADE$ (see No. 10). The first one is when $A$ and $C$ lie on opposite sides of the line $BD$ (Fig. 10), the second one is when they are on one side. The case when the lines $AB$ and $CD$ coincide does not interest us (although it is not complicated).

As a special case of problem ($\alpha$), we solve the following problem:

Task No. 12. Determine whether two lines are parallel: $AB$ and $CD$.

Solution. If both points $A$ and $B$ lie on $CD$ (see No. 4), then the lines coincide and the answer is positive. If at least one of them (say, $A$) does not lie on $CD$, then (Fig. 8) we lower from $A$ to $CD$ the perpendicular $AE$ and from $B$ to the line $AE$ the perpendicular $BF$. If $F$ coincides with $A$, then $AB$ is parallel to $CD$, otherwise it is not parallel.

Now we are able to solve problem ($\alpha$).

Task No. 13. Find the intersection of lines $AB$ and $CD$.

Solution. Let's discard the known cases when points $A$ or $B$ lie on $CD$, or when $AB$ is parallel to $CD$ (see No. 4 and No. 12), or when $AB \perp CD$ (see No. 8). Now, putting aside the segment $AB$ on the straight line $AB$ the number of times (see No. 2) in one direction and the other, we will certainly obtain on the straight line $AB$ two points lying on opposite sides of $CD$, and we will find out about this using No. 9. Therefore, we can assume that points $A$ and $B$ immediately lay on opposite sides of $CD$ (Fig. 11). From $A$ and $B$ we lower the perpendiculars $AA'$ and $BB'$ to $CD$. Let's add parallel segments $AA'$ and $BB'$ (see No. 10). We obtain the segment $A'E$ containing the point $A$, and $AE = BB'$. Divide $A'B'$ by the point $F$ in relation

$$\frac{A'F}{A'B'} = \frac{AA'}{A'E}$$

(see #6). Point $F$ lies at the intersection of $AB$ and $CD$.

Proof. Let us denote (in time) by $F'$ the intersection point of $AB$ and $CD$ and calculate $A'F'$. From the similarity of triangles $A'F'A$ and $A'B'E$ we have $A'F':A'B'=A'A:A'E$. This means $A'F=A'F'$ and dot $F=F'$ are excluding.

So, to complete the proof of Mascheroni’s theorem, all that remains is to find the intersection of a circle and a line passing through its center. And this small task turned out to be the most difficult. Mascheroni solved many more problems until it occurred to him to use the transformed inversion. But we will follow the path indicated by another geometer.

A new proof of Mascheroni's theorem was presented by Napoleon Bonaparte (the same one). The essence of the proof was a new solution to the remaining part of the problem ($\beta$).

But Napoleon did not solve the problem in any way, but first found out what length of segments we can construct with a compass, starting from two given ones, lengths $a$ and $b > a$. Here's what he learned to build:

№14. $\sqrt{b^2-a^2}$. №16. $a\sqrt{2}$.

№15. $a\sqrt{3}$. №17. $\sqrt{b^2+a^2}$.

We will learn too.

⟦folio 9⟧

No. 14. Construction $\sqrt{b^2 - a^2}$.
Let's divide the segment $b = EF$ in half (see No. 7). From the center $O$ we draw a circle $O_b$ of radius $b/2$ (Fig. 12). From point $E$ we draw a notch of radius $a$, intersecting $O_b$ at some point $G$. The segment $FG$ will be the required length. Indeed, the angle $EGF$ is right, since it is based on the diameter. Therefore $(GF)^2 = b^2 - a^2$.

No. 15. To construct the segment $a\sqrt{3}$ we write
$$a\sqrt{3} = \sqrt{(2a)^2 - a^2}.$$
Using No. 1, we construct the segment $b = 2a$ and take No. 14 to the segments $b = 2a$ and $a$.

No. 16. Let's write down the identity
$$a\sqrt{2} = \sqrt{(a\sqrt{3})^2 - a^2}.$$
We know how to build $a\sqrt{3}$ and, therefore, we know how to build $a\sqrt{2}$, let’s take No. 14 to $b = a\sqrt{3}$ and $a$.

No. 17. Let's write down the identity
$$\sqrt{b^2 + a^2} = \sqrt{(b\sqrt{2})^2 - (\sqrt{b^2 - a^2})^2}.$$
We can build $b\sqrt{2}$ (see No. 16) and $\sqrt{b^2 - a^2}$ (see No. 14). This means we can build $\sqrt{b^2 + a^2}$.

Now we can solve the desired problem.

Problem No. 18. Find the intersection of a circle with a line passing through its center.

Solution. Let the bottom be a circle $O_A$ with center $A$ and point $B \neq A$. We need to find the intersections of $O_A$ with line $AB$. Let's denote the radius of $O_A$ by $a$, the length of $AB$ by $b$ and construct $c = \sqrt{a^2 + b^2}$ and $a\sqrt{2}$ (see No. 16 and 17).

Now (Fig. 13) from the center $B$ we will draw a notch of radius $c$ to the intersection with $O_A$ at some point $C$. From point $C$ we draw a circle $O_C$ of radius $a\sqrt{2}$. The intersections $O_C$ and $O_A$ give the required points $E$ and $F$.

Indeed, $\Delta BAC$ is rectangular, or $c^2 = a^2 + b^2$. If $E$ and $F$ are the points of intersection of the line $AB$ with the circle $O_A$, then $(CE)^2 = (CF)^2 = 2a^2$, as was done.

Mascheroni's theorem is completely proven.

§ 7. Why do we need constructions with a circlel without a ruler?
It is well known that mathematics does not exhaust the solutions to ready-made problems, that it includes the search for problems and the formulation of the problem, the formulation of theorems. This part of the mathematics remains hidden, although we know that it is what guides the work. And on the probleme of construction with a zircle, problems and solutions of precisely the “second” part of mathematics are clearly visible.

When we watch a movie, we see actors, but we only guess that there is a director. Should the director stay behind the scenes? We decided to bring him on stage one day.
