---
id: 2025-2-kirichenko-timorin-samopodobie-v-kartinkah-4a8693b2
issue: kvant_2025_2
year: 2025
number: "2"
title: Self-similarity in pictures
authors:
  - Кириченко В. А.
  - Тиморин В. А.
rubric: kaleydoskop-kvanta
rubric_sub: Калейдоскоп
page_first: 34
page_last: 36
page_labels: "34"
tag: TM4J
lang: en
source: kvant_digital
extraction: native
content_sha256: 982e6d642e81ee3396de08e31d7373bc59ee68ceecadd2b1fc2c5defe0867870
prompt_sha256: draft-1
translated_from: content/ru/2025/02/articles/01_kirichenko-timorin-samopodobie-v-kartinkah-4a8693b2.md
source_content_sha256: ea2449d4ec9f7c98ed76737a3f322296c17bda365e05d6c9ceee6cc96749e1e8
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio none⟧

Self-similarity in pictures

Let’s supplement the article “Self-Similarity” with several striking examples.

1. Multi-colored polygonal areas of a self-similar “carpet” on figure 1 transform into each other when reflected

⟦column⟧

Fig 2

Fig 1

(or, what is the same, when rotated by 180q) relative to the appropriate vertex of the central regular pentagon. Each area is reflected relative to the rightmost vertex of the pentagon when viewed from that area. This fractal is obtained from a dynamic system with the rearrangement of pieces, somewhat similar to that shown in $статье.^{2.}$ A similar fractal “carpet”, but only the central polygon - a regular heptagon, is depicted in figure 2. There is also self-similarity here, but it is impossible to see it with the naked eye - you need a microscope with a thousandfold magnification.$^{3.}$ On figure 3 shows the construction of a fractal, which Fig. 3 can be considered as a geometric interpretation of Fibonacci’s words. The first broken line corresponds to $слову_{3}^{w}$, the second $–_{4}^{w}, затем_{5}^{w},_{6}^{w},_{7}^{w},_{8}^{w},_{9}^{w}$, then the rightmost one in the bottom row $–_{12}^{w}$, to the left $–_{15}^{w}$ and $наконец,_{22}^{w}$. A fractal is constructed according to the following rule: if a 1 is found in the sequence, then we draw a single segment; if there is a 0 in the sequence, then draw a unit segment and turn it to the left by 90q, if the 0 is in an even place, and by 90q to the right, if the 0 is in an odd place. Like words, a fractal satisfies the property of concatenation: each

⟦folio none⟧

the leading part of the fractal is the union of two $предыдущих.^{4.}$ At figure 4 a plane with coordinates x is shown; y (the axes of the coordinate system are not shown). On this “dynamic” plane there is a mapping

Fig 5

Fig. 4 motion f, translating point x; y to point $x^{2} y^{2} 1 ; 2 xy$. The orbits of the red dots go to infinity. The orbits of the blue and green points converge to a cycle consisting of two points: the central point figure, which has coordinates 0;0, and the white point in the left green area, which has coordinates 1;0. In this case, blue dots are displayed as green and vice versa. The blue and green dots are darker the slower their orbits approach the periodic 2-cycle, and the red dots, on the contrary, are darker the faster they escape to infinity. This picture is called a basilica. The basilica contains copies of itself at all scales: these copies preserve the angles, although they violate $пропорции.^{5.}$ The dynamic plane of the mapping, defined quite explicitly, but a little more complicated than the example with the basilica, is presented in figure 5. Here, too, there is an attracting cycle of period 2, and the set of points whose orbits never approach this cycle represents a self-similar figure, akin to the Sierpinski triangle. The cycle consists of the points 0 and infinity (this is what you get when dividing by 0), all the yellow and green points are attracted to this cycle, and the yellow points turn into green and vice versa. The yellow points are lighter the faster they are attracted to the cycle, and the green ones are the opposite, $темнее.^{6.}$ The Mandelbrot set (Fig. 6) consists of such points $u_{1} ; v_{1}$ for which the sequences $u_{n}, v_{n}$, given by the recurrence relations $u_{n} 1 u_{n}^{2} v_{n}^{2} u_{n}, v_{n} 1 2 u_{n} v_{n} v_{n}$, remain bounded. Each point of the Mandelbrot set has its own dynamic system, like a basilica.

Fig 6

The corresponding systems undergo significant changes (bifurcations) when crossing the boundary of the Mandelbrot set. In addition, the Mandelbrot set contains numerous smaller copies of itself - in the same sense as the basilica. Material prepared by V. Kirichenko, V. Timorin

⟦folio 34⟧

KVAN T 2025/№2

(For the beginning, see p. 29) b) Let's give an example: let there be 1, 2,..., 9 candies in the bags. Then, as is easy to check, the first will take 0 candies, the second 1, the third 2,..., the tenth 9 candies. A. Glebov

M2820. Let's call the knight's moves, during which it moves two squares horizontally and one vertically, horizontal, and the rest vertical. You need to place the knight on one of the squares of the board 46 and 46, and then alternate its horizontal and vertical moves. Prove that if it is forbidden to visit cells more than once, then no more than 2024 moves will be made.

Divide the board into 23 vertical stripes 46 u 2 and paint the stripes red and blue: paint the first strip red and then alternate colors (see figure).

Let the knight make h horizontal moves. Each of the horizontal moves defines a pair of cells (these are the cells in which the knight is located before and after the move); so we have h pairs of cells. It is easy to see that in such a pair one of the cells is red and the other is blue. In addition, according to the conditions of the problem, a knight cannot perform two horizontal moves in a row, so no cell can be included in two pairs for two different horizontal moves. Therefore, h does not exceed the number of blue cells: h d 11 2 46 1012. Similarly, we show that the number of vertical moves does not exceed 1012. In total, no more than 1012 + 1012 = = 2024 moves were made. A. Gribalko

M2821. A road on a plane is a straight line along which you can move only in one direction.

⟦column⟧

a) Petya and Vasya take turns leading the roads, Petya begins. Only horizontal or vertical roads are allowed; The direction on the road is chosen by the one who draws the road (when creating this road). Can Vasya always act in such a way that after any of his moves it is possible to travel according to the rules from any crossroads to any other, no matter how Petya acts? b) Let there be several (finite set) roads on the plane, any two of which intersect. For what is the smallest m it is always possible to add m roads and make it so that you can drive from any intersection to any other?

Answer: a) always; b) 2. a) While all the roads drawn are parallel, let Vasya continue to draw straight lines parallel to the drawn ones, so that after his move the outer roads are in different directions. When Petya draws a road intersecting them, Vasya can draw a road in the opposite direction on one side of it so that the following condition is satisfied (*): the leftmost road l, the rightmost road r, the highest road t and the lowest road b form a rectangle 3 with circular motion (Fig. 1). Let us show that 1) Vasya will be able to play in such a way that after each of his moves condition (*) is satisfied; 2) if condition (*) is satisfied, then from any intersection you can get to any other. From here the solution will immediately follow. 1) Let, for definiteness, on the next move Petya draws a horizontal path x. If x is drawn between t and b, then Vasya also draws a horizontal line between t and b, so rectangle 3 has not changed. Let us now assume that Petina’s straight line x is located above straight line t. Then let Vasya draw the horizontal Fig. 1
