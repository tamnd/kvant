---
id: 1972-10-kaplun-leybovich-papernov-konechnyie-parketyi-a410301a
issue: kvant_1972_10
year: 1972
number: "10"
title: Finished parquets
authors:
  - Каплун В. И.
  - Лейбович В. Г.
  - Папернов Е. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 27
page_last: 31
page_labels: 25-29
tag: 990R
lang: en
source: kvant_digital
extraction: vision
content_sha256: 165f66fdc053676918d0e2fbae1be8a51a744ab55505d3feb28f9244f3978400
prompt_sha256: draft-1
translated_from: content/ru/1972/10/articles/07_kaplun-leybovich-papernov-konechnyie-parketyi-a410301a.md
source_content_sha256: 46544dc6262fc22609c09f942357e6e909752aca291d1fb1bf958a637707744f
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 25⟧

ENDED PARQUETS

V. I. Kaplun, V. G. Leibovich, E. L. Papernov

Measure seven times, cut once

Imagine that you wanted to pave the bathroom floor with tiles or make general parquet in the room. In this case, the only condition is set: that the tiles (parquet flooring) be the same. The first thing that comes to mind is to try to make parquet from regular polygons. You can read about such parquets in the article by A. N. Kolmogorov “Parquets from regular polygons” *, where endless parquets are considered, that is, the tiles covered the entire plane. Moving to confined areas (such as a room) leads to significant complications.

Problem 1. Prove that it is impossible to pave a rectangular room with regular triangles or hexagons.

Problem 2. Come up with an example of a rectangular room, the chest of drawers cannot be replaced with any square tiles.

As you can see, we can’t do without “wrong” figures. They often make the task very simple. For example, it is not difficult to select a rectangular tile that can be used to cover a given rectangular room (Fig. 1). Later we learned how to freeze

*) See «Kvant», No. 3, 1970.

install parquet in a wide variety of areas. At the same time, we will use only polygonal parquet flooring and always demand that in each specific case they are all the same. Note that if we covered a certain figure with parquet, we simultaneously divided it into polygons—tiles—with straight segments. Therefore, in the future we will often use the words “breaking” and “cutting”. For convenience of presentation, we will give a special meaning to the word “cutting”: this is a division in which the boundaries of the tiles form segments that cut our area “through and through”. figure 2 shows an example of a partition that is not a cut, and figure 3 shows an example of a cut.

Let's now see how you can cut a rectangle into equal triangles. This will be one of our main tasks. For example, by drawing a diagonal, we cut the rectangle into two equal triangles.

Problem 3. Prove that an arbitrary rectangle can be cut into any integer number of triangles.

A natural question arises: is it possible to cut a rectangle into an odd number of equal triangles? The answer to this question will follow from more general results, for which we

⟦folio 26⟧

Let us prove a theorem about cutting infinite regions into equal triangles.

To formulate it, we need one important concept.

Let there be some family of lines on the plane. We will say that this family has a direction system and, if a finite number of lines can be distinguished on the plane, that each line from this set is parallel to one of them. For example, the directions highlighted in red on figure 4 are the directions for the set of lines shown on this figure.

Fig. 1.

Fig. 2.

Fig. 3.

Main theorem. Let the plane be cut into equal triangles; model the following cases are possible:

1) if the cutting triangles are rectangular with angles of 30°, then the system of guides of the family of cutting straight lines consists of either 3, 4, or 6 elements;

2) if the cutting triangles are rectangular, but are not triangles from case 1, then the guide system can consist of only 3 or 4 elements;

3) finally, if the cutting triangles are not straight, then there are only 3 guides.

Let us note one property of cuts that will play an important role in further discussions.

Let there be an arbitrary triangle included in the cut (ΔABC on Fig. 5). then each of the sides of this triangle determines one of the cutting lines. Each of these straight lines has additional triangles attached to it on the other side. Consider, for example, the side AC of triangle ABC on figure 5 and the corresponding straight line l (on which it lies). Let us consider one of the triangles attached to AC that has a common point with AC, different from points A and C (such a triangle is very wide). then this triangle - let's denote it A'B'C' - can occupy only two positions in relation to ΔABC (Fig. 5, a and b). Proof of this fact (based on the equality of triangles ABC and A'B'C' and the fact that our partition is

Fig. 4.

Fig. 5, a.

Fig. 5, b.

Fig. 6.

⟦folio 27⟧

cutting) we leave to the reader as an easy exercise, a warm-up for more difficult tasks that will occur very soon.

Now we can proceed directly to the proof of the theorem. Let us first consider case 3. Let $ABC$ be an arbitrary triangle of our parquet (Fig. 6). Let, for the purpose of definition, let its angle $A$ be the largest (in the case of an equilateral or equilateral triangle, one can, as will be clear from what follows, take an arbitrary one from the corresponding angles). Let us show that the second triangle, applied to the side containing the vertex $A$, can only form the configuration represented by figure 5, $6$ (from now on we will simply write “attached like “6”)). Indeed, since the angle $A$ is the largest, then $\angle A \geq 60^\circ$. Consequently, if the triangle $A'B'C'$ is attached according to type “a”, then it is no longer possible to attach a triangle to the other side containing the vertex $A$. We leave the proof of this simple fact to the reader. Let us consider the case $\Rightarrow A = 60^\circ$ separately.

It follows from this (this is also a problem) that the parquet can only look like figure 7 (some of the triangles on it are painted over for smoothness).

Let's move on to case 2. Obviously, here you can build the same parquet as in case 3. But in this case, you can build exactly one more (task!) parquet (see Fig. 8).

In case 1, of course, both parquets can be implemented, case 2 and one more parquet (again a problem!), which is given in figure 9.

Now, having in hand the theorem about infinite parquets, we can consider cutting finite figures.

Theorem 1. If a square is cut into equal triangles, these triangles are necessarily straight-level and their cent number is equal.

Indeed, a finite parquet is either part of one of the infinite parquets depicted in Figures 7-9, or has the form of a regular $n$-gon (this is the problem) (Fig. 10).

In a very square room, triangular parquet can only look like in Figures 7-9. But the sides of the square themselves must be straight cutting lines, so case 3 disappears. Consequently, the partition consists of right triangles. (Note that when the triangles on Fig. 8 are equilateral, we get a parquet of type Fig. 10.). If the parquet looks like in figure 7, then among the directed generatrices only two are mutually perpendicular. They must coincide with the direction of the side of the square. In this case, each of the categories of the cutting triangle must be laid an integer number of times on the side of the square. Let the side of the square be equal to $a$, and the categories lay in it the corresponding two pairs of mutually perpendicular guides.

Finally, we note that a parquet of type Fig. 9 cannot be realized on a square. This can be verified as follows. Let the length of the hypotenuse of the cutting triangle be equal to $a$, then the corresponding categories are $\frac{a}{2}$ and $\frac{\sqrt{3}}{2} a$. But if some straight parquet of type Fig. is 9, then (prove!) one of its sides is equal to $k \frac{\sqrt{3}}{2} a$, and the other $n \frac{3}{2} a$, where $n$ and $k$ are integers. But then

⟦folio 28⟧

The sides of the rectangle turn out to be unmeasured, and therefore a square cannot be obtained.

Theorem 2. If a rectangle is cut into equal triangles, then all these triangles are rectangles and their cent number.

The proof of this theorem is no different from the proof of Theorem 1. Try to prove it yourself.

Having made sure that the parquet floors for rectangular pillars are not very diverse, they naturally ask the question: what is the situation with other figures, for example, with a triangle? It is clear that an equilateral triangle can be cut into two equal triangles. What about others?

Problem 4. Prove that if a triangle is cut into two equal triangles, then it is equilateral.

Problem 5. Given an arbitrary triangle; How many equal triangles can it be cut into?

Still, the triangle, as you can see, can be cut. You might think that this is the case in all polygons.

However, this is not true. We will now deal with the simplest example of an uncut fugue.

Let's consider the question of cutting trapezoids. See figure 11 for an example of a trapezoid that can be cut into equal triangles. Let us show, however, that there are trapezoids that cannot only be cut, but also divided into equal triangles. The existence of such trapezoids is based on the existence of immeasurable segments. Recall that the segments $a$ and $b$ are immeasurable if the ratio of their lengths is an irrational number *). Let us call the segments $a_1, \dots, a_n$ mutually immeasurable if no $a_r$ can be represented in the form $a_r = k_1 a_1 + \dots + k_n a_n$, where $k_1, \dots, k_n$ are rational numbers ($k_r = 0$).

Let us take a trapezoid with sides $l, m, n, p$ (Fig. 12), where the segments $l, m, n, p$ are mutually immeasurable. Let's assume that it can be divided into equal triangles. Let's look at side $l$. Our partition will divide it into parts, each of which is one of the sides of the partition triangle (Fig. 13). Therefore $l = k_1 a + k_2 b + k_3 c$, where $k_1, k_2, k_3$ are non-negative integers. Similar reasoning for the remaining sides of the trapezoid gives a system of equalities

$$\begin{align*}
l &= k_1 a + k_2 b + k_3 c, \\
m &= k_1 a + k_5 b + k_6 c, \\
n &= k_7 a + k_8 b + k_9 c, \\
p &= k_{10} a + k_{11} b + k_{12} c
\end{align*}$$

where $k_1, k_2, \dots, k_{12}$ are non-negative integers. We assumed that the partition is feasible. This means that, given $k_1, k_2, \dots, k_{12}$, these equalities can be considered as a system of equations for $a, b$ and $c$.

Problem 6. Show that in the general case, the pairwise non-measurability of the numbers $a_1, \dots, a_n$ does not imply their mutual non-measurability.

Problem 7. Show that the joint intercept of the three equations has the form

$$\begin{align*}
a &= r_1 l + r_2 m + r_3 n, \\
b &= r_4 l + r_5 m + r_6 n, \\
c &= r_7 l + r_8 m + r_9 n
\end{align*}$$

where $r_1, \dots, r_9$ are rational numbers.

Substituting the values ​​$a, b$ and $c$ into the four equations, we get $p =$

*) In what follows, a segment and its length are denoted the same way.

⟦folio 29⟧

$$= r_{10}l + r_{11}m + r_{12}n, \quad r_{10}, r_{11}, r_{12} \text{ — разциональные числа. Но отрезки } l, m, n \text{ взимно несоизмеримы. Мы пришли к противоречию; следовательно, трапецю со взимно несоизмеримыми сторонами разбит на равные треугольники невозможно.}$$

Problem 8. Show that a boundary with sides $n = \sqrt{2}, m = \sqrt{3}, l = \sqrt{7}, p = \sqrt{5}$ cannot be divided into equal triangles.

Now take a rectangular piece and glue a cylinder out of it (Fig. 14). If we cut the resulting cylinder at any angle to the base, we get a parallelogram (Fig. 15). Thus, the problem of cutting a cylinder with straight lines is equivalent to cutting a parallelogram. But here the situation is in many ways similar to a rectangle: it is easy to cut a parallelogram into an even number, it is impossible to cut a parallelogram into an odd number of equal triangles, and whether it can be divided into an odd number of triangles is unknown. We have seen that for a trapezoid, the possible partitioning is related to the solvability of a certain system of equations. For a parallelogram we have only three independent equations corresponding to the quantities defined by the parallelogram, that is, the two sides and the angle at the base. Therefore the problem is conditional. It is important to note that the angle $\alpha$ at the base depends entirely on us, and we can choose it as convenient for us.

Another figure that can be glued together from a rectangle, the Möbius strip, has interesting properties in relation to cutting. A Möbius strip is obtained if we glue the rectangle $ABCD$ (Fig. 16) as follows: glue $AB$ to $CD$ so that $A$ is glued to $C$, and $B$ to $D$, that is, $AB$ "turns over." The Möbius strip has a number of remarkable properties.

(See, for example, “Encyclopedia of Elementary Mathematics”, M., 1966, vol. 5, p. 500).

If we make a cut at an acute angle to the edge of the surface, we get an isosceles trapezoid (Fig. 17). In it the angle $\alpha$ is arbitrary and $a + b = AD + BC$. It is not difficult to choose $\alpha$ so that $3b = 4a$, then, by making six cuts, we will get 7 equal triangles.

Problem 9. Show that the Möbius strip can be cut into any number of equal triangles.

Now that the reader has become familiar with some of the ideas and methods of cutting, we leave him to explore the theories of cutting and partitioning on his own. We present a number of possible problems in this area.

Problem 10. Show that every right-angled triangle can be cut into any number of triangles, starting from two, similar to the original one.
