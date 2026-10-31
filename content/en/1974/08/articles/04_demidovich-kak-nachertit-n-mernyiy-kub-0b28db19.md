---
id: 1974-8-demidovich-kak-nachertit-n-mernyiy-kub-0b28db19
issue: kvant_1974_8
year: 1974
number: "8"
title: How to draw an n-dimensional cube?
authors:
  - Демидович Н. Б.
rubric: osnovnye-stati
page_first: 24
page_last: 28
page_labels: 22-26
tag: ATNJ
lang: en
source: kvant_digital
extraction: vision
content_sha256: e93fffbf2f46ef3a06e7d9cdc46921308c799f84af391f2df0df4c1017c045b0
prompt_sha256: draft-1
translated_from: content/ru/1974/08/articles/04_demidovich-kak-nachertit-n-mernyiy-kub-0b28db19.md
source_content_sha256: 5b8570b7ba66f5972c8399574d43848e4c66cd01fab75fd4da0451c01de9f7eb
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 22⟧

Segment, square, cube...

What is the difference between a line segment, a square and a cube? A segment is part of a straight line, a square is part of a plane, and a cube is part of space. What do they have in common, except for the word hour in their definition? It turns out that there is a deep analogy in the process of their construction. In fact, the process of constructing a square for a given segment can, for example, be described as follows:

from the ends of this segment we construct perpendiculars to it so that these perpendiculars lie in the same plane; On each perpendicular, on one side of a given segment, we lay off segments of the pseudodine and then connect the ends of the resulting segments.

Let us now write down the process of constructing a cube for a given square:

from each vertex of a given square we construct perpendiculars to the plane of the square (that is, to the two sides of the square converging at this vertex) so that these perpendiculars are in the same space; on the perpendiculars on one side of the square we lay out segments equal in length to the edge of the square; Through the ends of these segments we draw straight lines, parallel to the edges of the square (that is, we build a square parallel to the given one).

In this entry, the artificiality and inappropriateness of the phrase “chimba these perpendiculars were in the same space” is striking: after all

our space is generally one! But let's banter and describe the process of one more construction:

from each vertex of a given cube we construct perpendiculars to all the edges (?!) converging in it so that these perpendiculars are in the same space; on these perpendiculars on one side of the cube (?!) we lay out segments equal in length to the edge of the cube; through the ends of these segments we draw straight lines, parallel to the edges of the cube and equal in length (maybe we build a cube parallel to this one (?!)).

Geometrically, such a “construction” is, of course, impossible - if only because in our space it is impossible to draw more than three pairs of perpendicular lines. But logically, this reasoning is completely coherent and leads to the concept of a “four-dimensional” cube (that is, a cube in which 4 pairwise perpendicular edges converge at each vertex). Moreover, continuing the description of the construction “by induction”, we will arrive at the concept of a “five-dimensional”, “six-dimensional” and, in the general case, an “n-dimensional” cube. According to this reasoning, an ordinary cube is a “three-dimensional” cube, a square is a “two-dimensional” cube, and a segment is a “one-dimensional” cube (Fig. 1, 2, 3).

The question is, are there real objects that correspond in their properties to an n-dimensional cube (n=1, 2,...)? It turns out that they exist; one such object will be discussed in the next chapter.

⟦folio 23⟧

Vertex table of n-dimensional cube
A segment (one-dimensional cube) has two ends (two vertices). Let's denote one of the ends of the numbers as 0, and the other as 1. We get a table at the vertices of the segment:
0
1

The set of vertices of a square (two-dimensional cube) is divided into two subsets of vertices of sides parallel to each other. Let us denote the corresponding vertices of the sides with the same numbers (0 or 1); to distinguish them from each other, we add the number 0 to the left of the designated vertices of one side, and the number 1 of the other. The table of vertices of the square takes the following form:
00 10
01 11

Similarly, from the table of vertices of a square, a table for a cube is constructed:
000 010 100 110
001 011 101 111

Next is the table at the vertices of the “four-dimensional” cube:
0000 0010 0100 0110 1000 1010 1100 1110
0001 0011 0101 0111 1001 1011 1101 1111

The process of constructing such tables can be continued indefinitely. These tables represent algebraic images of n-dimensional cubes; in this case, the vertex of the n-dimensional cube corresponds to some ordered set of n zeros and ones, called the coordinates of the vertex.

Let us now describe the basic properties of the vertices and edges of an n-dimensional cube.

1) Each edge of an n-dimensional cube contains exactly two of its vertices; all the corresponding coordinates of these vertices are the same, with the exception of one: at one end of the edge it is equal to 0, and at the other - 1. It is this coordinate that characterizes the direction of the edge.

2) All edges in one direction are parallel to each other and perpendicular to the edges of any other direction.

3) The number of different directions is n. All of them are described by basic edges connecting vertex 00... 0 with vertices

00 . . . 01
00 . . . 10
.

.

01 . . . 00
10 . . . 00

4) Exactly n edges emerge from any vertex of an n-dimensional cube. All of them are perpendicular to each other in pairs.

For n=1, 2, 3 the properties are checked directly (check!). For n>3, we will construct the described properties of the vertices and edges of the cube (we leave it to you to verify their internal consistency).

⟦folio 24⟧

Concurrent Engineering

Along with a real purely algebraic image - a table of vertices - a $n$-dimensional cube can also be associated with a real purely geometric image - a drawing.

figure 1 shows a drawing of a cube. Let us note the following properties:

1) The parallel edges of the cube remain parallel in the drawing.
2) The perpendicular edges of the cube in the drawing are not parallel.
3) Different vertices of the cube in the drawing do not merge into one.

In other words, the drawing of the cube appears as a back falling on a horizontal platform from illumination of the wired model of the cosmic cube with parallel rays of light that do not lie in the plane of any of the boundaries.

It turns out that if such parallel design is applied to a cube of any dimension $n$, then a flat drawing of a $n$-dimensional cube will be obtained, which has the third properties indicated above. But before we prove this, let's calculate

How many vertices are there in a $n$-dimensional cube?

Let $A$ be an arbitrary vertex of a cube with coordinates $a_n, a_{n-1}, \dots, a_2, a_1$. Since $a_i$ is equal to either one or one, we can consider the coordinates of this vertex as a double representation of some number $\varepsilon$:

$$\varepsilon = a_n \cdot 2^{n-1} + a_{n-1} \cdot 2^{n-2} + \dots + a_2 \cdot 2 + a_1$$

(then the double notation $\varepsilon$ is:

$$\hat{\varepsilon}_2 = a_n a_{n-1} \dots a_2 a_1).$$

The vertices of a $n$-dimensional cube correspond to all possible sets of zeros and ones ($a_n, a_{n-1}, \dots, a_2, a_1$); each such set corresponds to a completely defined number $\varepsilon$; the number $\varepsilon + 1$ is obtained from the number $\varepsilon$ according to the following rule: all right-hand digits $a_1, a_2, \dots, a_j$, which are units in a row, are replaced by zeros, the first zero (or missing) digit $a_{j+1}$ on the right is replaced by one, and the rest (if any) remain unchanged. Let us imagine, for example, in the double system the numbers 0, 1, 2,..., 15:

$$\hat{0}_2 = 0, \quad \hat{4}_2 = 100, \quad \hat{8}_2 = 1000,$$

$$\hat{1}_2 = 1, \quad \hat{5}_2 = 101, \quad \hat{9}_2 = 1001,$$

$$\hat{2}_2 = 10, \quad \hat{6}_2 = 110, \quad \hat{10}_2 = 1010,$$

$$\hat{3}_2 = 11, \quad \hat{7}_2 = 111, \quad \hat{11}_2 = 1011,$$

$$\hat{12}_2 = 1100,$$

$$\hat{13}_2 = 1101,$$

$$\hat{14}_2 = 1110,$$

$$\hat{15}_2 = 1111.$$

It is easy to see that the number $2^n$ in the dual number system is represented as ones with $n$ zeros, and the number $2^{n-1}$ as a set of $n$ ones. This means that there are $2^n$ different double numbers (from zero to $2^n - 1$) of bit depth no higher than $n$; therefore, the number of vertices of a $n$-cube is also $2^n$.

Let's now try to build

Drawing of a $n$-dimensional cube

Let's draw two straight lines on the plane at an angle to each other - use their bases. Let us plot on one of them (let's call it the first) on one side of the intersection point $2^n - 1$ times the scale $a$, and on the second - $n$ times the scale $b$ (Fig. 4, $a$). Let's number the ends of the scale segments on the first number line

$$1, 2,..., 2^n - 1,$$

and on the second - numbers

$$1, 2,..., n.$$

Through the end of each scale segment we draw a straight line parallel to the other main line. We get the grid coordinates. To each node of this grid we assign a pair of integers $(X, Y)$ - the coordinates of the node along the first and second directions (the point of intersection of the axis

⟦folio 25⟧

Fig. 4: $a$ - four-dimensional cube; $\delta$ - five-dimensional cube

new lines has coordinates $(0,0)$). Place the vertex of the cube with coordinates $(a_n, a_{n-1}, \ldots, a_2, a_1)$ at the node of the resulting grid with oblique coordinates

$$\left( \sum_{i=1}^{n} a_i \cdot 2^{i-1}, \quad \sum_{i=1}^{n} a_i \right)^*.$$

Thus, the first oblique coordinate of the node, which

$$*) \text{Знак } \Sigma \text{ (сигма)} \text{ — это знак суммирования, } \sum_{i=1}^{n} b_i = b_1 + \ldots + b_n.$$

we will draw a vertex of the cube, equal to the number of this vertex, and the second is its weight $a_1 + \ldots + a_n$ (that is, the total number of coordinate units of the vertex).

If two vertices of a $n$-dimensional cube differ in only one coordinate, then we connect the corresponding images of vertices on an oblique coordinate grid with a straight line segment - this segment will serve as an image of the edge of our cube.

This completes the construction of a drawing of a $n$-dimensional cube (in the figure -

⟦folio 26⟧

ke 4, a shows a drawing of a four-dimensional cube, and figure 4, b - a five-dimensional cube). To make sure that in the general (n-dimensional) case the drawing of an n-dimensional cube is the result of a parallel projection of the cube onto a plane, let’s check

When drawing properties

Property 3) is obviously satisfied: different numbers correspond to different vertices, and therefore their images have different first coordinates, and therefore do not coincide.

Let us now check property 1)—preservation of edge parallelism. Take any two parallel edges of the cube. Let us denote the coordinates of the vertices of the first edge by $\tilde{a}^1$ and $\tilde{a}^2$:

$$\tilde{a}^1 = (a_n^1, a_{n-1}^1, \dots, a_i^1, a_1^1),$$
$$\tilde{a}^2 = (a_n^2, a_{n-1}^2, \dots, a_i^2, a_1^2);$$

and the coordinates of the vertices of the second edge are through $\tilde{b}^1$ and $\tilde{b}^2$:

$$\tilde{b}^1 = (b_n^1, b_{n-1}^1, \dots, b_i^1, b_1^1),$$
$$\tilde{b}^2 = (b_n^2, b_{n-1}^2, \dots, b_i^2, b_1^2).$$

The direction of the edge here is characterized by the $i$-th coordinate.

We have:

$$a_j^1 = a_j^2, \quad j \neq i.$$

Without loss of generality, we can assume that

$$a_i^1 = b_i^1 = 0,$$
$$a_i^2 = b_i^2 = 1.$$

Let us now consider the images $\tilde{a}^1, \tilde{a}^2, \tilde{b}^1, \tilde{b}^2$ of these four-dimensional ones on the coordal coordinate grid. Let us draw through the images of vertices $\tilde{a}^1$ and $\tilde{b}^1$ straight lines parallel to the first coordinate direction, and through the images of vertices $\tilde{a}^2$ and $\tilde{b}^2$ - straight lines parallel to the second direction (Fig. 5). The intersection points of these lines are denoted by $\tilde{a}$ and $\tilde{b}$, respectively. We get two triangles: $\tilde{a}^1 \tilde{a}^2$ and $\tilde{b}^1 \tilde{b}^2$. We calculate the length of the sides $\tilde{a}^1 \tilde{a}^2$ - by construction, it is equal to the modulo difference of the first coordinate coordinates of the vertices $\tilde{a}^1$ and $\tilde{a}^2$:

$$\left| \sum_{j=1}^{n} a_j^1 \cdot 2^{j-1} - \sum_{j=1}^{n} a_j^2 \cdot 2^{j-1} \right| =$$
$$= \left| \sum_{j=1}^{n} \left( a_j^1 - a_j^2 \right) \cdot 2^{j-1} \right| =$$
$$= \left( a_i^2 - a_i^1 \right) \cdot 2^{i-1} = 2^{i-1}.$$

The length of the sides $\tilde{b}^1 \tilde{b}^2$ is also equal to $2^{i-1}$. Length of the second side of the triangle
