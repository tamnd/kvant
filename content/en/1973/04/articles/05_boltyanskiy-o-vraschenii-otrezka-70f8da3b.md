---
id: 1973-4-boltyanskiy-o-vraschenii-otrezka-70f8da3b
issue: kvant_1973_4
year: 1973
number: "4"
title: About the rotation of a segment
authors:
  - Болтянский В. Г.
rubric: osnovnye-stati
page_first: 26
page_last: 30
page_labels: 24-28
tag: CP76
lang: en
source: kvant_digital
extraction: vision
content_sha256: 36287416de41de6d83e7cdf7cf0153ac25282e9ea64cc16df7c920fc9d386c5c
prompt_sha256: draft-1
translated_from: content/ru/1973/04/articles/05_boltyanskiy-o-vraschenii-otrezka-70f8da3b.md
source_content_sha256: 84baf6a88945d945daa067a2f1c1f9a87e1d7bcb3e4c4f047c1d43b550ad57d2
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 24⟧

About the rotation of a segment

V. G. Boltyansky

1. It is clear that a segment of length 1 can make a full revolution, all the while being in a figure of area π/4, namely in a circle of diameter 1 (Fig. 1). But isn’t it possible for a segment of length 1 to make a full revolution while moving in a figure of smaller area? At first glance, this seems unlikely: it seems that a circle of diameter 1 is the most “economical” (in terms of area) figure, in which a segment of length 1 can make a full revolution. However, this is not true!

In 1918, A. S. Bezikovich proved that there is a figure of a suitably small area, moving in which a segment of length 1 can make a full revolution. More precisely, if we give any positive number ε (for example, ε = 0.000001), then we can construct a figure of area ε, inside which a segment of length 1 can make a full revolution. Besicovitch proposed simple geometric ideas with which we can prove this amazing fact. However, in order to turn these ideas into a complete proof, he had to perform rather cumbersome calculations, so that the whole reasoning as a whole turned out to be complex (the proof, similar to Besikovich’s proof, is given on pp. 258-263 of the book “Convex Figures” by I. M. Yaglom and V. G. Boltyansky).

Not long ago, Academician I.M. Vinogradov told me a short and elegant proof of this theorem. He came up with this proof immediately after Besikovich told him about his theorem, and began to print it once. With the kind consent of I.M. Vinogradov, I will present his proof here.

2. First of all, let's look at the geometric ideas of A. S. Bezikovich.

It is clear that it is enough to construct a figure of small area, inside which a segment of length 1 can be rotated through an angle of 60°: then applying three such figures to each other, we obtain a figure within which a segment can be rotated through an angle of 180°.

A segment of length 1 can be rotated 60° inside an equilateral triangle with height 1 (Fig. 2). Now let's cut this triangle with a height into two parts and put these parts on top of each other. Inside the resulting figure (Fig. 3) you can rotate segment AB to position AC; in addition, the segment DE parallel to AC can be rotated to position DF. But move segment AB to position DF in this

⟦folio 25⟧

We look at the figure shown in figure 3, segments $AH$ and $DH$ and a sector of radius 1 with center $H$, as shown in figure 4. In the resulting figure it will already be possible to rotate the segment from position $AB$ to position $DF$: it will be necessary from position $AC'$ move the segment along $AH$ to position $HK$, then rotate it inside the sector to position $HL$, and then move it along $HD$ to position $DE$.

What did we get as a result? The area of ​​the figure shown in figure 3 exists less than the area of ​​the first equilateral triangle (since the two halves of this triangle overlap). When moving from figure 3 to figure 4, we add only the segments $AH$, $DH$ (they have zero area) and a sector with center $H$, and the area of ​​this sector can be made as a small angle (you only need to take the point $H$ far away so that the angle $AHD$ is small).

What if you cut the equilateral triangle not into two, but into four parts (Fig. 5)? Then, by making parallel transfers of these parts (so that they overlap), we get a figure (Fig. 6), in which we can rotate a segment of length 1 by an angle $15^\circ$, then “jump” to a parallel position, rotate it again by $15^\circ$, then again and again by $15^\circ$. And since our segment is not allowed to “jump,” we will have to, as in figure 4, add segments and sectors (Fig. 7). In the figure shown in figure 7, a segment of length 1, continuously moving, can turn through an angle $60^\circ$. In this case, the sum of the areas of the added sectors can be made as a small angle (you just need to take points $H_1$, $H_2$, $H_3$ far enough away). At the same time, the area of ​​the figure depicted in figure 6 is significantly less than the area of ​​the original equilateral triangle, since the four parts into which this triangle is cut overlap many times.

Now it becomes clear to them the general direction of the proof: it is necessary

⟦folio 26⟧

these parts, having an area less than ε, where ε is a given positive number.

3. The reported messages, however, do not yet provide proof. This is just the direction in which to look for it. The hardest part is ahead: we need to figure out how to move the parts so that, due to multiple overlaps, we get a figure with a sufficiently small area. The method of shifting a part and calculating the area, proposed by I.M. Vinogradov, is as follows.

Let's take an arbitrary natural number m and divide the base of the equilateral triangle into 2$^m$ equal parts. By connecting the division points with the vertex, we obtain a partition of the equilateral triangle into 2$^m$ parts, which are called cliæ. Let us, in addition, draw straight lines parallel to the base and dividing the height of the triangle into m equal parts; We denote these lines, starting from the vertex, by $l_1, \dots, l_{m-1}$ (Fig. 8).

Let's consider two adjacent wedges. The straight line $l_1$ cuts out identical segments in them. Let’s move these wedges so that these segments “hop” through each other (Fig. 9), and now “glue” these two wedges, that is, the figure obtained from these two wedges will be considered as a single whole for all further parallel transfers. We will perform such gluing for each two adjacent

⟦folio 27⟧

wedges: 1st clem with 2nd, 3rd with 4th, ..., (2$^m$—1)th with 2$^m$.

The figure obtained by gluing two wedges is divided into parts as follows: we select from it a triangle with a vertex on the straight line $l_1$ and four “tails”. Each of the “tails” is a triangle with height $1/m$ (recall that the height of the original equilateral triangle is 1). The base of each “tail” is equal to $\frac{a}{m \cdot 2^m}$, where $a = \frac{2}{\sqrt{3}}$ is the side of the original equilateral triangle. Consequently, the total area of ​​all four “tails” is equal to $2 \cdot \frac{a}{m^2 \cdot 2^m}$, and since there are a total of $2^{m-1}$ pairs of glued wedges, then the total sum of the areas of the “tails” is equal to $a/m^2$. The area $S_1$ of the equilateral triangle $\Delta_1$ cut from the original triangle by the straight line $l_1$ (Fig. 10) is equal to $\frac{a}{2m^2}$. Thus, the total sum of the areas of all the “tails” is $2S_1$. Let us now throw out all these “tails” from consideration, filling in the sum of their areas. With all further cdws, the sum of the areas of the discarded “tails” can only decrease (due to overlap).

The triangles remaining after discarding all the “tails” (the number of these triangles is $2^{m-1}$),

We will now consider them as new wedges. Shifting them together, we obtain from these $2^{m-1}$ new wedges an equilateral triangle with height $1 - \frac{1}{m}$ (Fig. 11). Now it is no longer the straight line $l_1$, but the straight line $l_2$ that cuts off from it the small equilateral triangle $\Delta_2$, and it is very much equal to the triangle $\Delta_1$. By shifting and gluing new wedges in the same way as before, we will again obtain “tails”, the total sum of areas of which is equal to $2S_1$, and “completely new” wedges, the vertices of which lie on the straight line $l_2$.

From these “completely new” wedges, moving them, we obtain an equilateral triangle with height $1 - \frac{2}{m}$, and by gluing together “completely new” wedges in pairs, we again obtain “tails”, the sum of the areas of which is equal to $2S_1$, etc.

Let's do all the $m$ steps of such a construction (at the last $m$ step you will get just an equilateral triangle equal to $\Delta_1$, so you don’t need to move anything). We see that nothing remains from the first initial wedges after cutting off the “tails”. In other words, the area of ​​the figure resulting from the first initial wedges after all the shifts and pecking is less than the total sum of the areas of all “tails”, then

⟦folio 28⟧

ect less than

$$m \cdot 2S_1 = 2m \cdot \frac{a}{2m^2} = \frac{a}{m} = \frac{2}{\sqrt{3}m} < \frac{2}{m}.$$

It is now clear that by taking $m$ large enough, we can make this area as angle-small. Proof complete!

4. And yet, maybe our intuition will not deceive us? Maybe a circle of diameter 1 is really the smallest figure in area in which a segment of length 1 can make a full revolution, but not among any figures (as we have seen, this is not true), but among all of them? After all, those figures of a fairly small area, which were discussed above (see Fig. 7), are very “loose”, scattered and, in any case, non-convex. Let us recall that a figure is called convex if, together with each two points, it entirely contains the segment connecting them (Fig. 12). So, is it true that among all convex figures in which a segment of length 1 can make a full revolution, a circle of diameter 1 has the smallest area?

It turns out that this is not true either. Let's explain what's going on here. Let $F$ be a figure in which a segment of length 1 can make a complete revolution. Take some straight line $l$ and draw two supporting lines $l_1$ and $l_2$ of the figure $F$, parallel to $l$, that is, two lines between which the figure $F$ is “sandwiched” (Fig.13). Since the segment that has completed a full revolution in the figure $F$ must at some point take a position perpendicular to the line $l$, then the distance between the lines $l_1$ and $l_2$ (it is called the width of the figure $F$ in the direction perpendicular to $l$) is not less than 1. So, the width figures $F$ in any direction not less than 1.

It seems completely natural to assume that a figure on a small area should have a width in all directions equal to 1 (otherwise the area, apparently, would be larger). Let's see where this assumption leads us.

First of all, the question arises: what is a figure whose width in all directions is equal to 1? They often answer that such a figure can only be a circle with diameter 1. However, this is not true! There are an infinite number of different shapes whose width is 1 in all directions; they are called figures of constant width 1. Two such figures are shown at figure 14. Both figures are bounded by two circles, and the distance between these straight lines is 1. The first of the figures depicted in figure 14 has a special name: *Reuleaux triangle* (named after the mechanic who first became interested in the property of this figure and tried to use it in the design of mechanisms).
