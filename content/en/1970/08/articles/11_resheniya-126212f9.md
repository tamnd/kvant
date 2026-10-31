---
id: 1970-8-resheniya-126212f9
issue: kvant_1970_8
year: 1970
number: "8"
title: '[Solutions to problems M3—M5]'
rubric: zadachnik-kvanta
page_first: 44
page_last: 55
page_labels: 42-53
tag: YY42
lang: en
source: kvant_digital
extraction: vision
content_sha256: d46ed87daaa8cb190900421c0767c193047b20a0e6c1d50afede667dc2eda7f7
prompt_sha256: draft-1
translated_from: content/ru/1970/08/articles/11_resheniya-126212f9.md
source_content_sha256: 1e1c63e577b116e795ad261ce0f5085972efd2d8c0b4f2f1288fd1dbaa64d376
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

M3. (a) On figure 1, and the plane is covered with heel squares of flowers. The centers of squares of the same color are located at the vertices of the square grid. With what number of colors is a similar filling of the plane possible?

(b) On figure 1, b the plane is covered with hexagons of families and colors so that the centers of hexagons of the same color form the vertices of a lattice of identical regular triangles. With what number of colors is a similar construction possible?

Notes. In the first problem, the number of colors can be one (all squares are the same color) or two (like on a chessboard). In the second problem you can easily find solutions with one color and with a third color. It is advisable to give a complete solution to the problems, i.e., describe all colorings that satisfy the specified conditions. However, please send incomplete solutions if they seem interesting to you. Think, for example, is there a solution with thirteen colors in the second problem?

Solution*)

Now we will consider correct only such filling of the plane with squares (or hexagons) in which the grid corresponding to any one color has the same dimensions and directions of the sides of the squares (or triangles) as the grid corresponding to any other color. In other words, all meshes must be obtained from each other in parallel. Of course, different meshes cannot be painted with the same color. The solution to the problem for general cases (squares and hexagons) is similar, and we will consider both cases at once.

1. Let us first prove that if the filling plane is in the indicated way, then the number of colors is equal to $k^2 + l^2$ in the case of squares and $k^2 + kl + l^2$ in the case of hexagons, where $k, l$ are non-negative integers (but not equal to zero at the same time)**).

*) For the beginning of solving this problem, see «Kvant» No. 7, page 54.
**) There are other formulas that represent the same sets of numbers, for example, $k^2 - kl + l^2$ for hexagons,

⟦folio 43⟧

The unit of length is the distance between the centers of two adjacent squares or hexagons.

Let's draw a grid with thick black lines passing through the centers of squares or hexagons of the same color, say, red (Fig. 2, 3).

In the case of hexagons, we will draw lines in only two directions, so that the grid will not consist of regular triangles, but of rhombuses.

Let $ABCD$ be one square or one diamond of the grid. Let us derive a formula for its area.

In the case of a square, we draw straight lines through the points $A$ and $B$, parallel to the sides of the surrounded squares, and denote the point of their intersection as $M$. The lengths $AM=k$ and $BM=l$ are integers (one of them can be zero). On figure 1 $k=3$, $l=2$. Then $AB=\sqrt{k^2+l^2}$ and the area of ​​$ABCD$ is $k^2+l^2$.

In the case of a rhombus, we draw straight lines through the points $A$ and $B$, parallel to the apsphemas of the hexagons, and denote the point of their intersection as $M$. Angle $AMB$ may turn out to be equal to $120^\circ$ or $60^\circ$. Let's draw straight lines so that it is equal to $120^\circ$. The lengths $AM=k$ and $BM=l$ are integers (one of them can be zero). On figure 2 $k=1$, $l=2$. Then $AB=\sqrt{k^2+kl+l^2}$, and the area of ​​the rhombus is $\frac{\sqrt{3}}{2}(k^2+kl+l^2)$.

We will prove that the number of colors participating in the coloring is equal to the ratio of the area $ABCD$ to the area of ​​one circumferential square (case (a)) or hexagon (case (6)) and is therefore equal to:

in the case of squares $k^2+l^2$,

in case of hexagons $k^2+kl+l^2$

(since the area of ​​one hexagon is $\frac{\sqrt{3}}{2}$).

This follows immediately from the next lemma.

Main lemma. Part $ABCD$, painted with whatever color is involved in the coloring, either represents one square (in case (a)), corresponding to a hexagon (in case (6)), or consists of pieces (for red - four, for other colors - two), from which the same square or hexagon can be folded.

The proof of the lemma is not difficult, and we invite the reader to carry out

⟦folio 44⟧

Fig. 4. The plane is filled with identical figures with an area of ​​13 squares. Try to find an “elementary” piece of a plane filled in this way and glue a torus from it, as we did with a square.

Note. You need to select 13 figures, from them you need to form a polygon that will not be a square, but nevertheless can easily be glued into a torus. This should be done with a sheet of glue paper.

It's on its own. Let us only note that the coloring of all squares (rhombuses) of the bold grid is the same, that is, if you cut out a square (rhombus) $ABCD$ from the plane and superimpose it, say, on an adjacent square (rhombus), then part $ABCD$, painted with any color, will exactly match the part of the neighboring square (rhombus), painted with the same color.

There is another way to present this proof, more beautiful, but requiring some imagination. Let us first restrict ourselves to the case of a square grid. Let us express a square $ABCD$ from the plane and make a tube from it - a cylinder, the colored side on the outside, compatible from the sides $AB$ and $DC$. This tube is delimited by two circles derived from sides $AB$ and $DC$. Let's glue these circles together (by combining point $A=D$ with point $B=C$). For this, the paper tube will have to be solidified, but we still consider its entire painted surface as a single whole, not divided into parts by folds. The surface area of ​​the resulting figure is $k^2+l^2$, and the part of it painted with any of the coloring colors is a square of size $1 \times 1$. We advise you to do all this practically with a square sheet of paper, coloring it with a fifth or more colors.

In the case of hexagons, we will arrive at a similar result if we mark a rectangle in the same way, having one side common with the rhombus $ABCD$ and the other equal to the height of the rhombus.

You can fill the plane with other equal figures in which the areas shaded with different colors are equal. For example, in the solution to problem (a), sent from Kyiv (Belinsky lane 8, apt. 32, the author’s last name is not indicated), it is proposed to fill the plane with figures made up of two squares on the sides $k$ and $l$. Let's say for $k=2$ and $l=3$ (13 colors) the figure will be the same as in figure 4.

II. Now let us be given the number $m=k^2+l^2$ or $n=k^2+kl+l^2$. Let us show that the plane can be filled in accordance with the conditions with squares of $m$ colors or hexagons of $n$ colors.

Let's fill the plane with equal squares or regular hexagons and start cutting them out as follows.

Let's paint one of them red. Let's count $k$ squares (hexagons) from it in one direction, then turn it by $90^\circ$ for squares and $60^\circ$ for hexagons and count $l$ squares (hexagons) in a new direction, and we will also paint the square (hexagon) in which we arrive in red. On the segment connecting the centers of two red squares (hexagons), as on the side, we will construct a square (a) or a regular triangle (6). By attaching equal squares (regular triangles) to it, we get the centers of all squares (hexagons), which must be painted red; moving all the soybeans in parallel

⟦folio 45⟧

A collection of red squares (hexagons), each time we will get a new collection of unpainted squares (hexagons) and paint it with a new color until we have painted the entire plane. According to what was proven above, the number of colors will be equal to $k^2+l^2$ in case (a) and $k^2+kl+l^2$ in case (b).

III. What natural numbers can be represented as $k^2+l^2$ or $k^2+kl+l^2$? To write down the first few of these numbers, it is convenient to create two tables: table 1 for $k^2+l^2$, table 2 for $k^2+kl+l^2$.

The numbers below the diagonal repeat those already written and do not need to be written. Some numbers appear in the table twice; the corresponding cells are highlighted. This means that with such a number of colors there are two significantly different ways of filling the plane. Now it’s easy to find and write these numbers in ascending order.

First table: 1, 2, 4, 5, 8, 9, 10, 13, 16, 17, 18, 20, 25, 26, ...
Second table: 1, 3, 4, 7, 9, 12, 13, 16, 19, 21, 25, 27, 28, ...

Suppose we have already written down these numbers to some point and are looking for the next largest number.

The red lines drawn on the first table help to do this. To explain how they are carried out, we note that in the first table each number is equal to the square of the distance from the center of the cell in which it stands to point 0 in the upper left corner (we take the side of the cell as a unit of length). Therefore, if we draw several circles with center 0, then they will divide our numbers (that is, the centers of the cells in which they stand) into groups in ascending order. If you try to draw similar lines in the second table by hand, it may seem that they are straight. But this, of course, is not true. In fact, these graphs correspond to the form

$$k^2+kl+l^2=c=\text{const}$$

in a coordinate system with origin 0 and axes going: axis $k$ - to the right, axis $l$ - down. Moving on to another pair of variables: $x=k+l$, $y=k-l$, you can see that these are ellipses elongated in the direction of the $y^*$ axis).

In a sense, we have the answer, but perhaps it can be simplified. For example, if in some other problem we get the answer: all numbers of the form $k^2+l^2+m^2+n^2$, two $k$, $l$, $m$, $n$ are integers, then it can be rewritten as follows: any non-negative integer, since all natural numbers can be represented in this form. It may be in our sequence

*) Those who read the book by N.B. Vasiliev and V.L. Gutenmacher “Straights and Curves”, of course, noticed that the red lines are the level lines of the functions $k^2+l^2$ and $k^2+kl+l^2$ on the plane $(k, l)$.

⟦folio 46⟧

Are all natural numbers included, starting from a certain place? To prove that this is not so, you can use the dotted line system.

Let us draw a red circle with center 0 of radius $n$ in the first table. The centers of all cells containing numbers less than or equal to $n^2$ lie inside or on the edge of a sector of this circle with a central angle of $45^\circ$. Therefore, all such cells lie inside the figure; they are obtained from this sector if we add to it a strip of width 1 bordering it. The area of ​​this figure is less than $\frac{\pi n^2}{8} + 3n + 4$.

Hence, among the first $n^2$ natural numbers there are $\frac{\pi n^2}{8} + 3n + 4$, representable as $k^2 + l^2$. For large $n$ the second number of the first is approximately $\frac{\pi}{8}$. In fact, since some numbers in the table are equal, there are even fewer numbers of the form $k^2 + l^2$. It is easy to see that the fraction of numbers representable as $k^2 + kl + l^2$ is even smaller.

**M4.** Given the segment $AB$. Find points $C$ on the plane of the set such that in triangle $ABC$ the median drawn from vertex $A$ is equal to the altitude drawn from vertex $B$.

Solution

The editors have received many letters with solutions to this problem, but almost all of them are incomplete. Many readers have forgotten that when finding the geometric locus of points (GLP), it is necessary to clearly verify two things: 1) all points of the found set satisfy the conditions; 2) all points satisfying the conditions belong to the found set. Requirement 1) a lot of things were not taught. We will present two solutions to the problem: one is purely geometric, the second is using the coordinate method.

First decision. Let's start with 2). Let us be given a segment $AB$ and a path $C$—a point satisfying the conditions, $AD$—the median of triangle $ABC$. Let us complete the triangle to a parallelogram by extending the median $AD$ to the point $E$ so that $AD=DE$. There are two possible cases here: the angle $AEB$ is acute or obtuse.

(a) Let the angle $AEB$ be acute (Fig. 5, a). Let's draw $BF \perp AC$, $AK \parallel BF$, then in the right triangle $AEK$ the leg $AK$ is equal to half the hypotenuse $AE$, therefore $\angle AEB=30^\circ$.

⟦folio 47⟧

(6) Let angle AEB be of type (Fig. 5, 6). Carrying out BF ⊥ AC, AK || BF, we obtain, similarly to case (a), that ∠AEK=30°, therefore ∠AEB=150° (the difference from case (a) is that now points K and B lie on opposite sides of E).

So, if C is the desired point, then segment AB is visible from point E at an angle of 30° or 150°. As is known, all such points E are located on two circles O₁ and O₂, which are divided by the chord AB into arcs of 300° and 60° (Fig. 6, a), and, therefore, all points C are on the same circles O'₁ and O'₂, obtained from O₁ and O₂ by parallel transfer to the segment l=AB in the direction from B to A (Fig. 6, 6).

Now we prove that any point M of circles O'₁ and O'₂ belongs to the required set of points. Let M be an arbitrary point of one of these circles; then by drawing MK=AB, MK||AB, we get point K on one of the circles O₁ or O₂ (Fig. 7, a, 6). On figure 7, a' BF ⊥ MA, AL||BF, AL=BF, then (from ΔAKL) AL=1/2 AK, i.e. the point M satisfies the conditions. Similarly on figure 7, 6 BF ⊥ MA, AL=BF, AL||BF, ∠AKB=150°, ∠AKL=180°−∠AKB=30°, i.e. AL=1/2 AK, and point M also satisfies the conditions. So, all points O'₁ and O'₂, except points N and A, satisfy the conditions.

Note that many readers who solved the geometric problem received parts of circles O'₁ and O'₂ as an answer. (Figure 8, a was obtained, for example, by V. Mashanov from the city of Grodno, figure 8, 6 by S. Ivanenko from the city of Fedosia and figure 8, by A. Alyaeva from the Penza region.) The correct solution (although slightly different from the one given here) was added by L. Stolyarov from the city of Penza.

Second solution. (A slight simplification of the solution sent by A. Grishkov from Tomsk.) Let us introduce a rectangular coordinate system with the origin at point A, let point B have coordinates (2; 0), and the desired point C have coordinates (x; y). Let AF be the median in triangle ABC, BK ⊥ AC (Fig. 9). It is easy to show that point F has coordinates (x+2/2; y/2). Then AF²=(x+2/2)²+y²/4. According to the conditions BK²=AF², therefore

⟦folio 48⟧

Fig. 8, a. Fig. 8, b. Fig. 8, p.

from the similarity of triangles AKB and ACD it follows that $\frac{BK^2}{AK^2} = \frac{CD^2}{AD^2}$ or
$$\frac{\left(\frac{x+2}{2}\right)^2 + \frac{y^2}{4}}{4 - \left[\left(\frac{x+2}{2}\right)^2 + \frac{y^2}{4}\right]} = \frac{y^2}{x^2}.$$

Transforming (1), we get
$$y^4 + (2x^2 + 4x - 12)y^2 + (2x + x^2)^2 = 0.$$

This is the equation connecting the coordinates of the required points. Some readers further wrote that it defines a fourth-order curve, which is quite difficult to draw.

In fact, it turns out that the left side of equation (2) is factorized:
$$[(x+1)^2 + (y+\sqrt{3})^2 - 4] [(x+1)^2 + (y-\sqrt{3})^2 - 4] = 0.$$

Fig. 9. Fig. 10.

⟦folio 49⟧

You can guess about it, for example, like this.

Let us introduce the notation: $y^2 = z$. Then (2) is a quadratic equation with respect to $z$. Let's factorize its left-hand side. To do this, let's find roots (2).

$$z_{1,2} = \frac{12 - 2x^2 - 4x \pm \sqrt{(12 - 2x^2 - 4x)^2 - 4(2x + x^2)^2}}{2} =$$

$$= \frac{12 - 2x^2 - 4x \pm \sqrt{48(3 - x^2 - 2x)}}{2} = 6 - x^2 - 2x \pm 2\sqrt{3(3 - x^2 - 2x)} =$$

$$= (\sqrt{3 - x^2 - 2x} \pm \sqrt{3})^2.$$

Equation (2) can now be represented as follows:

$$\left| z - (\sqrt{3 - x^2 - 2x} + \sqrt{3}) \right| \left| z - \sqrt{3 - x^2 - 2x} - \sqrt{3} \right|^2 = 0$$

or

$$\left| y^2 - (\sqrt{4 - (x + 1)^2} + \sqrt{3}) \right| \left| y^2 - (\sqrt{4 - (x + 1)^2} - \sqrt{3}) \right|^2 = 0.$$

(see figure 10, where one of these sets is red and the other is green).

Let us transform (4) further:

$$\left| y - \sqrt{4 - (x + 1)^2} + \sqrt{3} \right| \left| y + \sqrt{4 - (x + 1)^2} - \sqrt{3} \right| [\dots] [\dots] = 0;$$

hence we get (3)*.

Ninth-grader P. Kriksunov from Kiev and some other readers who wrote us solutions to this problem noticed that the following more general problem can be solved in a similar way: find a set of points $C$ such that in triangle $ABC$ the ratio of medians $AD$ to height $BF$ is equal to the given number $k$ (either of the two solution methods described above is suitable).

M5. In the set $E$, consisting of $n$ elements, $m$ different subsets (different from $E$ itself) are identified so that for every two elements from $E$ there is exactly one of the given subsets that contains both of these elements.

Prove that $m \geq n$. In what cases is a solution possible?

Solution

From readers' letters one can judge that this task is extremely difficult, but interesting. Strictly speaking, here we are dealing with two problems: 1) prove that $m \geq n$, 2) in what cases is a solution possible?

As for the first problem, only $A$ solved it completely. Creatures from Leningrad. His proof is based on one of the basic theorems of linear algebra, which states that if there are more $n$-vectors than $n$, then they are linearly dependent.

For those who are familiar with this concept, it will be interesting to come up with such a proof. As for the second problem, it is shown, and this is not surprising, since it will be shown below that it is related to one known, but unsolved mathematical probleme.

For ease of presentation, some readers suggested other formulations of the problem. Here are two of them.

*) Equation $(x - a)^2 + (y - b)^2 = c^2$ defines a circle with center at point $(a; b)$ of radius $c$ (see, for example, I. M. Gelfand, E. G. Glagoleva, A. A. Kirr ilov, Method of coordinates, “Nauka”, 1968).

⟦folio 50⟧

Fig. 11.

a) Students from the same school often gather in groups and go out to eat ice cream. After such a visit, they quarrel so much that no two of them eat ice cream together after that. By the end of the year, they found out that in the future they could only go to the ice cream parlor one by one. Prove that if the number of students visited by this time was more than 1, then it is not less than the number of students in the school.

6) Let there be $n$ points. Through every two points there is exactly one straight line, and each straight line contains no more than $(n-1)$ points. We need to prove that the number of lines is at least $n$.

Are these tasks equivalent to the original one?

In any case, it is convenient, when thinking about this problem, to imagine the elements as “points”, and the bases as “lines”, passing through these points and doing for yourself figure like our figure 11 and 12. (In general, it is impossible not to ensure that all the lines are straight; as problem M36, figure 12 shows, it is impossible to correct it so that the red line is straight, so the problem 6) is not equivalent to the original one.)

Next, we present the solution to the problem, following the instructions of the author of the problem, N. Bourbaki*), and also, for convenience, we rewrite the conditions of the problem.

Given $n$ different elements and has a system $m$ of sets composed of these elements, and:

1) no set of our system contains all the elements at once;
2) every two of the given $n$ elements occur in one of the set of the system;
3) if two elements occur in one of the sets, then they do not appear together in any of the other sets of the system.

Let us prove that $m \geq n$.

Let us give some example of such arrangement of elements. Let $n=5$ and there be elements: $a, b, c, d, e$. Let's create such a system of a set of these elements;

$(a, b), (a, c, e,), (b, e), (b, c), (b, d), (a, d), (d, e), (c, d)$.

Obviously, it satisfies conditions 1), 2), 3). Here $m=8$, and by the way $8 \geq 5$.

To make the proof more clear, we will sometimes refer to this example.

Proof. Note that $n>2$ and that it is sufficient to prove the inequality $m \geq n$ for a system of sets containing at least two elements.

1. The system consists of at least two sets, then by condition 2) this set would contain all the elements at once, which contradicts conditions 1).

*) See N. Bourbaki, Set Theory, Mir, M., 1965, p. 220.

⟦folio 51⟧

2. Each element is included in at least two sets of the system. If an element were included in only one set, then by virtue of 2) it must contain all $n$ elements, which contradicts 1).

3. One and the same element cannot be included in all sets of the system at once. Let some element, call it $x$, be included in all sets of the system. Then, by condition 3), no two sets contain identical elements, with the exception of the element $x$. Therefore, no two elements other than $x$ occur in any of the set, but this contradicts 2).

4. Let us associate each element with the number of the set of the system in which it is included, that is, we count how many times it is repeated in this system. In the example, the element $a$ is mapped to the number 3, the element $b$ to 4, etc.

What set of the system is comparable to the number of elements it contains? In the example of the first set the number 2 is associated, the second set is associated with 3, etc.

The sum of all numbers corresponding to elements is equal to the sum of all numbers corresponding to sets. In the example $3+4+3+4=2+3+2+2+2+2+2+2=17$.

In fact, if we consider two elements to be different when they are included in different sets, then both sum to the number of elements of all sets of the system.

5. Notation. Let's take one of those elements that correspond to the smallest number, i.e., which is included in the smallest number of the set of the system. In the example, we can take either $a$, or $c$, or $e$; let's take $a$. Let us denote this element by $a_n$, and the number of the set in which it is included by $k_n$. In the example $a_5=a$, $k_5=3$. By virtue of paragraphs. 2 and 3 we have $2 \leqslant k_n < m$.

The sets that include $a_n$ will be denoted in some order by $A_1$, $A_2$, ..., $A_{k_n}$, and the rest by $A_{k_n+1}$, ..., $A_m$. In the example $A_1=(a, b)$, $A_2=(a, c, e)$, $A_3=(a, d)$, $A_4=(b, e)$, ..., $A_8=(c, d)$.

Consider the first $k_n$ sets $A_1$, $A_2$, ..., $A_{k_n}$. Reasoning in the same way as in point 3, we see that no two of them contain the same elements, with the exception of $\dot{a}_n$. Therefore, we can take one element from each of these sets and denote them respectively by $a_1$, $a_2$, ..., $a_{k_n}$. We denote the remaining elements in some order by $a_{k_n+1}$, $a_{k_n+2}$, ..., $a_n$. In the example $a_1=b$, $a_2=c$, $a_3=d$, $a_4=e$; then $A_1=(a_1, a_5)$, $A_2=(a_2, a_4, a_5)$, $A_3=(a_3, a_5)$, $A_4=(a_1, a_4)$, $A_5=(a_1, a_2)$, $A_6=(a_1, a_3)$, $A_7=(a_3, a_4)$, $A_8=(a_2, a_3)$.

Now let us denote the numbers corresponding to the elements $a_1$, $a_2$, ..., $a_{k_n}$, ..., $a_{n-1}$ in the same order by $k_1$, $k_2$, ..., $k_{n-1}$. For example, that the element $a_n$ corresponds to the number $k_n$, and it is the smallest of all the numbers $k_1$, $k_2$, ..., $k_{n-1}$, $k_n$.

Finally, let us denote the numbers corresponding to the sets $A_1$, $A_2$, ..., $A_m$ in the same order by $s_1$, $s_2$, ..., $s_{k_n}$, ..., $s_m$.

Let us once again pay attention to how we numbered the elements and sets.

First, $k_n$ is the smallest of the numbers $k_1, k_2, ..., k_{n-1}$.

Secondly, $k_n$ is the number of the last of the sets that contain the element $a_n$, and, thus, the element $a_n$ is not included in the sets $A_{k_n+1}$, ..., $A_m$.

The set $A_i$ contains the element $a_i$, but does not contain the elements $a_j$ if $1 \leqslant i \leqslant k_n$, $1 \leqslant j \leqslant k_n$ and $i \neq j$. In addition, according to paragraph 4, $k_1 + \dots + k_n = s_1 + \dots + s_m$.

⟦folio 52⟧

6. If the element $a_i$ does not belong to some set $A_j$, then $k_i \geqslant s_j$. Indeed, let the set $A_j$ not contain the element $a_i$ and consist of $s_j$ different elements. then the element $a_i$ must occur with each of these elements in some of the remaining sets of the system. On the other hand, no two of these elements can ever occur in these sets, since they have already occurred in $A_j$. Therefore, the number of sets in which the element $a_i$ is not less than $s_j$.

7. Consider the first $k_n$ set $A_1, A_2, \dots, A_{k_n}$ and the first $k_n$ elements of $a_1, a_2, \dots, a_{k_n}$. They are chosen in such a way that each set $A_i$ contains an element $a_i$ with the same number, but does not contain elements with other numbers, then, according to paragraph 6, $s_1 \leqslant k_2, s_2 \leqslant k_1$ if $k_n = 2$ and

$$\begin{align*}
s_1 &\leqslant k_2, \quad s_2 \leqslant k_1, \quad \dots, s_{k_n} \leqslant k_1, \\
s_1 &\leqslant k_{k_n}, \quad s_2 \leqslant k_{k_n}, \quad \dots, s_{k_n} \leqslant k_{k_n-1},
\end{align*}$$

if $k_n > 2$.

In the example $k_n = 3$ and

$$\begin{align*}
2 &= s_1 \leqslant k_2 = 3, \quad 3 &= s_2 \leqslant k_1 = 4, \quad 3 &= s_3 \leqslant k_1 = 4, \\
2 &= s_1 \leqslant k_3 = 4, \quad 3 &= s_2 \leqslant k_3 = 4, \quad 3 &= s_3 \leqslant k_2 = 3.
\end{align*}$$

8. Adding up all the inequalities, we get that

$$(k_n - 1)(s_1 + s_2 + \dots + s_{k_n}) \leqslant (k_n - 1)(k_1 + \dots + k_{k_n})$$

or

$$s_1 + s_2 + \dots + s_{k_n} \leqslant k_1 + \dots + k_{n}.$$

9. Teller we can prove the inequality $m \geqslant n$ required in the problem. Let's assume that $m < n$. Let's compare two amounts

$$S = (s_1 + s_2 + \dots + s_{k_n}) + s_{k_n+1} + \dots + s_m$$

And

$$K = (k_1 + k_2 + \dots + k_n) + k_{k_n+1} + \dots + k_n.$$

Note that we have renumbered the set in such a way that the element $a_n$ does not belong to the set $A_{k_n+1}, \dots, A_m$; this means $s_{k_n+1} \leqslant k_n, \dots, s_m \leqslant k_n$ and even more so $s_{k_n+1} \leqslant k_{k_n+1}, \dots, s_m \leqslant k_m$, since $k_n$ is the smallest of all numbers $k_i$. In this case, since $m < n$, we get: $k_{k_n+1} + \dots + k_n > s_{k_n+1} + \dots + s_m$, but then $S < K$, and this contradicts item 4.

The proof that $m \geqslant n$ is complete.

10. Let's try to find out in what cases equality is possible. If $m = n$, then from items 8, 9 and 4 it follows:

$$k_1 + \dots + k_{k_n} + \dots + k_n = s_1 + \dots + s_{k_n} + \dots + s_n.$$

Obviously, for this it is necessary that the equality

$$k_1 + \dots + k_{k_n} = s_1 + \dots + s_{k_n}$$

and all the inequalities from paragraph 8 were reduced to equalities. Since $k_n$ is the smallest of $k_i$, we have

$$s_{k_n+1} = \dots = s_n = k_{k_n+1} + \dots + k_n.$$

Next we consider two cases.

(a) $k_n = 2$. In this case, as is easy to see, the following set system is possible (Fig. 9): $(a_n, a_1), (a_n, a_2, a_3, \dots, a_{n-1}), (a_1, a_2), (a_1, a_3), \dots, (a_1, a_{n-1})$. For any $n$ it satisfies the conditions of the problem.

(b) $k_n > 2$. In this case, we obtain that all inequalities in paragraph 7 must be

⟦folio 53⟧

rushes into equality. Comparing all these equalities, we obtain that $s_1=s_2=\dots=s_{k_n}=k_1=k_2=\dots=k_{k_n}$.

And the same as for case (a): $s_{k_n+1}=\dots=s_n=k_{k_n+1}=\dots=k_{n-1}=k_n$.
It is obvious that one of the numbers $s_1, s_2, \dots, s_{k_n}$ is at most one of the numbers $k_{k_n+1},\dots,k_{n-1}$ and, therefore, $s_1=s_2=\dots=s_n=k_1=k_2=\dots=k_n=l>2$.

As a result, we find that in this case the following condition is satisfied:

4) which set contains exactly $l$ distinct elements and which element is included in exactly $l$ distinct sets.

For this it is necessary that $n=l(l-1)+1$. Indeed, consider some element $x$. It must appear exactly in the $l$ set, therefore all these sets contain all $n$ elements just as $x$ must occur with all elements. In addition, they cannot contain the same elements, since they all contain the element $x$. From here we obtain the required equality.

For $l=3$, i.e. $n=7$, it is easy to construct the required set system (Fig. 10). But the question of for which $n$ type $l^2-l+1$ a set of $n$ elements there is a subset system that satisfies conditions 1), 2), 3) and 4) turns out to be very difficult.

Such a system has a special name: a finite projective plane of order $l-1$. (On Fig. 12 a projective plane of order 2 is depicted, consisting of 7 points and 7 lines.) It is easy to prove that for any finite projective plane the following property is also satisfied, “dual” to property 2):

5) Any two sets from our system have a common element (obviously only one); in other words, which two lines intersect at one point.

Let us show how to construct a finite projective plane of order $p$ (with $n=p^2-p+1$), where $p$ is a prime number. To do this, you need to use “numbers” from $p$-arthmetic (see the article “Comparisons modulo and remainder arithmetic”, «Kvant» No. 5, pp. 27-33) - arthmetic of remainders modulo $p$. In this kind of mathematics, if $p$ is prime, you can divide any “number” by any other non-zero number. Let us use a point to define the triple “number” $(x_1, x_2, x_3)$, considered up to proportionality (i.e., the triples $(x_1, x_2, x_3)$ and $(kx_1, kx_2, kx_3)$ define the same point). Let’s agree that the three $(0, 0, 0)$ should not be considered a dot.

The straight line is given by a triple of numbers $(a_1, a_2, a_3)$ (except for the triple $(0, 0, 0)$), considered up to proportionality. The point $(x_1, x_2, x_3)$ accepts a straight line $(a_1, a_2, a_3)$ if and only if $a_1x_1+a_2x_2+a_3x_3=0$.

Check that for such specific lines and points all conditions 1)–5) are met. Make sure that for $p=2$ you get exactly the example of a projective plane of order 2 that is chosen for figure 12.

Similarly, we can prove that there exists a projective plane of order $p^k$, where $p$ is a prime and $k$ is any natural number. It is proven that projective planes of order $N$ do not exist for an infinite number of $N$ (in particular, for $N=6$, $N=14$). But for $N=10$ it is unknown whether a projective plane of order $N$ exists or not: no computer can simply enumerate all possible combinations.

You can read about the theory of finite projective planes and related problem combinators in the book “Combinatorial Mathematics” by G. J. Reiser (“Mir”, 1966, series “Matematika Collection Library”).

A. Toom, J. Rabbot, W. Gutenacher
