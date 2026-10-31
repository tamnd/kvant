---
id: 1970-11-resheniya-ea9bff7c
issue: kvant_1970_11
year: 1970
number: "11"
title: Solutions to problems M11—M15; F18—F23
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 31
page_last: 45
page_labels: 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 41, 42, 43
tag: KSKR
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2de22a7bc99cf517bbaa1c727cbf65e0f21ac43fc730c3dfff6395629a7ebe02
prompt_sha256: draft-1
translated_from: content/ru/1970/11/articles/09_resheniya-ea9bff7c.md
source_content_sha256: 50590bd2e7b05730af3ba43a2c5a9d7fc477b1a8834bee11166a4bdc1a822db7
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 29⟧

M11. On 44 trees located in a circle, 44 cheerful siskins sat (there was one siskin on each tree). From time to time, two siskins simultaneously fly to neighboring trees in opposite directions (one clockwise, the other counterclockwise). Prove that the siskin will not gather on one tree. What if siskins and trees $n$?

Solution. We solve the problem for $n$ siskins and $n$ trees at once. We rank the trees in order (say, clockwise) with numbers from 1 to $n$ (Fig. 1). Let us denote the number of siskins on the $k$th tree at each moment of time by $a_k$ (on the first tree - $a_1$, on the second - $a_2$, etc.). Consider the expression

$$S = 1 \cdot a_1 + 2 \cdot a_2 + \dots + ka_k + \dots + na_n.$$

Let us show that when two siskins fly to neighboring trees in opposite directions, then $S$ either does not change or changes to $n$.

Indeed, let one siskin fly from the $k$th tree to the next one in a clockwise direction. Then in the sum $S$ two terms change. If $k < n$, then the $k$-th and $(k+1)$-th terms change, and their sum becomes equal

$$k (a_k - 1) + (k+1) (a_{k+1} + 1) = ka_k + (k+1) a_{k+1} + 1,$$

that is, it increases by 1. If $k=n$, then the $n$th and first terms change, and their sum

$$n (a_n - 1) + 1 (a_1 + 1) = na_n + 1 \cdot a_1 - (n-1)$$

decreases by $n-1$. On the contrary, if the siskin flies counterclockwise to a neighboring tree, then the sum either decreases by 1 or increases by $n-1$. Therefore, when two siskins simultaneously fly to neighboring trees (one clockwise, the other counterclockwise), then the sum $S$ either does not change at all, or changes to $n$.

At the initial moment of time, there was one siskin perched on each tree,

$$S = 1 \cdot 1 + 2 \cdot 1 + \dots + n \cdot 1 = 1 + 2 + \dots + n = \frac{n (n+1)}{2}.$$

⟦folio 30⟧

Thus, after any number of flights, the sum will be equal to $\frac{n(n+1)}{2} + np$, where $p$ is some integer. If all the siskins were gathered on some one $q$-th tree, then $S$ would be equal to $nq$, that is, the equality $\frac{n(n+1)}{2} + np = nq$ would hold, hence $n+1+2p = 2q$; $n = 2(q-p)-1$.

Thus, if $n$ is even, for example, $n = 44$, then the siskins will not be able to gather on the same tree. Let us show that for odd $n$ this can be used*).

Let's consider the initial situation when there was one siskin on each tree. Let’s “order” one siskin to do it on the spot and call it “unvizable.” Divide the remaining siskins into pairs sitting at the same distance of $r$ flights from the stationary one in both directions ($r=1, 2, \ldots, \frac{n-1}{2}$). It is clear that each such pair can, in $r$ flights, get to the tree where the motionless siskin is sitting.

A similar solution was added by D. Grigoriev from Leningrad, V. Luzgin from Georgievsk, Stavropol Territory, and other readers.

The given solution is typical for problems in which it is necessary to find out whether a certain result can be obtained as a result of a series of transformations. In this case, the transformation is the flight of two siskins in opposite directions, and we want to find out whether as a result all the siskins can gather on one tree. To prove that it is possible, it is enough to give an example of how to do it. To prove that no transformation can obtain the required result, it is often convenient to do this: find some quantity that is preserved under all transformations under consideration and for which the initial value differs from the required one in the final state (such a quantity is called an invariant of the transformation data). In our problem, this quantity is the remainder of the separation of the sum $S$ by $n$.

Those who have solved this problem will be interested in understanding the following more general question. Let the given two different arrangements of $a$ siskins on $n$ trees. Let us say that they are equivalent if one can produce another (during the migration of siskins, as indicated in the conditions of the problem). How do you know if these locations will be equivalent? One more question. It is clear that the set of all possible arrangements of $a$ siskins on $n$ trees falls into several equivalence classes. How many such classes will there be?

M12. What quadrilaterals can be cut by a straight line into two similar quadrilaterals?

Solution. Let us prove that only trapezoids and parallelograms have this property.

Suppose that the quadrilateral $ABCD$ is cut by a straight line into two similar quadrilaterals. It is clear that this one intersects two opposite ones.

*) The need for this stage of proof, as can be seen from the letter, is not clear to all our readers. Let's take a closer look at this. What have we proven so far? Only that if the siskins managed to gather on one tree, then there were necessarily an odd number of siskins (this is a necessary condition). Now we need to prove that this condition is sufficient, that is, that if there is an odd number of siskins, then they will be able to gather on one tree (from what we have proven so far, the condition is sufficient).

⟦folio 31⟧

false sides of a quadrilateral. Let it intersect side AD at point K and side BC at point L (Fig. 2). In what follows, we will use this obvious statement several times: if it is known about two quadrilaterals EFGH and PQRS that they are similar and that vertex E corresponds to vertex P, then <E = <P, <G = <R and, in addition, either <F = <Q and <H = <S, or <F = <S and <Q = <H.

So, suppose that the quadrilaterals ABLK and CDKL are similar (we only find that their angles are respectively equal), and we prove that the quadrilateral ABCD has two parallel sides. Angle α of the quadrilateral ABLK (<α = <AKL) can correspond to one of the angles of the quadrilateral KLCD.

1) <α corresponds to <D. Then <α = <D, <γ = <B, AB || KL || CD.
2) <α corresponds to <C. Then <α = <C, <δ = <B; <B + <C = <α + <δ = 180°, AB || CD; in this case <A = <γ, <D = <β (the case <β = <γ, <A = <D does not need to be considered separately, since in this case <β + <γ = 180° and <A = <D = <β = <γ = 90°).
3) <α corresponds to <γ. Then <B = <D, AD || BC and AB || DC, that is, ABCD is a parallelogram.
4) <α corresponds to <δ. Then <α = <δ = 90°, <B = <C and either <β = <γ = 90°, AD || BC (equal trapezoid or rectangular), or <β = <D, <γ = <A, <A + <D = 180°, AB || CD, and up to notation, this case has the same properties as case 2).

We have proven that ABCD is a parallelogram or trapezoid. It is easy to see that, conversely, any parallelogram or any trapezoid can be divided into two similar quadrilaterals. The parallelogram of any line passing through the center is divided into two equal quadrangles (of course, unless the line goes diagonally). A trapezoid with bases a < b is divided into two similar lines, parallel to the bases and dividing the height in the ratio $\sqrt{b}/\sqrt{a}$; it is necessary, of course, to check that the corresponding sides are proportional (Fig. 3): AK/KD = BL/LC = AB/KL=

⟦folio 32⟧

CL/DC = $\sqrt{b}/\sqrt{a}$. Try to find out when it is possible to split a trapezoid into two similar quadrangles in a more cunning way, corresponding to the following case 2), as shown in figure 4 (answer: if and only if $\sqrt{a}/\sqrt{b} < \sin \alpha/\sin \beta$, where $\alpha < \beta$ are the angles at the larger base of the trapezoid $b$).

**M13. Prove that if the difference between the largest and smallest $n$ real numbers $a_1, a_2, \ldots, a_n$ is $d$, and the sum of the models of all $\frac{n(n-1)}{2}$ pairwise differences of these numbers

$$\sum_{i<j} |a_i - a_j| \text{ равна } s, \text{ то } (n-1) d \leqslant s \leqslant \frac{n^2}{4} d.$$

Solution: Let's plot the points $a_1, a_2, \ldots, a_n$ on the number line. Then $d$ is the distance between the outermost of these points, the leftmost and the rightmost, and $s = \sum_{i<j} |a_i - a_j|$ is the sum of all pairwise distances between these numbers.

One can obviously assume that the points are designated by $a_1, a_2, \ldots, a_n$ in ascending order: $a_1 \leqslant a_2 \leqslant \ldots \leqslant a_n$ (Fig. 5). Let us denote the distance between neighboring points $a_k$ and $a_{k+1}$ by $d_k(k=1, 2, \ldots, n-1)$. Obviously $d = d_1 + d_2 + \ldots + d_{n-1}$.

Let us now express $s$ in terms of the quantities $d_k$. To do this, we replace the total $s$ length of each segment $[a_i - a_j]$ with the sum of those $d_k$ of which it consists: $|a_i - a_j| = d_i + d_{i+1} + \ldots + d_{j-1}$. It is clear that $d_k$ is included in those segments whose left end lies at one of the points $a_1, \ldots, a_k$, and the right end lies at one of the points $a_{k+1}, \ldots, a_n$, that is, in total $d_k$ is included in the sum $k(n-k)$ times. That's why

$$s = \sum_{k=1}^{n-1} k(n-k)d_k.$$

Now the assertions to be proved follow from two very simple inequalities: for all $k=1, \ldots, n-1$

1) $k(n-k) \geqslant n-1 \iff kn-k^2-n+1 \geqslant 0 \iff (k-1)(n-k-1) \geqslant 0$;
2) $k(n-k) \leqslant \frac{n^2}{4} \iff n^2-4nk+4k^2 \geqslant 0 \iff (n-2k)^2 \geqslant 0$.

Let's use these examples and use what we get, what we get

$$\sum_{k=1}^{n-1} k(n-k)d_k \geqslant \sum_{k=1}^{n-1}(n-1)d_k = (n-1)d,$$

$$\sum_{k=1}^{n-1} k(n-k)d_k \leqslant \sum_{k=1}^{n-1}\frac{n^2}{4}d_k = \frac{n^2}{4}d.$$

The correct solutions to this problem were sent by M. Praeger from Tomsk, tenth-class student I. Protasov from Kyiv, S. Pozdnyakov from Vilnius and other readers.

It is also interesting to find out whether the estimates indicated in the problem statement are exact; is it possible, say, to put large numbers together with $n-1$ in the left inequality? In order to be convinced of the opposite, it is enough to give an example of a case when inequality turns into equality (and both of its parts contain positive numbers). It’s easy to come up with such an example, we’ve figured out our proof: we need to arrange

⟦folio 33⟧

points $a_1, a_2, \dots, a_n$ so that all $d_k$, except the first one - $d_1$, are equal to zero, that is $a_1 < a_2 = a_3 = \dots = a_n$. Then $s = (n-1)d_1 = (n-1)d$.

As for the second inequality $s \leqslant \frac{n^2}{4}d$, then for even $n = 2m$ equality can also be achieved in it (it is enough to take $a_1 = a_2 = \dots = a_m < a_{m+1} = \dots = a_{2m}$), and for odd $n = 2m+1$ it can be somewhat refined: it is not difficult to report that for odd $n$ the most of the numbers $k(n-k)$ is equal to $\frac{n-1}{2} \cdot \frac{n+1}{2} = \frac{n^2-1}{4}$ (prove this rigorously!); using this instead of inequality 2), we can prove the stronger inequality $s < \frac{n^2-1}{4}d$ in the same way as above. Equality in it is achieved when $a_1 = \dots = a_m < a_{m+1} = \dots = a_{2m+1}$.

M14. A convex white polyhedron has some faces painted black red so that no two black faces have a common edge. Prove that if at least one of the following conditions is met:
a) more than half of black faces;
b) the area of ​​the black faces is more than half the surface area of ​​the polyhedron, then a ball cannot be inscribed in this polyhedron.

Solution. Let's start with task 6). Let us assume that a ball can be inscribed in a polyhedron. On each face, mark the point of contact with the ball and draw segments from it to the vertices of this face. Then the face will be divided into triangles. Each edge of the polyhedron is adjacent to two such triangles lying in adjacent faces. They are equal on three sides (since two tangents drawn from one point to the ball are equal). By condition, each edge is adjacent to at most one black face. Thus, each black triangle is adjacent to an equal white one*). Consequently, the sum of the areas of the black faces is not greater than the sum of the areas of the white faces. Problem 6) has been solved.

Problem a) is solved in exactly the same way, which was already discussed in the article “Irrepressible polyhedra” by E. M. Andreev (see «Kvant» No. 8, problem 9 at the end of the article). This article examines a number of questions that arise in connection with our task: are there polyhedra that satisfy similar conditions, what other “signs of indescribability” exist, etc. True, as one can judge from the purpose of the article, it is about whether this or that polyhedron can be inscribed in a sphere, and in our task, whether it can be described near a sphere. It turns out, however, that both theories are completely similar.

More precisely, each convex inscribed polyhedron can be assigned a corresponding description so that for each face, the planes corresponding to them will intersect at one point - the vertex of the new polyhedron, corresponding to the face of the original inscribed one. If two vertices of an inscribed polyhedron are connected by an edge, then the corresponding tangent planes will intersect along the edge of the inscribed polyhedron. Thus, we have constructed a mapping of inscribed polytopes into the set of described ones; it is easy to see that this is a mapping onto the entire set of described polyhedra and that it has an inverse mapping

*) But, of course, white can also be applied to a white triangle - the only important thing is that different black triangles correspond to different white ones.

⟦folio 34⟧

(we use the terminology discussed in the article by A. N. Kolmogorov “What is a function” in «Kvant» No. 1)—in other words, that for each described polyhedron one can associate an inscribed one, from which this described one is obtained in the manner indicated above. It is enough to mark the point of contact in each face—the vertex of the future inscribed polygon—and prove that all points of contact of faces that have a common vertex lie in the same plane (Fig. 6). Both of these mappings, connecting the set of convex inscribed and circumscribed polytopes, constitute an excellent example of a situation that mathematicians usually call the word “duality” (this word was mentioned in detail in the article by E.M. Andreev). Think about which described polytopes will be dual to such inscribed ones: a cube, a regular n-gonal prism, a regular n-gonal prism, a regular doctrinal prism, a dodecadron.

We highly recommend that readers return to the article “Indescribable polytopes” and, using the duality we just talked about, translate its content into “indescribable” polytopes.

M15. The square table $n \times n$ is filled with non-negative numbers so that the sum of the numbers in each row and the sum of the numbers in each column is equal to 1. Prove that from the table you can choose $n$ to put the calf of $x$ numbers, no two of which are in any column or row.

Solved and e. Let us first note that if we rearrange the rows (or columns) of our table, this will not affect either the condition of the problem or what we need to prove. Suppose that we collect the permutations of rows and columns into a regular angle of size $m \times k$ one zero (Fig. 7). Let us prove that $m + k$ is always no greater than $n$. Let's calculate the sum of the numbers in the piece marked on figure by the letter $C$. It is clear that the sum of the numbers in the piece $B$ is equal to $m$ (m columns, in each of which the sum is 1). Similarly, the sum of the numbers in the piece $A$ is equal to $k$ (k ​​lines). Since the total sum of all numbers in the table is $n$, then the share of the piece $C$ remains $n - m - k$. This number is non-negative, since by condition in the table all numbers are non-negative. So, $n - m - k \ge 0$, that is $m + k \le n$, which is what we argued.

Now we can reformulate the problem as follows: there are numbers in the table $n \times n$, and it is known that by lower rearranging the rows and columns it is impossible to

⟦folio 35⟧

Divide in it an angle of zeros of size $m \times k$ such that $m + k > n$; prove that it is possible to choose $n$ non-zero numbers, no two of which appear in any column or row. (It doesn’t matter to us now that the numbers are positive and that the sums in the rows and columns are equal to 1. We have already used these conditions. In what follows, we distinguish only between “zeros” and “non-zeros.”)

If you read the article by M.I. Bashmakov “Matchings and transport networks” in No. 4 of our magazine, then you will easily be informed that our new formulation of the problem is simply a record in the language of “tables” of the matchmaking theorem. Indeed, let us write boys in the rows of the table $n \times n$, and girls in the columns (both $n$ are empty). At the intersection of the $s$th row and the $t$th column we put “non-zero” (an asterisk) if the $s$th boy is familiar with the $t$th girl, and “zero” if he is unfamiliar. Let's get a table (as mathematicians say, a “matrix”) of dating.

Let's take an arbitrary group of $k$ young men. Let's put the corresponding lines first. If none of these boys is familiar with a girl, then according to the column in the first $k$ lines there are zeros. If we rearrange all the columns corresponding to all such girls last (their number is $m$ empty), then we get an angle of zeros of size $m \times k$ (Fig. 8). Each of the first $m - n$ columns has at least one “non-zero” in the first rows, since the corresponding girl has another of our chosen $k$ boys. Since $m + k \leq n$, then $m - n \geq k$, that is, there are at least $k$ such girls. We see that these problems completely coincide with the data of the “matchmaking theorem”. The choice of $n$ brides for all the young men is the choice of $n$ “non-zeros”, standing in different rows and columns.

Now you can read a simple (by induction) proof of the “matchmaking theorem”, which gives a complete solution to the problem. Of course, the properties of the problem to this theorem are not at all necessary. Inductive reasoning can be carried out immediately - by rearranging rows and columns (this is what, for example, reader D. Grigoriev from Leningrad did). In this case, a new proof of the “matchmaking theorem” is obtained*).

*) But, of course, by simply crossing out the last column and the last row in a table that satisfies the conditions of the problem, we can get a table that no longer satisfies this condition - indexing cannot be carried out “roughly” in this way.

⟦folio 36⟧

F18. If you look at the light through two combs with different frequencies of teeth, superimposed on each other, then the luminous areas will intersect with the dark ones. At what speed will these sections move if one of the combs is moved relative to the second at a speed of 1 cm/sec? A stationary comb has 5 teeth per 1 centimeter, while a moving comb has 6.

Solved and e. Let's combine some comb teeth (Fig. 9). Then the next teeth will be at a distance of $1/5$ cm - $1/6$ cm = $1/30$ cm from each other. Let us now move the comb by this distance. Then the pattern of light and dark stripes will shift by $1/5$ cm—the distance between the teeth of the stationary comb. If the comb is shifted by 1 cm, then the pattern of light and dark stripes will shift by $1/5$ cm·30 = 6 cm.

This means that when the comb with a higher frequency of teeth moves at a speed of 1 cm/sec, the light and dark stripes move at a speed of $v = 6$ cm/sec in the same direction in which the moving comb moves.

The picture of alternating light and dark stripes moving at a constant speed is a very convenient model for the movement of waves of any physical nature. If you look at the moving stripes through the slit (Fig. 10), then the slit will periodically be covered with either rear or black stripes:

⟦folio 37⟧

we will see fluctuations. The black and yellow colors of the stripes correspond to two opposite phases of oscillations (Fig. 11). The wavelength is equal to the total width of the light and dark bands. By counting the number of black or yellow stripes passing through the slits in one second, the frequency of oscillations and their period can be determined.

This simple model allows us to understand many physical phenomena and interesting process experiments.

Using black and yellow stripes, you can simulate not only linear waves, but also any others, such as ring waves (Fig. 12). The movement of such ring waves can be shown, for example, the black and yellow Archimedean spiral (Fig. 13). When the spiral rotates through the slit, it will be visible how the waves run towards the center or away from the center, depending on the direction of rotation of the spiral.

If the stripes do not mix, we will get a picture of motionless waves. Such pictures are called rasters. Stationary raster waves should not be confused with standing waves. The standing wave pattern is an alternating black and yellow stripe that periodically changes its color to the opposite.

When several sine waves are superimposed on each other, new waves are created that are no longer sine waves. They are called group waves. Group waves differ from folded sine waves in length, propagation speed, and other parameters. The simplest group waves are beat waves. They are obtained when two waves with unequal, but close to each other, lengths are added.

In order to build a group wave model, two systems of bands need to be superimposed on each other. If these systems are the same, they can be superimposed so that the stripes of one system coincide with the stripes of the other. Such waves will be superimposed by the corresponding ones. If the systems of stripes differ slightly from each other in the distance between the stripes, then we get a picture of beats (Fig. 14). You got a similar picture in your experiments with combs.

It is not difficult to find the wavelength of the beats generated by waves with lengths $\lambda_1$ and $\lambda_2$ ($\lambda_1 > \lambda_2$). If two black bands coincide, then the system of bands with wavelength $\lambda_1$ and $(n+1)$ are close to the system of bands with wavelength $\lambda_2$. This means that the wavelength of the beats is

$$L = n\lambda_1 = (n+1)\lambda_2.$$

⟦folio 38⟧

From the equality $n\lambda_1 = (n+1)\lambda_2$ we find that $n = \frac{\lambda_2}{\lambda_1 - \lambda_2}$.

Because $L = \frac{\lambda_1\lambda_2}{\lambda_1 - \lambda_2}$.

The smaller the differences between the superimposed waves, the greater the length of the group waves. This is used when changing the wavelength of high frequency vibrations. To change, the length of the second wave is selected so that when the waves are added, beats with a long wavelength are obtained. Such beats are easy to see and change using an oscilloscope. Knowing the beat length and the wavelength of some vibrations, it is not difficult to determine the wavelength of the vibrations under study.

The beat waves, which are shown in figure 14, are stationary waves. If one or both wave systems are set in motion, the group waves will also mix. The speed $v$ of group waves can be found in the same way as we find the speed of movement of group waves resulting from the application of combs. It is equal

$$v = \frac{\lambda_1 v_2 - \lambda_2 v_1}{\lambda_1 - \lambda_2},$$

where $v_1$ is the speed of waves with length $\lambda_1$, and $v_2$ is the speed of waves with length $\lambda_2$.

This formula is a generalization of the formula we derived for combs.

In this way, this problem was solved by Vyacheslav Mileshin (Balti, Moldova) and Alexander Karpenko (Lisichansk, Voroshilgovgrad region). Lyutsman Petraschik (Lida, Grodno region) and Sergey Yushman (Vilany, Latvia) solved it in a similar way. Some of the readers, while solving the problem correctly, incorrectly calculated the distance between the teeth of the combs. If a comb contains $n$ teeth per 1 cm, then per 1 cm there are also $n$ spaces between teeth (not $n-1$). Of the two outer teeth on one centimeter, the first belongs to this centimeter, and the last belongs to the next one.

F19. The shape of the communicating vessels is shown in figure 15. Where will the water flow through the tube connecting the vessels if you heat the water in one of the vessels?

Solved and e. Regardless of which vessel is heated, the water warms

⟦folio 39⟧

Even right. Let the liquid in the right vessel heat up. Then it will expand and occupy more volume. If the vessel were cylindrical (Fig. 16), then the pressure of the liquid at the bottom would not change: the reduced density of water would be exactly compensated by the increase in the height of the liquid column. This follows from the fact that the pressure force on the bottom of a cylindrical vessel, on the one hand, is equal to the gravitational force acting on the water in the vessel, and on the other hand, is equal to the pressure of the liquid on the bottom, multiplied by the bottom area: $P = pS$. Since neither the force of gravity nor the area of ​​the bottom changes when the liquid is heated, the pressure on the bottom of the cylindrical vessel does not change either.

In a finite expanding vessel, with the same decrease in liquid density, the increase in column height is less than in a cylindrical vessel. This happens for two reasons: firstly, less liquid expands, which means there is less change in its volume; secondly, when expanding, the water must fill the volume protected at figure. Therefore, the pressure at the bottom of the vessel decreases when the liquid is heated. Since when the liquid in the tube connecting the vessel is in equilibrium, the pressure at its end in the left vessel must be equal to the pressure at its end in the right vessel, the liquid will flow from the left vessel to the right.

Considering in a similar way the heating and expansion of the liquid in the left vessel, we will find that when the left vessel is heated, the pressure on its bottom increases. This means that in this case the liquid will flow from the left vessel to the right.

Vladimir Metlitsky (Angarsk, Irkutsk region) and Alexaンドr Karpenko solved this problem correctly. 8th grade student Efim Kaplun (Vinnitsa, Ukraine) noticed that in a heated vessel, water evaporates more intensely than in one whose temperature does not change. This should affect the flow of water. However, if the vessel temperatures are low, then this effect can be neglected.

F20. A round hole is drilled parallel to the axis of the cylinder of radius $R$ at a distance $\frac{R}{2}$ from its center. The response radius is $\frac{R}{2}$. The cylinder lies on a plate, which is slowly lifted at one end (Fig. 17). Find the maximum angle of inclination of the swing arm at which the cylinder will still be in right balance. The friction coefficient of the cylinder on the plate is 0.2.

⟦folio 41⟧

the cylinder will lose stability at the angle of inclination of the plate

$$\alpha = \alpha_1 = \arcsin \frac{1}{6}.$$

Lyutsman Petrasik, Vladimir Metlitsky, Mikhail Kuznetsov (village of Golchevskaya, Volgoda region), Vladimir Korneev (Moscow), AlexaンドR Karpenko, Alexey Efimov (Moscow) and others correctly solved this problem.

F21. The armature axes of two identical DC motors are also connected to each other. If identical sources with e.g. are connected to the armature windings. d.s. E, then the angular speed of rotation of the anchors without load is equal to $\omega_0$; if the motors are slowed down so that they do not rotate, then current $I_0$ flows through the armature windings. One of the current sources was switched so that the torques of the armatures were opposite. What external moment must be applied to the axis of the armatures in order for them to rotate at a given angular velocity $\omega$? There are few frictional motor claims; The magnetic field of the stat is coefficientd by a permanent magnet.

Solved and e. When the armature is completely inhibited, a current $I_0 = \frac{E}{R}$ flows through its winding. This means that the armature winding resistance is $R = \frac{E}{I_0}$.

When the armature of an electric motor rotates, e.m. occurs in its winding. d.s. induction $E_n$, proportional to the angular velocity of rotation of the armature:
$$E_n = k\omega (k - \text{козффициент пропорциональнойности}).$$
Let us write the law of conservation of energy for an electric motor:
$$EIt = I^2Rt + Nt.$$
Or, reducing the engine operation time $t$, we get
$$EI = I^2R + N;$$
here $N$ is the power consumed by the electric motor from the network, $I^2R$ is the heat loss in the armature winding, $N$ is the power supplied to the load, $R$ is the resistance of the armature winding and $I$ is the current in the winding.

From this equation it follows that in the absence of load ($N = 0$) the current through the armature winding is zero. But according to Ohm's law, the current passing through the winding must be equal to $I = \frac{E - E_n}{R}$. This means that in the absence of load e. d.s. the induction arising in the armature winding is equal to e. d.s. source: $E = E_n$.

After switching one of the sources in the armature windings, e.m. will be excited. d.s. $E'_n = k\omega = E_n \frac{\omega}{\omega_0} = E \frac{\omega}{\omega_0}$. In this case, currents will flow through the windings
$$I_1 = \frac{E - E'_n}{R} = \frac{\left(E - E \frac{\omega}{\omega_0}\right)}{E/I_0} = I_0 \left(1 - \frac{\omega}{\omega_0}\right),$$
$$I_2 = \frac{E + E'_n}{R} = I_0 \left(1 + \frac{\omega}{\omega_0}\right).$$

Moreover, both the work of the sources and the work of the external force will go towards heating the windings. Therefore $EI_1 + EI_2 + N' = I_1^2R + I_2^2R$.

Since $N' = F \cdot v = F \cdot r\omega = M\omega$ (F is the external force applied to the anchor, M is its moment relative to the axis and v = $\omega r$ is the angular velocity of points on the surface of the anchor axis), then, replacing $N'$, $I_1$, $I_2$ and R with their expressions in terms of M, $\omega$, $\omega_0$ and E, we obtain
$$M\omega + EI_0 \left[ \left(1 + \frac{\omega}{\omega_0}\right) + \left(1 - \frac{\omega}{\omega_0}\right) \right] = I_0^2 \frac{E}{I_0} \left[ \left(1 + \frac{\omega}{\omega_0}\right)^2 + \left(1 - \frac{\omega}{\omega_0}\right)^2 \right],$$

⟦folio 42⟧

from where $M\omega + 2EI_0 =$
$= EI_0 \left[ 2 + 2 \left( \frac{\omega}{\omega_0} \right)^2 \right]$
and $M = \frac{2EI_0\omega}{\omega_0^2}$.

F22. Two blacksmiths form a piece of iron. First, they place it on an anvil and hammer it one at a time, then hang it from the ceiling and hit it from different sides at the same time. The force of each blacksmith's blow is the same in both cases. In what case does a piece of iron heat up more in one blow?

Solution. In the second. It is clear that both when a blacksmith strikes a piece of iron lying on an anvil, and when a blacksmith strikes a hanging piece of iron, the same work is performed: the role of the second blacksmith, striking a piece of iron, in the first case is taken on by the anvil. This work goes to heating a piece of iron and, in addition, to performing mechanical work during the expansion of this iron. When iron lies on an anvil, its center of gravity rises as it expands—work is done against gravity. But in the case when the piece is suspended, its center of gravity drops as it expands. This means that in the second case, when not only the work done by the blacksmiths is converted into heat, but also part of the potential energy of a piece of iron (the work done by iron during expansion is negative), it will heat up in one blow more than in the first.

F23. On a horizontal plane there are two identical thin-walled pipes of mass $m$ each. Their axes are parallel, and their radii are equal to $R$. First, one of the pipes will pile up, and the second will roll without slipping towards the first until it collides. The translational speed of the pipe is $v$. How do the speeds of translational motion and the angular speeds of rotation of the pipes depend on time (write graphs)?

The friction coefficient of sliding pipes on a horizontal surface is $k$, the friction between pipes during a collision is negligible, the impact is absolutely elastic.

Solution. Since the friction between the pipes is negligible, we can assume that when the pipes hit, the rotation of one of them is not transmitted to the second. Therefore, when considering the collision of pipes, we can not take into account the rotation of the first (initial moving) pipe.

Let us write down the laws of conservation of energy and momentum for the alignment of pipes:

$$mv_0 = mv_1 + mv_2, \frac{mv_0^2}{2} = \frac{mv_1^2}{2} + \frac{mv_2^2}{2}$$

($v_1$ and $v_2$ are the translational velocities of the corresponding first and second pipes after the collision).

Solving these equations together, we find that $v_1 = 0$ and $v_2 = v_0$, that is, when the pipes hit, they exchange translational velocities - just like when two identical balls hit.

Let us now consider what will happen to the first, initially moving pipe after the impact. In the coordinate system associated with a pipe rolling without slipping along a plane with a speed of $v_0$, the speed of a point touching the plane is equal to - $v_0$. This means that such a pipe rotates around its axis so that the linear rotation speed

⟦folio 43⟧

points on its surface is equal in magnitude to the speed of translational movement of the pipe axis. Therefore, after the collision, the first pipe rotates around its axis with an angular velocity $\omega = \frac{v_0}{R}$.

The friction force $F_{\text{тр}} = kmg$ (Fig. 20) acting on this pipe replaces its rotation and at the same time imparts to it an acceleration $a = \frac{F_{\text{тр}}}{m} = kg$ in the direction of the initial movement of the pipe. By the moment $t$ this pipe will have a translational speed $u'_1 = at = kgt$ and will rotate around the axis with an angular velocity $\omega_1 = \frac{v_0 - kgt}{R}$. The speed of translational movement of the pipe increases, and the speed of rotation of the pipe decreases in proportion to time. By the moment $t_0$, when the speed of translational movement of the pipe axis becomes equal to the linear speed of rotation of the pipe around the axis, the slipping of the pipe relative to the plane will stop, and after that the speed of rotation of the pipe $\omega'_1$, nor the speed of translational movement of the pipe axis $u'_1$ will no longer change. From condition $kgt_0 = v_0 - kgt_0$ we find that $t_0 = \frac{v_0}{2kg}$. At this moment

$$u_1 = \frac{v_0}{2} \text{ и } \omega_1 = \frac{v_0}{2}.$$

Considering the movement of the second pipe in a similar way, we find that the friction force acting on it decreases in its translational motion, $u_2 = v_0 - kgt$, and the angular velocity of rotation $\omega_2 = \frac{kgt}{R}$ increases.

By moment $= \frac{v_0}{2kg}$, the slipping of the pipe relative to the plane will stop. At this moment, the pipe will have a translational speed $u_2 = \frac{v_0}{2}$ and an angular rotation speed around the axis $\omega_2 = \frac{v_0}{2R}$ that will not change in the future.

Graphs of the dependence of the speeds of translational movement of pipes and their angular speeds of rotation on time are shown in figure 21.

The correct solution to this problem was provided by Mikhail Kuznetsov and Sergey Yushmanov.
