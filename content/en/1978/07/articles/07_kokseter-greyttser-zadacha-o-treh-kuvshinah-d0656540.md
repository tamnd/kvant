---
id: 1978-7-kokseter-greyttser-zadacha-o-treh-kuvshinah-d0656540
issue: kvant_1978_7
year: 1978
number: "7"
title: Three jug problem
authors:
  - Коксетер Г. С. М.
  - Грейтцер С. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 31
page_last: 33
page_labels: 29-31
tag: 47TY
lang: en
source: kvant_digital
extraction: vision
content_sha256: 092e8e3dbeeb2ddc868ca35dec1383a867cfc62cdecdf0db0ec36c0fab0a44a4
prompt_sha256: draft-1
translated_from: content/ru/1978/07/articles/07_kokseter-greyttser-zadacha-o-treh-kuvshinah-d0656540.md
source_content_sha256: b6db19ffb37918ae28c2db900fd3df9de9904c349e75623073e254a36e899701
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 29⟧

The three jug problem

The proposed article is an open source from the books of American mathematicians G. S. M. Coxeter and S. L. Greitzer “New Encounters with Geometry”, the Russian translation of which will soon be published in the series “Library of the Mathematical Circle” by the publishing house “Nauka”. The material was prepared for publication by L. Savina.

Now we will look at the application of geometry to solving problems in which it is necessary to divide a liquid into certain portions using tools that would seem inconceivable for this purpose. To solve this, we need so-called trilinear coordinates, which we will now describe.

Typically, graph paper is used to plot points with given Cartesian coordinates. For our purposes, it is better to use trilinear paper, that is, paper on which three systems of parallel lines are drawn, dividing it into small equilateral triangles. Let's draw on such paper a large equilateral triangle ABC with sides running along the grid lines. For an arbitrary point P in this plane, we define the numbers x, y, z as the distances from this point to the lines BC, CA and AB, respectively, and for each of these lines the distance will be positive if the point lies on the same side of this line as the triangle ABC, and imprinted otherwise. We will call the resulting point of numbers (x, y, z) trilinear coordinates of urine P relative to triangle ABC. Note that for points lying in coordinates to describe a situation in which three variables are involved that have a constant sum. If one of these quantities x, y or z remains constant and the other two change, then the point (x, y, z) moves in a straight line parallel to one of the sides of triangle ABC. In particular, the straight lines on which the coordinates BC, CA and AB lie are described by the equations

$$x = 0, y = 0, z = 0,$$

and vertices A, B, C have coordinates (h, 0, 0), (0, h, 0), (0, 0, h).

This is exactly the situation that will arise in the case when h liters of liquid are poured into the following vessels: in the first there are x liters, in the second there are y liters and in the third there are z liters. Gradually, the transfusion of liquid from the second vessel into the third corresponds to the movement of a point with trilinear coordinates (x, y, z) relative to triangle ABC with a height equal to h, along the straight line x=const in the direction corresponding to a decrease in y and an increase in z. If each vessel can collectively hold h liters (we will denote this situation by the symbol [h; h, h, h]), then each of the coordinates x, y, z can take any value from 0 to h, and the set of points that can be reached by somehow pouring liquid from one vessel into another - we will call this set the area of ​​operation - is given by inequalities.

$$0 \leq x \leq h, 0 \leq y \leq h, 0 \leq z \leq h,$$

⟦folio 30⟧

and coincides with the entire triangle ABC.

The case [h; a, b, c]. Here the three given vessels have capacities a, b, c and h≥a>b>c. Let's set the task: you need to measure out a certain amount of d liters of liquid, pouring a lot of it from one vessel to another; At the same time, we cut a small amount to either completely empty one vessel, or fill another to the brim (and perhaps my others will happen at the same time). The domain of operations is now specified by the inequalities

$$0 \leq x \leq a, \ 0 \leq y \leq b, \ 0 \leq z \leq c,$$

which typically define a regular or irregular hexagon bounded by six straight lines

$$x = 0, \ x = a, \ y = 0, \ y = b, \ z = 0, \ z = c.$$

But in some cases, this area can turn into a pentagon, trapezoid, parallelogram, or (as we have already seen) covers the entire equilateral triangle.

We will assume that the numbers a, b, c, h and d are integers.

Figures 1 and 2 illustrate the situation [8; 7, 6, 3]: 8 liters of liquid are somehow poured into containers of 7, 6 and 3 liters. Here the domain of operations is the hexagon $0 \leq x \leq 7, \ 0 \leq y \leq 6, \ 0 \leq z \leq 3$, bounded by the lines $x = 7, \ z = 0, \ y = 6, \ x = 0, \ z = 3, \ y = 0$. Prilinear coordinates of the hexagon vertices (relative to

for an equilateral triangle with height 8) - (7, 1, 0), (2, 6, 0), (0, 6, 2), (0, 5, 3), (5, 0, 3), (7, 0, 1). Let’s say that the first vessel contains 3 liters of liquid, the second one also contains 3; then the third vessel contains 2 liters of liquid. This liquid distribution corresponds to a point with coordinates (3, 3, 2). The six directional ones emanating from this point indicate six possible transfusion operations. the direction from point (3, 3, 2) to point (5, 3, 0) corresponds to the process of emptying the triangle of the vessel: the liquid contained in it is poured into the first vessel; in the opposite direction - from point (3, 3, 2) to point (2, 3, 3) - the process of filling the triangle of the vessel: it must receive liquid from the first. the direction from point (3, 3, 2) to point (0, 6, 2) corresponds to the process of emptying the first vessel, the contents of which are poured into the second vessel; at the same time, the second vessel is completely filled, etc.

Let's say that we need to measure 4 liters of liquid (that is, get 4 liters in at least one of the vessels). First of all, we note that at the very first cut transfusion of liquid, we move from the internal point of the area of ​​​​operations (in our case, from the point (3, 3, 2)) to its boundary point - these are the conditions. For example, the red broken line at figure 2 specifies one of the possible ways to move from point

⟦folio 31⟧

ki (3, 3, 2) to the point (4, 4, 0) (and thus dividing eight liters into two equal portions). It is easy to see that the links of the broken line are always parallel to the sides of triangle ABC, and the broken line “turns” only when it hits the boundary of the region. If now, without setting ourselves the task of measuring four liters, we draw all sorts of broken lines from the point (3, 3, 2) (with links parallel to the sides of triangle ABC, and with ends on the boundary of our hexagonal region), then sooner or later we will find ourselves at all the boundary points of our hexagon. The same is true for any integer point of a given area of ​​operations (both internal and boundary). This means, whatever the distribution of eight liters of liquid among the vessels for the case [8; 7, 6, 3], by “topping up” and “emptying” the vessels, you can measure any number of liters of liquid (less than eight).

On figure 3 the case [10; 8, 7, 6]: Pour 10 liters of liquid into vessels containing 8, 7 and 6 liters together. The operation area here is again a hexagon. In this case, for any distribution of ten liters among vessels, it is easy to measure $d=1, 2, 3, 4, 6, 7, 8$ and 9 liters of liquid. But if from the very beginning none of the vessels contains five liters of liquid, then these 5 liters are in no way a path passing through the points (0, 5, 5), (5, 0, 5) and (5, 5, 0), closed, and it cannot be reached from any other path. In general, if $h=2d \geq a > b > c > d$, then in the situation [h; a, b, c] by emptying and adding vessels, $d$ liters of liquid cannot be measured, no matter how these $h$ liters were distributed among the vessels, unless there were $d$ liters in one of the initial vessels.

Let us consider another case [10; 8, 6, 4] - pour an even number of liters of liquid into vessels with four containers (Fig. 4). Here the area of ​​operations is a pentagon. From figure 4 it is clear that if initially each of the vessels contained an even number of liters, that is, the starting point is with four coordinates (for example, (6, 2, 2)), then we will never be able to measure out an odd number of liters of liquid.

The tasks corresponding to the case [h; a, b, c], where $h=a=2d=b+c$. In this case, the operation area is a parallelogram with vertices (a, 0, 0), (c, b, 0), (0, b, c), (b, 0, c). Figures 5 and 6 show two solutions to the task corresponding to the case [8; 8, 5, 3] with the initial liquid distribution (8, 0, 0); you need to measure 4 liters of liquid. In other words, two people have a vessel filled with eight liters of some liquid, and two empty vessels with a capacity of 5 liters and 3 liters, although these 8 liters of liquid are divided equally.

The first thing to do is fill either a 5 liter container, as in figure 5, or a 3 liter container, as in figure 6.

Fig. 3.

Fig. 4.
